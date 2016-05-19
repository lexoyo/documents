We have a call this morning with NLnet, and I wanted to make a quick review of what we accomplished so far with IndieHosters.
The good news is that, on our way, we contributed a lot to FLOSS!

# Official instructions to create an IndieHosters package:

https://github.com/indiehosters/applications/

# Standardise the archive to migrate betwwen hosters:

We decided to go with yunohost archive format to avoid [xkcd 927](https://xkcd.com/927/).
We are not yet finnished, but in the process of migrating over.
Anyway, it wouldn't be too difficult to write a converter.

We have a proof of concept of unattended migration between 2 hosters.
With that comes the possibility for the end user to download all his data whenever he wants.
(contact us if interested)

We host around 60 domain names and 100 people/group (1 group can be many users).

We signed:
 - [user data manifesto](https://userdatamanifesto.org/)
 - [framasoft charte](https://framagit.org/framasoft/CHATONS/)

In numbers:
 - 310 running containers
 - 60 domain names
 - 100 users (1 user can host many other users, like with ownCloud)
 - uptime 99.91%/month (it has been worst, it is a good month, the worst was 98%)
 - 20 different applications (mostly web and email)
 - 23 different technologies

Applications we offer:
 - piwik ([official image](https://github.com/docker-library/official-images/commit/cffe0fc9a4b62d1f3eb59e8bac6c50a0073a97db))
 - rocket.chat ([official image](https://github.com/docker-library/official-images/commit/68cd064b33ac1c7f23145577eede8f3e337992f4))
 - ownCloud ([fpm official image](https://github.com/docker-library/owncloud/commits?author=pierreozoux))
 - known ([on the way for official image](https://github.com/idno/Known-Docker/issues/1))
 - wezer ([upstream Dockerfile](https://github.com/indiehosters/wezer))
 - remoteStorage ([upstream Dockerfile](https://github.com/indiehosters/remoteStorage))
 - silex ([upstream Dockerfile](https://github.com/silexlabs/Silex/blob/master/Dockerfile))
 - email ([docker-compose](https://github.com/indiehosters/email))
 - discourse ([docker-compose](https://github.com/docker-discourse/docker-discourse))
 - mautic
 - wekan
 - etherpad
 - ethercalc
 - WordPress
 - boxbilling
 - oxwall
 - odoo
 - dotClear
 - static website
 - laverna
 - revealJS

Technologies we use:
 - Docker
 - SystemD
 - clair
 - [HAProxy](https://github.com/indiehosters/HAProxy)
 - OCSP
 - Let's encrypt
 - duplicity
 - nginx
 - apache
 - postfix
 - dovecot
 - spamassassin
 - vimbadmin
 - dkim
 - dmarc
 - spf
 - php
 - nodeJS
 - python
 - RubyOnRails
 - MySQL
 - MongoDB
 - Postgres
