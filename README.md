# kx_transport_pytest_POMbased_allure_report

After cloning go to project root directory and run this command:
pip install -r requirements.txt

To generate allure report for single test case run this command:
pytest --alluredir allure-results .\Tests\test_loginpage.py

To generate allure report for all test case run this command:
pytest --alluredir allure-results .\Tests

To run single test case without allure report run this command:
pytest .\Tests\test_loginpage.py

To run all test case without allure report run this command:
pytest .\Tests

To see allure report run this command:
allure serve allure-results

Pass parameter from terminal specific browser and headless run:
pytest --browser=your_browser_name --headless
