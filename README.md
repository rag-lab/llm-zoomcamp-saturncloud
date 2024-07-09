# LLM Zoomcamp Saturn Cloud

Saturn Cloud starter code for LLM Zoomcamp 




#Pip installs

pip install python-dotenv
pip install tqdm notebook==7.1.2 openai elasticsearch pandas scikit-learn ipywidgets
(to use the opensource llm)
pip install -U transformers accelerate bitsandbytes sentencepiece


run lamma
docker run -it \
    -v ollama:/root/.ollama \
    -p 11434:11434 \
    --name ollama \
    ollama/ollama