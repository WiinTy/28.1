
Итоговый проект курса "Тестировщик-автоматизатор на Python"

Запуск тестов:


1) Install all requirements:

    ```bash
    pip install -r requirements.txt
    ```

2) Download Selenium WebDriver from https://chromedriver.chromium.org/downloads 

3) Run tests:

    ```bash
    pytest -v --driver Chrome --driver-path ~/chrome autotests_rostelecom.py
    ```

