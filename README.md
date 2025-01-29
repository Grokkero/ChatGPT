# ChatGPT
AI

## Технологический провал: анонс китайского чат-бота, аналога ChatGPT-4, окончился обвалом фондового рынка США на $1 трлн
https://dzen.ru/a/Z5liOsb0OEwKz2I5

Но знаете, что самое оскорбительное для OpenAI и всей американской индустрии, которая стремилась монополизировать рынок ИИ?

DeepSeek появился как побочный продукт другого проекта и лишь с целью догрузить имеющиеся в распоряжении неиспользуемые графические процессоры. Потому и обошлись китайцы лишь 2 тысячами процессоров, вместо 100 000 у OpenAI. И силами 200 сотрудников. 

Как будто в подтверждение этих слов, 27 января китайский разработчик сообщил о масштабных вредоносных атаках и приостановил регистрацию новых пользователей. Ну, а что, нечего белым господам портить малину, понимаешь ли.

Но хуже всего не это, хуже всего то, что США повторяют провал, когда-то стоивший им векового технологического отставания. Этот провал американская промышленность не смогла наверстать до сих пор и не сможет это сделать в будущем. Однако это уже тема для закрытого разговора, статью выложу в раздел премиум, ибо такое в открытый доступ лучше не выставлять.
https://dzen.ru/sferalive?tab=premium
Но хуже всего не это, хуже всего то, что США повторяют провал, когда-то стоивший им векового технологического отставания. Этот провал американская промышленность не смогла наверстать до сих пор и не сможет это сделать в будущем. Однако это уже тема для закрытого разговора, статью выложу в раздел премиум, ибо такое в открытый доступ лучше не выставлять.


#  Все GPT -- 120+ нейросетей с аптаймом 99%
доступ из России без VPN и блокировок
OpenAI API для интеграций
https://vsegpt.ru/

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
