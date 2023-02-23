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

Redirected to last @.

## Cross-Site Scripting
XSS - Allows an attacker to execute arbitrary client side code on victim's browser. XSS can be used for phishing, exfiltrating data, account takeovers and more.
- An attacker inserts a malicious script or payload into victim's browser.
- When victim encounters the script, it executes in the victim's browser.
- Malicious payload is able to perform any action that victim can. Serious vulnerable if victim has special privilege.

#### Impact
- Read/Modify/Delete content of any page.
- Steal a users cookies or session and gain access to their account.
- Serve malicious content like phishing.

Type of XSS
1. **Reflected XSS** : Payload is injected from victim's request. Victim must click a malicious link or navigate to an attacker controlled property.
2. **Stored XSS** : Payload is stored server side and can be triggered by a victim with no interaction outside of the application.
3. **DOM XSS** : Vulnerability is in the client side code vs the server side. Injection is still typically from victim's request.


