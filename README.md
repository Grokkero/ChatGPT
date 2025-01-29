# ChatGPT
AI
# Как установить и использовать ИИ модель DeepSeek R-1 на вашем компьютере
https://habr.com/ru/articles/876320/
Using Ollama.com

х х х
# Fusion of Engineering, Control, Coding, Machine Learning, and Science
https://aleksandarhaber.com/how-to-install-and-run-deepseek-v3-model-locally-on-gpu-or-cpu/

DeepSeek-V3 / llama.cpp / LLM / Machine Learning / Machine Learning/Data Science

In this tutorial, we explain how to install and run a (quantized) version of DeepSeek-V3 on a local computer by using the llama.cpp program. DeepSeek-V3 is a powerful Mixture-of-Experts (MoE) language model that according to the developers of DeepSeek-V3 outperforms other LLMs, such as ChatGPT and Llama. The YouTube tutorial is given below.

Чтобы установить DeepSeek на компьютер без GPU, можно следовать инструкции на сайте aleksandarhaber.com:

Установить Visual Studio. 1
Установить CUDA toolkit. 1
Скачать и установить llama.cpp. Для этого нужно перейти на сайт github.com и скачать файл в формате llama--bin-win-cuda-cu-x64.zip. Распаковать его и скопировать все загруженные файлы в новую папку. 1
Скачать файлы модели DeepSeek. Для этого нужно перейти на сайт huggingface.co и выбрать нужную модель, загрузив все пять файлов модели. 1
После загрузки модели можно запустить её. Для этого нужно открыть командную строку и перейти в папку, в которой сохранены llama.cpp и файлы модели. В этой папке ввести команду: 1

llama-cli --model DeepSeek-V3-Q2_K_XS-00001-of-00005.gguf --cache-type-k q5_0 --threads 16 --prompt "<｜User｜>How to solve a quadratic equation?<｜Assistant｜>"
