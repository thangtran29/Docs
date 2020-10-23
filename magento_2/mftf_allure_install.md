# Install allure in ubuntu with a package

```
curl -o allure-2.7.0.tgz -Ls https://dl.bintray.com/qameta/generic/io/qameta/allure/allure/2.7.0/allure-2.7.0.tgz
sudo tar -zxvf allure-2.7.0.tgz -C /opt/
sudo ln -s /opt/allure-2.7.0/bin/allure /usr/bin/allure
rm -rf allure-2.7.0.tgz
allure --version
```

