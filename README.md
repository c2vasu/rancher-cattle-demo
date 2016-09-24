# rancher-cattle-demo
Rancher - Open Source container orchestration frameworks.<br/>
Building Rancher Catalog Templates from Scratch. <a href="http://rancher.com/rancher-catalog-templates-from-scratch-part-1/">Refer to this article</a>

### Workspace setup for Ranchar custom catalog
```
$ mkdir rancher-cattle-demo
$ cd rancher-cattle-demo
$ git init
$ mkdir -p templates/demo/0
$ touch templates/demo/0/{docker-compose.yml,rancher-compose.yml} templates/demo/config.yml

```
### Add Host
```
#For development environment, we will add the same host running the Rancher server as a host in Rancher.

```
