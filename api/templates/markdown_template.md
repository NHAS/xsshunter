# XSSHunter Report

The page located at `{{vulnerable_page}}` suffers from a Cross-site Scripting (XSS) vulnerability. XSS is a vulnerability which occurs when user input is unsafely encorporated into the HTML markup inside of a webpage. When not properly escaped an attacker can inject malicious JavaScript that, once evaluated, can be used to hijack authenticated sessions and rewrite the vulnerable page's layout and functionality. The following report contains information on an XSS payload that has fired on `{{origin}}`, it can be used to reproduce and remediate the vulnerability.

### XSS Payload Fire Details
##### Vulnerable Page
`{{vulnerable_page}}`

##### Victim IP Address
`{{victim_ip}}`

##### Referer
`{{referer}}`

##### User Agent
`{{user_agent}}`

##### Cookies (Non-HTTPOnly)
`{{cookies}}`

##### Document Object Model
`{{dom}}`

##### Origin
`{{origin}}`

##### HTML5 Canvas-Rendered Screenshot
![XSS Screenshot](https://api.{{domain}}/{{screenshot}} "{{vulnerable_page}}")

##### Injection Timestamp
`{{injection_timestamp}}`

## Remediation
For more information about Cross-site Scripting and remediation of the issue, see the following resources:
* [Cross-site Scripting (XSS) - OWASP](https://www.owasp.org/index.php/Cross-site_Scripting_(XSS))
* [XSS (Cross Site Scripting) Prevention Cheat Sheet - OWASP](https://www.owasp.org/index.php/XSS_(Cross_Site_Scripting)_Prevention_Cheat_Sheet)
* [What is Cross-site Scripting and How Can You Fix it?](https://www.acunetix.com/websitesecurity/cross-site-scripting/)
* [An Introduction to Content Security Policy - HTML5 Rocks](http://www.html5rocks.com/en/tutorials/security/content-security-policy/)
* [Why is the same origin policy so important? - Information Security Stack Exchange](https://security.stackexchange.com/questions/8264/why-is-the-same-origin-policy-so-important)

*This report was generated by an XSS Hunter server: https://github.com/mandatoryprogrammer/xsshunter*