# How to use it in an Alpine-based LXC container

1. Create Container
2. optionally run setup-alpine
3. Add Python 3
``apk add --update python3 py3-pip``
3. Unzip the code in /usr/local/share/py-kms so that the pyKms_Server.py is in that directory.
4. Add the initd_pykms as /etc/init.d/py-kms
5. run
   ``rc-service py-kms start``
