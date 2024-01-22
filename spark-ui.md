## RUN SERVER
### copy logs ( search with job id) paste in /temp 

```
brew install apache-spark
 
cd /tmp
 
mkdir spark-events
 
{Copy your log files into the /tmp/spark-events folder}
 
cd /usr/local/Cellar/apache-spark/3.4.1/libexec/sbin
 
./start-history-server.sh
```
