
# NeuralNet-Tokenization-Papers

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4011767.svg)](https://doi.org/10.5281/zenodo.4011767)

This repository hosted by ThaiTour, encompasses every notebook, model, and pickled dataset along with other supporting materials utilized during research pertaining to automated source code generation and auto-completion using deep learning. For an insightful purpose of each file and model, please refer to the paper.

## 📓 Notebooks

The notebooks focused on the data cleaning and preparation processes, and the training of AWD-LSTM and AWD-QRNN neural networks, and Transformer models like GPT-2, BERT, and RoBERTa.

## 📖 Models post-tokenization

The models and vocab files resultant from each tokenization process and utilized for AWD-LSTM and AWD-QRNN neural nets are embedded here. Also, the models and vocab files employed for GPT-2, BERT, and RoBERTA are under the respective folders. An additional Python script for tokenization utilities, `tokenizer_utils.py`, is used in some notebooks.

## 🤖 Trained models

Every model, trained using the [FastAI library](https://github.com/fastai/), is housed under the Zenodo record [10.5281/zenodo.4293857](https://doi.org/10.5281/zenodo.4293857). The models are stored using the [🤗HuggingFace's Transformers](https://github.com/huggingface/transformers) library, sited in the named folders `20200813_gpt2-CodeSearchNet-fine-tuned`, `20200817_fit_head_bert_model-CodeSearchNet`, `20200817_fine_tuned_bert_model-CodeSearchNet`, `20200813_roberta-CodeSearchNet_fit_head`, and `20200813_roberta-CodeSearchNet_fine_tuned`.

## ✅ Results

The CSV files bearing the results from training processes are nested under the `results` folder. The associated notebook that examines them is `analyzing_results.ipynb`.