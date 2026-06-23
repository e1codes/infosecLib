# Exploiting Emails
- https://www.youtube.com/watch?v=Bpnc1-g3fMk

## RCE 
- https://github.com/httpvoid/writeups/blob/main/Apple-RCE.md
- https://www.rcesecurity.com/2026/02/when-audits-fail-from-pre-auth-ssrf-to-rce-in-trufusion-enterprise/
- https://projectdiscovery.io/blog/hacking-apple-with-sql-injection
- https://www.wiz.io/blog/github-rce-vulnerability-cve-2026-3854 --> GitHub RCE via git push
- https://www.hacktron.ai/blog/react2shell-vercel-waf-bypass#bypass-4-duplicate-content-type-in-multipart-field
- https://www.hacktron.ai/blog/rce-in-vscode-copilot
- https://bugbunny.ai/blog/google-gemini-cli-rce-2025

## Parsers vulnerabilities
- https://blog.sicuranext.com/breaking-down-multipart-parsers-validation-bypass/
- https://lab.ctbb.show/research/parse-and-parse-mime-validation-bypass-to-xss-via-parser-differential
- https://portswigger.net/research/splitting-the-email-atom -> see also https://portswigger.net/research/bypassing-character-blocklists-with-unicode-overflows
- https://blog.bugport.net/exploiting-http-parsers-inconsistencies
- https://www.yeswehack.com/learn-bug-bounty/syntax-confusion-ambiguous-parsing-exploits -> recommended

## Database Exploitation
- https://www.r-tec.net/r-tec-blog-mssql-exploitation-run-commands-like-a-pro.html

## API related vulns
#### Business logic 
- https://zere.es/posts/deanonymizing-users-at-scale/

## Java
- https://www.dsecured.com/en/articles/spring-boot-actuator-using-misconfig-to-your-advantage-paths-bypasses-techniques

## Reverse Proxy and middleware
- https://labs.detectify.com/ethical-hacking/middleware-middleware-everywhere-and-lots-of-misconfigurations-to-fix/


## Cache bugs
- https://medium.com/@Aacle/20-cache-poisoning-case-study-depth-analysis-of-real-world-bug-reports-d6aa02a6a44f
- https://malicious.group/smuggling-through-the-front-door-achieving-0-click-xss-with-cache-poisoning/


## Authentication, SSO
- https://medium.com/@Maverick0o0/zero-click-mass-account-takeover-on-exchange-5e6c8790b054
- https://medium.com/@0x_xnum/saml-authentication-bypass-leading-to-admin-panel-access-24f23812ed76
- https://security.lauritz-holtmann.de/advisories/flickr-account-takeover/
- https://mey-d.github.io/posts/zero-click-ato-persian/

## Abusing WAFs
- https://medium.com/@blogwithsarthak/from-query-param-to-cookie-poisoning-how-wafs-fail-at-security-69f784822635 -> intereseting

## Cookie and JWT
- probably a seperate topic later
- https://rmrf.tips/en/posts/jwt-why-broken/ --> highly recommended
- https://github.com/sin99xx/researchlab/blob/main/JWTs-deep-dive.md


## SSRF
- https://medium.com/@skycer_00/full-blown-ssrf-to-gain-access-to-millions-of-users-records-and-multiple-internal-panels-3719d9b802e9
- https://gist.github.com/jhaddix/78cece26c91c6263653f31ba453e273b --> cloud metadate wordlist
- http://blog.assetnote.io/2021/01/13/blind-ssrf-chains/ --> Exploiting blind SSRF
- https://x.com/Rhynorater/status/1689400476452679682 --> Justing Baaghboon SSRF tips
- https://portswigger.net/research/top-10-web-hacking-techniques-of-2017#1:~:text=1.%20A%20New%20Era%20of%20SSRF
- https://ahmed-tarek.gitbook.io/security-notes/owsap-top-10-2025/a01-broken-access-control/server-side-request-forgery-ssrf
- https://medium.com/@AlvaroBalada/ssrf-on-a-headless-browser-becomes-critical-c08daaa1017e
- https://github.com/httpvoid/writeups/blob/main/Circumventing-Browser-Security-Mechanisms-For-SSRF.md
- https://www.synack.com/exploits-explained/microservices-attack-vectors-in-modern-web-applications/
- https://x.com/ryancbarnett/status/1958202455528771942 --> IP Obfuscature tool, useful
- https://eib.hashnode.dev/crafting-a-full-read-ssrf-a-journey-through-oauth-dcr-open-url-redirects-and-path-normalization
- https://blackhat.com/docs/us-17/thursday/us-17-Tsai-A-New-Era-Of-SSRF-Exploiting-URL-Parser-In-Trending-Programming-Languages.pdf

## IDOR , Access Control
- https://j4eva.io/blog/meta-ai-idor
- 
