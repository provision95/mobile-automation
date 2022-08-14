# This project is a test automation for WEHAGO mobile application.

To run the project a user has to install [Poetry](https://python-poetry.org/).

---

## Before RUN

<ul>
    <li><strong>JAVA</strong> installed.</li>
    <li><strong>npm</strong> and <strong>nodejs</strong> installed.</li>
    <li>Run <strong>Appium Desktop</strong> server.</li>
    <li>Run <strong>android emulator</strong> (<code>emulator -avd {emaltor name}</code> or <strong>Virtual Device Manager</strong> from Android Studio).</li>
</ul>


## Run

<ol>
    <li><code>poetry shell</code> - activate virtual environment.</li>
    <li><code>poetry install</code> - install dependencies.</li>
    <li><code>poetry build</code> - build the project.</li>
    <li><code>poetry run pytest --alluredir="./Allure" /tests/ContactTests.py</code> - run the tests.</li>
    <li><code>deactivate</code> - to deactivate virtual environment.</li>
</ol>