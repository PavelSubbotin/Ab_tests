# AB tests
### Преамбула
Данный репозиторий создан с целью самообразования и закрепления знаний.
Код лежит в папке [notebooks](https://github.com/PavelSubbotin/Ab_tests/tree/main/notebooks). 
Данные ноутбуки не являются учебным пособием, но написаны в стиле статьи, содержат краткие справки о реализуемых алгоритмах и тестовые вставки, поясняющие просходящее, так же в некоторых местах можно найти ссылки на материалы, которые я использовал при изучении темы.
В тетрадках я писал реализации некоторых тестов/способов улучшения тестов "с нуля" и искал ответы на вопросы, возникавшие у меня во время изучения теории. 
Репозиторий обновляется, актуальный статус ноутбуков можно найти в readme ниже.
При обнаружении ошибок/неточностей в коде, по желанию можно создать issue или написать мне в [телеграм](https://t.me/I_Love_Rogue).

### Краткое описание ноутбуков
#### Готовые ноутбуки
1) [Тест Стьюдента](https://github.com/PavelSubbotin/Ab_tests/blob/main/notebooks/T_test.ipynb) - реализация T-теста, проверка его корректности, исследование работы теста в различных условиях.
2) [Bootstrap 1-я часть](https://github.com/PavelSubbotin/Ab_tests/blob/main/notebooks/bootstrap_1.ipynb) - реализация бутстрепа, реализация пуассоновского бутстрепа и сравнение его работы с обычным, сравнение различных бутстрепных доверительных интервалов.
3) [U-test добро или зло](https://github.com/PavelSubbotin/Ab_tests/blob/main/notebooks/mann_whitney.ipynb) - поиск случаев, когда тест Манна-Уитни работает лучше, чем T-тест, пример, когда U-test некорректен.
4) [Стратификация](https://github.com/PavelSubbotin/Ab_tests/blob/main/notebooks/stratification.ipynb) - реализация стратификации, исследование эффекта от стратификации на различных данных.
#### Ноутбуки в работе
1) Bootstrap 2-я часть - продолжение сравнения эффективности использования различных доверительных интервалов, применение формулы MDE для бутстрепа.
2) CUPED - реализация CUPED, исследование эффективности при использовании различных ковариат.
#### Будущие планы
1) Проводим тест идеально - пайплайн идеального проведения теста.
2) CUPAC - сравнение использования различных ML моделей для получения ковариаты для CUPED.
3) Байесовское AB тестирование - обзор методов и их реализация.
4) Causal inference.
