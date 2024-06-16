<p align="center"> Ansible Role for installing and configuring nginx
    <br> 
</p>


### Role Variables

| Variable Name | Value | Type | Default |
| ------ | ------ | ------ | ------ |
| nginx_user | defines as which user nginx service will be started | String | www-data |
| nginx_conf_path | defines the path of nginx.conf file | String | See templates/default-nginx.conf.j2 |
| nginx_vhosts_dir_path | defines the path where website virtual *.conf reside for role to upload to the server | String | See templates/default-vhosts/ |
