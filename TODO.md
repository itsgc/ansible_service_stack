#TODO
##Playbook split
###Base playbook
 * SSH Hardening
 * Firewall (close unneeded ports)

###Web server playbook
* Apache config hardening
* SSL autoconfig (selectable letsencrypt or regular certs)
* PHP config hardening
* __Fix SSL configuration, right now only cleartext vhosts are created__
* __Once SSL config is ok, fix letsencrypt one-site config__
* __find a way to have letsencrypt work with multiple vhosts (different path for webauth for each vhost) and find a way to use letsencrypt module as a task and not declaring things in roles.__

###Database server playbook
* MariaDB hardening
* Memcached (?)

###otrs playbook
* eredita www + db playbook
* installa otrs 5
* configurazione di base

###otrs-bdi playbook
* eredita www + db + otrs
* aggiunge le modifiche allo schema sviluppate per banca d'italia

###portale-bdi
* eredita www + db
* installa app marco

###VPN playbook
* autoprovisioning of site to site with lets encrypt certificates towards a central hub site
