# Integrating screenshots in Allure Report with Pytest and Playwright

This repository is a part of Allure Report documentation and contains code examples for integrating screenshots in Allure Report with Pytest and Playwright. You can find the original documentation:

- [English version](https://allurereport.org/docs/guides/playwright-pytest-screenshots/)
- [Spanish version](https://allurereport.org/es/docs/guides/playwright-pytest-screenshots/)

## Run examples

1. Clone the repository through HTTPS:

    ```shell
    git clone https://github.com/allure-examples/guide-pytest-playwright-screenshots.git
    ```

    or SSL:

    ```shell
    git clone git@github.com:allure-examples/guide-pytest-playwright-screenshots.git
    ```

2. In the shell of your choice, navigate to the repository directory

    ```shell
    cd path/to/guide-pytest-playwright-screenshots
    ```

3. The repository provides with automatic scripts that install the virtual environment, necessary packages, and run the tests. Run the script correspondind to your operating system. For Linux and MacOS:

    ```
    ./run.sh
    ```

    For OS Windows:

    ```shell
    .\run.bat
    ```

    Alternatively, create and activate Python virtual environment and install the packages manually:

    ```shell
    python -m venv venv
    source venv/bin/activate
    pip install -m requirements.txt
    ```

    After the installation, run:
    ```
    pytest
    ```

4. Run Allure Report server:

    ```shell
    allure serve -p <port-of-your-choice>
    ```

5. Browse Allure Report page on `http://127.0.0.1/<port-of-your-choice>`.
