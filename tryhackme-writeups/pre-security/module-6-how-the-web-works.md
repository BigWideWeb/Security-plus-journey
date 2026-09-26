# Module: How the Web Works — TryHackMe Pre Security

Covered how a web request actually travels from typing a URL to a page loading.  DNS, HTTP, and how it all fits together.

## What I learned

- **DNS in detail:** DNS (Domain Name System) translates human-readable domain names (like google.com) into IP addresses computers actually use to find each other. It's essentially the internet's phonebook — without it, we'd have to memorize IP addresses for every site.
- **HTTP in detail:** the protocol that governs how browsers and servers actually communicate; from requests (GET, POST, etc.) and responses (status codes like 200 OK, 404 Not Found). This is also where security relevance shows up early. HTTP vs HTTPS, headers, and how attacks like injection often ride on top of these requests.
- **How websites work:** a website isn't just "a file", it's a combination of a server hosting content, a browser rendering it, and the back-and-forth of requests/responses that assembles the page you see.
- **Putting it all together:** tracing the full path,  you type a URL, DNS resolves it to an IP, your browser sends an HTTP request to that server, the server responds, and the browser renders the page. Seeing it as one continuous chain (rather than separate isolated topics) is what made the earlier modules click into place.

## What confused me

I'd learned DNS and HTTP as separate, disconnected facts before this but,  the "putting it all together" section is what actually made it stick, seeing them as sequential steps in one process rather than two unrelated protocols to memorize.

## Mystery Gift

Streak freeze.
