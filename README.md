
# DockerComposeMagento2.3  

**Docker Compose for magento 2.3 php7.2 redis varnish**  
   
  
Start docker:  
```shell  
$ ./cmd/start  
```  
  
Install Magento 2 :  
- empty src directory  
- ``` $ ./cmd/shell ```  
- ``` $ install-magento2 ```  
- copy .docker/magento/env in src/app/etc

| Commands | Description |Option|
|--|--|--|
| `./cmd/init` | If you didn't use the CURL setup command above, please use this command changing the name of the project. |`./cmd/init MYMAGENTO2` |
| `./cmd/start` | If you continuing not using the CURL you can start your container manually. | |
| `./cmd/stop` | Stop your project containers. | |
| `./cmd/kill` | Stops containers and removes containers, networks, volumes, and images created to the specific project. | |
| `./cmd/kill` | Stops All containers and removes All containers, All networks, All volumes, and All images. | |
| `./cmd/shell` | Access your container. |`./cmd/shell root` |
| `./cmd/magento` | Use the power of the Magento CLI.| |
| `./cmd/n98` | Use the Magerun commands as you want.| |
| `./cmd/grunt-init` | Prepare to use Grunt.| |
| `./cmd/grunt` | Use Grunt specifically in your theme or completely, it'll do the deploy and the watcher.| `./cmd/grunt luma` |
| `./cmd/xdebug` | Enable / Disable the XDebug. | |
| `./cmd/composer` | Use Composer commands.| `./cmd/composer update` |
| `./cmd/change-magento-url` | Change magento base url in magento database .| `./cmd/change-magento-url http://localhost:66` |
| `./cmd/varnishadm` | Open Varnish Cli. | |
| `./cmd/varnishncsa` | Open Varnish Live Log. | |
| `./cmd/restart-varnish` | Restarts varnish. | |
| `./cmd/mysql` | Open mysql Cli. | |

> Full Setup Magento2.3 + php 7.2  based on the work of :  
> https://github.com/clean-docker/Magento2 
> and 
> https://github.com/fballiano/docker-magento   
> Thanks a lot

