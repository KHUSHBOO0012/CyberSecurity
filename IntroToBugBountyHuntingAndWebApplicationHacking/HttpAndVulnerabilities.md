Burp Suite or Developer console
Foxy Proxy chrome extension for sending request with decrypting, install CA certificate.

## Open Redirect
- Unvalidated redirects and forwards
- When web-app takes and untrusted input and redirects a user from the web-application to untrusted site or resources that will be used further for malicious purposes.

#### Security-Measures 
- Developer defines list of trusted or untrusted resources. In some cases, you may be able to bypass it if you fully understand what it works.

- Allowed - https://example.com/login/?nextPage=https://google.com
- Not allowed - https://example.com/login/?nextPage=https://evilsite.com
- Allowed - https://example.com/login/?nextPage=https://evilsite.com/?google.com  

https://example.com/login/?redirect=https://google.com@nahamsec.com

<img width="480" alt="image" src="https://user-images.githubusercontent.com/32810320/220905055-ffa3c26d-3889-44f5-bebb-e05a6ff8e207.png">

Before @ are ignored.

## Cross-Site Scripting
XSS - Allows an
