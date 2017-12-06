@title[Introduction]

# Traffic, Verbs, Testing and T-Shirts

#### @sharathb and @tonybruce77
<br>
<br>


---

@title[PITCHME.md]

## Agenda
* Quick overview of HTTP and REST API and what part they play
* Introduction on how to start testing HTTP
* Exercises to understand and test HTTP
* Introduction to tools - 
    * Postman
    * REST-Server
    * Curl  
* And T-shirts

---

## How does HTTP work?

Client-server* transactions consist of three main parts.
* A response or request line
* Header information
* The body

*meaning a computer system where a central server provides data to a number of networked workstations.

---

## A <span style="color:blue">_***request***_</span> or response line

The <span style="color:blue">_***request***_ </span> line has three parts - 
* A method name
* Local path of the requested resource
* The version of HTTP used

> GET /tonybruce/Traffic-Verbs-Testing-and-T-Shirts/master HTTP/1.1

<br>
---
## Header Information 
```
GET /tonybruce/Traffic-Verbs-Testing-and-T-Shirts/master HTTP/1.1
Host: gitpitch.com
Connection: keep-alive
Pragma: no-cache
Cache-Control: no-cache
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/62.0.3202.94 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8
Accept-Encoding: gzip, deflate, br
Accept-Language: en-GB,en-US;q=0.9,en;q=0.8
Cookie: _ga=GA1.2.1473685318.1512492645; _gid=GA1.2.1103842518.1512492645; _gat=1
```
---
## HTTP Verbs


