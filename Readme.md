# mega-php
Mashed up php code for mega api from couple of sources.

## Notes
- Changed decryption methods from mcrypt to openssl.
- Downloads now store in a tempfile and decrypted later.

### References
Base code - https://github.com/smartinm/mega-php-client

node_publish - https://github.com/MichaelRPowell/mega-php-client

Login for v2 accounts, finding node object from path string - https://github.com/odwyersoftware/mega.py
