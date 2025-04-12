## YANG

```shell
$ pyang ietf-distributed-notif@2025-04-12.yang -f tree --tree-line-length 69 -p dependencies
```

Full tree
```shell
$ pyang ietf-distributed-notif@2025-04-12.yang ietf-subscribed-notifications@2019-09-09.yang ietf-yang-push@2019-09-09.yang -f tree --tree-line-length 69 -p dependencies
```

Format for Datatracker
```shell
$ pyang ietf-distributed-notif@2025-04-12.yang -f yang --yang-line-length=69 -p dependencies
```