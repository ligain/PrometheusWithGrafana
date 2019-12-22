# Prometheus + Grafana inside Vagrant

In this project, we are configurating prometheus, node_exporter, alertmanager and Grafana in Vagrant VM. We setup Grafana dashboard which can use source as Prometheus.


# Run  
0) `vagrant` and `Ansible` should be installed on your system
```
$ vagrant -v
Vagrant 2.2.5
```
1) Clone this repository
```bash  
$ git clone https://github.com/ligain/PrometheusWithGrafana.git  
``` 
2) Go to project folder
```bash  
$ cd PrometheusWithGrafana/
```  
3) Run `Vagrantfile`
```bash  
$ vagrant up
```
4) After the vagrant virtual machine will have been setuped  you can try to check `Prometheus`  admin page at [http://localhost:9090](http://localhost:9090/graph) and `Grafana` web interface at [http://localhost:3000](http://localhost:3000).
