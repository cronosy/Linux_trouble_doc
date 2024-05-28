# VMS

```json:table
{
    "fields" : [
        {"key": "namevm", "label": "NAME VM"},
        {"key": "memory", "label": "MEMORY"},
        {"key": "cpu", "label": "CPU"},
        {"key": "hotmem", "label": "HOT_ADD MEM"},
        {"key": "hotcpu", "label": "HOT_ADD CPU"},
        {"key": "firmware", "label": "FIRMWARE"},
        {"key": "dfip", "label": "DEFAULT_IP"},
        {"key": "vmfolder", "label": "VMWARE_FOLDER"},
        {"key": "disks", "label": "DISKS"}
    ],
    "items" : [
      {"namevm": "12312_co", "memory": "22", "cpu": "33","hotmem": "true", "hotcpu": "true", "firmware": "EFI", "dfip": "10.10.10.10", "vmfolder": "xxxxx", "disks": {"disk0":{"attach": "False", "controller_type": "scsi", "datastore_id": "datastore-2637075","device_address":"scsi:0:0"}} },
      {"namevm": "12313_co", "memory": "22", "cpu": "33","hotmem": "true", "hotcpu": "true", "firmware": "EFI", "dfip": "10.10.10.11", "vmfolder": "xxxxx", "disks": "" }
    ],
    "filter" : true
}
```
