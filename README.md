### insert module 
```sudo insmod queue_list.ko```
### access root mode 
```sudo -i```
### push to queue
```echo "some information string" > /proc/queue ```
### pop from queue
``` cat /proc/queue ```
