## Repos
- https://github.com/zomasec/client-side-bugs-resources -> good source


## Write-up
- [DOM XSS to Account Takeover in GSI SDK](https://blog.voorivex.team/not-so-dirty-dancing-in-gis-sdk)
- https://security.lauritz-holtmann.de/post/xss-ato-gadgets/
- https://ysamm.com/uncategorized/2026/01/17/math-random-facebook-sdk.html
- https://nokline.github.io/bugbounty/2024/06/07/Zoom-ATO.html
- https://mizu.re/post/fcsc-2026-writeups --> Kevin Mizu (recommended)

## CSPT 
- https://medium.com/@renwa/client-side-path-traversal-cspt-bug-bounty-reports-and-techniques-8ee6cd2e7ca1
- https://blog.voorivex.team/cloudflare-image-proxy-as-a-cspt-gadget-a-cross-origin-cspt-exploit
- https://zere.es/posts/cache-deception-cspt-account-takeover/
  - https://www.youtube.com/watch?v=O1ZN_OCfNzg --> Exploiting Client-Side Path Traversal: CSRF Is Dead, Long Live CSRF
  - https://matanber.com/blog/cspt-levels
- https://x.com/samwcyo/status/1437030056627523590
- https://whoareme.com/blog/cspt-account-takeover-2fa-bypass/

## WAF Bypass
- https://blog.ethiack.com/blog/bypassing-wafs-for-fun-and-js-injection-with-parameter-pollution

## JS Analysis
- https://kpwn.de/2023/05/javascript-analysis-for-pentesters/

## postMessage and sandbox escaping 
- https://javascript.info/cross-window-communication
- https://javascript.info/cross-window-communication
- https://www.monke.ie/p/exfiltrating-data-from-sandboxed-documents?utm_source=bugbountydaily.com&utm_medium=referral
- https://rhynorater.github.io/postMessage-Braindump
- https://www.turb0.one/pages/Challenge_One:_Strange_XSS_Writeup.html
- https://x.com/floatingdotmind/status/1847911787053645927
- https://hackerone.com/reports/207042 --> to implement

## XSS
- https://github.com/masatokinugawa/filterbypass/wiki/Browser's-XSS-Filter-Bypass-Cheat-Sheet
- https://www.imperva.com/blog/xss-marks-the-spot-digging-up-vulnerabilities-in-chatgpt/
- https://x.com/sudhanshur705/status/1950836945418076596
- https://lab.ctbb.show/research/Exploiting-web-worker-XSS-with-blobs
- https://xbow.com/blog/xbow-salesforce-xss
- https://flatt.tech/research/posts/why-xss-persists-in-this-frameworks-era/ -> good for depth knowledge
- https://mey-d.github.io/posts/self-xss-disk-cache/
- https://github.com/ArtSecTest/artsec-xss-labs -> xss lab
- https://coopergyoung.com/exacerbating-cross-site-scripting-the-iframe-sandwich/
- https://sudistark.github.io/2026/04/07/mxss.html --> Mutation XSS
- https://mey-d.github.io/posts/self-xss-disk-cache/ --> by meydi 

#### Parser discrepencies and XSS
- https://lab.ctbb.show/research/parse-and-parse-mime-validation-bypass-to-xss-via-parser-differential
- https://blog.voorivex.team/when-two-parsers-disagree-exploiting-query-string-differentials-for-xss

#### DOM XSS
- https://elmahdi4.wordpress.com/2025/09/26/dom-xss-bypassing-server-side-cookie-overwrite-chrome-innerhtml-quirk-and-json-injection/
- https://medium.com/@renwa/site-dom-xss-using-cookie-injection-the-ai-hackers-are-coming-faster-than-you-think-3ef82f2a991d --> Renwa XSS

## Browser, iframe, and specifications --> very important 
- https://blog.huli.tw/2022/04/07/en/iframe-and-window-open/
- https://reshpentestexperts.medium.com/bypassing-the-x-frame-options-header-b6ad0ff8df07
- https://joaxcar.com/blog/2024/05/16/sandbox-iframe-xss-challenge-solution/
- https://aszx87410.github.io/beyond-xss/en/ -> MUST READ
- https://github.com/sin99xx/researchlab/blob/main/Cookies-and-CORS.md


## CSP Bypass
- https://jorianwoltjer.com/blog/p/research/nonce-csp-bypass-using-disk-cache
