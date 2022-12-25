# DS920+_DSM-7.1.1_Proxmox
Xpenology DSM 7.1.1 Proxmox ( tinycore-redpill )


```
./rploader.sh update now
./rploader.sh fullupgrade now
./rploader.sh serialgen DS920+
./rploader.sh ext ds920p-7.1.1-42962 add https://raw.githubusercontent.com/pocopico/rp-ext/master/e1000/rpext-index.json
./rploader.sh ext ds920p-7.1.1-42962 add https://raw.githubusercontent.com/pocopico/redpill-load/develop/redpill-acpid/rpext-index.json
```
