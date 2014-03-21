```
/**
 * Rework of rabbitmq-auth-backend-http by simonmacmullen (github.com/simonmacmullen) 
 * Copyright (c) 2014, Sergey Shilko (sergey.shilko@gmail.com)
 * @author simonmacmullen, Alessandro Sivieri, Sergey Shilko
 * @see https://launchpad.net/~scattino/+archive/ppa
 * @see https://github.com/sshilko/rabbitmq-auth-backend-server-3.2.4-amd64
 * @see https://github.com/simonmacmullen/rabbitmq-auth-backend-http
 */
```

## Overview

* Debian (deb) package for installation with RabbitMQ 3.2.4
* Requires erlang >= R15
* Enable with 'rabbitmq_auth_backend_http' in /etc/rabbitmq/enabled_plugins 
* Change auth adapter with /etc/rabbitmq/rabbitmq.config {auth_backends, [rabbit_auth_backend_http]}

## Why another fork?

* Original deb from ppa was built against RabbitMQ 3.1.3
* Original deb attached: rabbitmq-auth-backend-http_20131225-3_amd64.deb
* Original ppa was built against Ubuntu 13.04 (Saucy), but needed Precise 12.04
* Original ppa: deb http://ppa.launchpad.net/keks9n/rabbitmq-auth-backend-http/ubuntu saucy main

