# nginx_Reverse_Proxy
reverse-proxy.conf

English:
Example-Config for nginx Reverse-Proxy
(Edit: Domain, Sub-Domain [Folder] and IP-Adresses)

Deutsch:
Beispiel-Konfiguration für einen nginx Reverse-Proxy
(Anzupassen: Domäne, Unter-Domäne [Ordner] und IP-Adressen)

# How-To

Save File here:
 /etc/nginx/sites-available/

Make a Sym-Link:
 ln -s /etc/nginx/sites-available/reverse-proxy.conf /etc/nginx/sites-enabled/reverse-proxy.conf

Test the Config:
 nginx -t

Reload nginx:
 nginx -s reload
