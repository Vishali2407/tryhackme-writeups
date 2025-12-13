# TryHackMe – HTTP in Detail

## Overview
This room focuses on how the HTTP and HTTPS protocols work behind the scenes. It explains how a browser communicates with a web server, how requests are sent, and how responses are returned.  

For a beginner in cybersecurity, this room is important because web traffic is the base of almost all web attacks and defenses. Understanding HTTP is mandatory before learning web vulnerabilities or using security tools.

The room mainly covers web fundamentals, basic networking concepts, and browser–server communication.

## What I Learned
- **HTTP vs HTTPS**  
  HTTP is used for transferring data between a client and a server. HTTPS adds encryption so data cannot be easily intercepted.
- **Requests and responses**  
  Every webpage load is a request sent by the browser and a response sent back by the server.
- **HTTP methods**  
  Methods like GET and POST define what action the client wants to perform.
- **Status codes**  
  Status codes indicate whether a request was successful or failed, such as 200 for success and 404 for not found.
- **Headers**  
  Headers contain extra information about the request or response, like content type and browser details.
- **Cookies**  
  Cookies store small pieces of data to manage sessions and user states.

## Tools & Commands Used
- Web browser
- Browser Developer Tools (Network tab)
- Basic understanding of HTTP request structure

## Key Takeaways
- Web pages are built on simple request and response cycles.
- Status codes became easier to understand instead of guessing errors.
- Headers looked complex at first but make sense when focusing on common ones.
- Cookies helped me understand how sessions work on websites.

## How This Helps My Cybersecurity Journey
This room builds the foundation for web security. Without understanding HTTP, it is difficult to learn web attacks, analyze traffic, or use tools like Burp Suite.  

It prepares me for learning real-world vulnerabilities and understanding how attackers interact with web applications.

## Next Steps
- Learn about common web vulnerabilities like SQL injection and XSS.
- Practice beginner web exploitation rooms.
- Start using Burp Suite for intercepting HTTP traffic.
