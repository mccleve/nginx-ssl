# Nginx SSL A+ rating config

This repository contains stub configuration for obtaining an A+ rating with Qualys SSL Labs https://www.ssllabs.com/ssltest/


### Pre-Requisite
You will need to generate a new diffie-helman 4096 bit prime if you haven't already. This process does take some time (~30-45 minutes).

`openssl dhparam -out dhparam.pem 4096`

### Site Config
`stub-nginx.config` typically located at `/etc/nginx/nginx.config`

This is the global configuration for nginx. For multi-tenant boxes, we prefer to keep the ssl config global so changes are easier to manage. See the "REPLACE-ME" comments for lines that need modification.

### Global Config
`stub-site.config` typically located at `/etc/nginx/conf.d/YOURSITENAME.config`

This is the individual site configuration stub. See the "REPLACE-ME" comments for lines that require modification.
