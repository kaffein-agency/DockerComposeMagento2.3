# DockerComposeMagento2.3
Docker Compose for magento 2.3 php7.2 redis varnish

Full Setup Magento2.3 + php 7.2 on the work of :

https://github.com/clean-docker/Magento2 and https://github.com/fballiano/docker-magento


Start docker:
$ ./shell/start

Install Magento 2 :
- empty src directory
$ ./shell/shell
$ install-magento2
- copy .docker/magento/env in src/app/etc

