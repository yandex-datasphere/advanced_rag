# Advanced RAG

В данном репозитории содержатся примеры построения предметно-ориентированных диалоговых систем на основе продвинутых техник Retrieval-Augmented Generation:

* `simple_rag`: Наивный RAG и поиск на основе синтетических вопросов
* `graph_rag`: Графовый RAG на основе извлечения графа знаний из текстового массива, вдохновлён [статьей](https://arxiv.org/abs/2404.16130)/[примером от Microsoft Research](https://github.com/microsoft/GraphRAG)
* `multiagent`: Многоагентный RAG с явной оркестрацией агентов и агентом с явными рассуждениями на основе онтологий с логическим выводом на языке Prolog.

В качестве предметной области рассматривается вино - классификация вин, подбор подходящего вина к разным блюдам. Исходные данные находятся в директории `source`.

### Конференции

Различные вариации этого кода были показаны в рамках докладов/мастер-классов на следующих конференциях:

* [SMILES 2024](https://smiles.skoltech.ru/). Летняя школа машинного обучения Skoltech. 
* Yandex Practical ML Conf 2024: Дмитрий Сошников, Дмитрий Рыбалко. Разные (мультиагентные) подходы для работы с LLM в Yandex Cloud [слайды](https://speakerdeck.com/shwars/raznyie-multiaghientnyie-podkhody-dlia-raboty-s-llm-v-yandex-cloud)

### Ссылки

* Телеграм-канал Дмитрия Сошникова [Облачный адвокат](https://t.me/shwarsico)
* Телеграм-канал [Yandex Foundation Models](https://t.me/YFM_Community)
* Телеграм-канал [Yandex for ML](https://t.me/yandexforml)