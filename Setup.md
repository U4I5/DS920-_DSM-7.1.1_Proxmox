# DS920+_DSM-7.1.1_Proxmox
Xpenology DSM 7.1.1 Proxmox ( tinycore-redpill )


```
./rploader.sh update now
./rploader.sh fullupgrade now
./rploader.sh serialgen DS920+

  #This command add Driver of Intel Network Card
./rploader.sh ext ds920p-7.1.1-42962 add https://raw.githubusercontent.com/pocopico/rp-ext/master/e1000/rpext-index.json

  #This command add acpid Driver
./rploader.sh ext ds920p-7.1.1-42962 add https://raw.githubusercontent.com/pocopico/redpill-load/develop/redpill-acpid/rpext-index.json

./rploader.sh build ds920p-7.1.1-42962
./rploader.sh backup now
```
