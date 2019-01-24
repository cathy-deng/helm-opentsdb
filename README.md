# helm-opentsdb
### install zookeeper
```
helm install --name myzk incubator/zookeeper --set servers=1,heap="1G"
```
### install hbase
```
use https://github.com/warp-poke/hbase-helm for reference.
```
### install opentsdb
```
change configuration in value.yaml file and then install opentsdb 
helm install ./opentsdb --name opentsdb
```
