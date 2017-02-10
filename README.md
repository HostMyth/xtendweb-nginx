# xtendweb-nginx

opt/ Discuz and ECSHOP templates of xtendweb-nginx

etc/ limit webdisk download speed and connection 

# register nginx into cPanel's checksrvd 

To add a new service, create a line in ”’/etc/chkserv.d/chkservd.conf’” in the same format as the others:
 ```
nginx:1
 ```
And upload nginx of the attachment to /etc/chkserv.d/

Finally, reboot the chkserv.d by command
 ```
/scripts/restartsrv_tailwatchd
 ```
