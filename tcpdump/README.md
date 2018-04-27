# Use tcpdump to analyse http request/response

## Install tcpdump on any centos host
1. scp the zip file to host, unzip it
2. install rpms
```
sudo yum install libpcap.rpm tcpdump*.rpm
```
3. use dump.sh to start listen
```
./dump.sh <port>
```
