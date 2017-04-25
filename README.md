# docker_scripts

## greenbox_db_create

Za kreiranje postgresql docker CT-a

```
  ./greenbox_db_create [DOCKER_HOST] [DOCKER_CT] [PORT]
  ./greenbox_db_create greenbox-110.db.out.ba  F18-db-rudze-dobavljaci 54325

```
* kreira docker CT na remote docker hostu
* pwdless ssh poželjan
* postojeći CT se uvijek briše
* podaci su u CT-u


## greenbox_usb_create 

Za kreiranje greenbox USB diska

```
  ./greenbox_usb_create
   argumenti su:   ./greenbox_usb_create [USB_HDD]
   npr:   ./greenbox_usb_create /dev/sdc

```


## greenbox_usb_update 

Za update greenbox USB diska

```
	argumenti su:    ./greenbox_usb_update [GREEN_VER]
	npr:  ./greenbox_usb_update 3.7.2

```

