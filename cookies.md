# Cookies:

⇒ These are mainly concerned towards privacy.

⇒ HTTP is a stateless protocol, a lot of times web sessions are required, we store those on cookies

## How cookies work?

⇒ Cookies are unique identifier strings, These are set by server through the HTTP headers.

⇒ As soon as cookies is stored, It is sent along with subsequent HTTP requests to the same server.

⇒ This allows server to know who is contacting it and hence serve the content accordingly.

### Set Cookie header:

⇒ when a server wants to set a cookie, it includes set-cookie: value in the HTTP response .

⇒ This value is stored in the cookie file of browser.

⇒ It contains website domain, string value, when initiated, when expires
