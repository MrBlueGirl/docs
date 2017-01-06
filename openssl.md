##### self signed certificate
    $ openssl req -x509 -newkey rsa:2048 -keyout key.pem -out cert.pem -days XXX

##### show fingerprint HTTPS
    $ openssl x509 -noout -in /usr/local/etc/stunnel/stunnel.pem -fingerprint -sha256
