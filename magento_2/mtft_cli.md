# Run the Selenium server
```
java -Dwebdriver.chrome.driver=chromedriver -jar selenium-server-standalone-3.141.59.jar
```

#Generate and run all tests

## Generate test
```
vendor/bin/mftf generate:tests {text}
```

## Run a test
```
vendor/bin/mftf run:test {text} --remove
```

# Generate reports
```
allure serve dev/tests/acceptance/tests/_output/allure-results/
```
