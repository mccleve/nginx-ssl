# Nginx SSL A+ rating config

This repository contains stub configuration for obtaining an A+ rating with Qualys SSL Labs https://www.ssllabs.com/ssltest/

`stub-nginx.config`

This is the global configuration for nginx. For multi-tenant boxes, we prefer to keep the ssl config global so changes are easier to manage. See the "REPLACE-ME" comments for lines that need modification.

`stub-site.config`

This is the individual site configuration stub. See the "REPLACE-ME" comments for lines that require modification.
