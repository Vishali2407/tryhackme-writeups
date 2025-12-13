TryHackMe – HTTP in Detail
Overview

This room explains how websites communicate using the HTTP and HTTPS protocols. It breaks down what actually happens when a browser requests a web page and how a server responds.
For a cybersecurity beginner, this room is important because HTTP is everywhere. Almost every web attack, scan, or exploit depends on understanding how web requests and responses work.
The room mainly focuses on web fundamentals, networking basics, and how browsers and servers interact.

What I Learned

What HTTP and HTTPS are
HTTP is the protocol used by browsers and servers to talk to each other. HTTPS is the secure version where data is encrypted to prevent interception.

How requests and responses work
A browser sends a request to a server, and the server replies with a response. This response includes status codes, headers, and the actual content.

HTTP methods
Methods like GET and POST define what action the client wants to perform, such as fetching data or sending form input.

Status codes
Status codes tell whether a request succeeded or failed. Codes like 200, 404, and 500 quickly explain what happened.

Headers and cookies
Headers carry extra information about the request or response. Cookies store small pieces of data to maintain sessions and user states.

How requests are made manually
Learned how requests can be inspected and created using tools instead of relying only on the browser.

Tools & Commands Used

Web browser (to observe normal requests)

Browser developer tools (Network tab)

Basic understanding of HTTP request structure

Simple request testing using built-in browser tools

Key Takeaways

I finally understood what happens behind the scenes when a webpage loads.

Status codes stopped feeling random and started making sense.

Cookies were confusing at first, but seeing how they track sessions cleared it up.

Headers looked overwhelming, but focusing on common ones made them easier to understand.

How This Helps My Cybersecurity Journey

This room builds a strong foundation for web security. Understanding HTTP is necessary before learning topics like web vulnerabilities, authentication flaws, or API security.
It prepares me to read web traffic properly, understand scanner output, and analyze how attacks like SQL injection or XSS actually work in real applications.

Next Steps

Practice more web-based rooms related to HTTP and web basics.

Learn how HTTP is abused in common web vulnerabilities.

Move on to beginner rooms focused on web exploitation and Burp Suite basics.
