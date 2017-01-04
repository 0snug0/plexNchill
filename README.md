# plexNchill
Simple config for proxying Plex, CouchPotato, Sonarr, and Sabnzbd

## plexNchill.conf
Move plexNchill.conf to `/etc/nginx/conf.d/` folder
Conf file is commented. Make changes if necessary.

## plexNchill.md
Markdown file, either modify the `domain.com` in the file, and compile to html, or by default the plexNchill.conf will rewrite `domain.com` to the host header that is being used.

Easiest way to compile md to html is to use `CMD+B` in sublime text.

## Service Config Update
### Sonarr
In order for the NGINX config to work, go to the `settings > general` and modify the URL base to `/sonarr`

### CouchPotato
In order for the NGINX config to work, go to the `settings > general` on the top right, switch to `Show Advanced` and modify the URL base to `/couchpotato`

