# fastd-verify 0.1
fastd Verification by API

[![Code Issues](https://www.quantifiedcode.com/api/v1/project/80964151ca3448e397ea83c0270b9811/badge.svg)](https://www.quantifiedcode.com/app/project/80964151ca3448e397ea83c0270b9811)

### Purpose
This little script verifies fastd peers by calling an API using the public key
of the peer as an argument.
It can be used to support a scenario in which fastd peers are to be 
verified by a database or API backend.

### Use in fastd
1. Put the script somewhere it can be executed from (eg. `/usr/local/bin`).
2. Configure the server to call the script like this:

  ```on verify "/usr/local/bin/fastd-verify";```

### Bugs
Contact me a via e-mail at felix at freifunk-leverkusen.de

### License
This software is licensed under the GPLv2 or any later version.
