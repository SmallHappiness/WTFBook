# WTFBook
What the funny book it is!

# RoR issue

Enviroment:
---

Windows OS + 2.1.x Ruby 

Problem:
---
When Using "gem" to install package, occurs error message:

<pre><code>SSL_connect returned=1 errno=0 state=SSLv3 read server certificate B: certificate verify failed</code></pre>


Solution:
---
1. Download http://curl.haxx.se/ca/cacert.pem into C:\railsinstaller\cacert.pem
2. Go to your Computer -> Advanced Settings -> Environment Variables
3. Create a new System Variable:
 - Variable: SSL_CERT_FILE
 - Value: C:\RailsInstaller\cacert.pem
