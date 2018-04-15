@title[Introduction]

# Traffic, Verbs, Testing and T-Shirts

#### @sharathb and @tonybruce77
<br>
<br>


---
## Ice Breaker

![Get](assets/ice.png)
![Get](assets/mallet.png)
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
    * Karate
* And T-shirts

---
## Background: What are the technologies?

**HTTP**: is an application protocol for distributed, collaborative, and hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web

---
**HTTP Verbs/Methods**: HTTP defines methods (sometimes referred to as verbs) to indicate the desired action to be performed on the identified resource. What this resource represents, whether pre-existing data or data that is generated dynamically, depends on the implementation of the server

---
**HTTP Headers:** carry information such as information about the client browser, the requested page, the server and etc

---
**HTTP Status Codes**: are used to convey the results of a request, for example 200 (OK) generally means the request was carried out successfully

---
**API**: is a set of subroutine definitions, protocols, and tools for building application software. In general terms, it is a set of clearly defined methods of communication between various software components

---
**REST**: Representational state transfer (REST) or RESTful web services are a way of providing interoperability between computer systems on the Internet. REST-compliant Web services allow requesting systems to access and manipulate textual representations of Web resources using a uniform and predefined set of stateless operations. 

---
**RESTful API**: A RESTful API is an application program interface (API) that uses HTTP requests to GET, PUT, POST and DELETE data.

---
![Get](assets/tech.jpg)

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
## A request or <span style="color:blue">_***response***_</span> line

The <span style="color:blue">_***response***_ </span> line has three parts -
The version of HTTP used
A response status code 
English reason phrase which describes the status code



<span style="color:green">_***HTTP/1.1 200 OK***_</span>

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
TODO This is a repeat
## HTTP Verbs

HTTP defines methods (sometimes referred to as verbs) to indicate the desired action to be performed on the identified resource. What this resource represents, whether pre-existing data or data that is generated dynamically, depends on the implementation of the server

---
## GET  

<span style="color:blue">_***GET requests***_ </span> ask for data, and <span style="color:blue">_***do not change***_ </span> the data on the server  
<span style="color:blue">_***GET returns/responses***_ </span> are a representation in XML or JSON and a HTTP response code of <span style="color:blue">_***200 (OK)***_ </span> if everything is OK  
In an <span style="color:blue">_***error***_ </span> case, it most often returns a <span style="color:blue">_***404 (NOT FOUND)***_ </span> or <span style="color:blue">_***400 (BAD REQUEST)***_ </span>

---

## GET - Let's have a look

Launch dev tools in your browser:  
* Chrome - Shift + Ctrl + i  
* Firefox - Ctrl + Shift + k  
* Internet Explorer - F12  

Select the Network tab  
Browse to https://gitpitch.com/tonybruce/Traffic-Verbs-Testing-and-T-Shirts  
The first request should be the GET request for the page  
---
![Get](assets/get.jpg)
---
## POST

The <span style="color:blue">_***POST request***_ </span> is most-often utilised to <span style="color:blue">_***create***_</span> new resources
On successful creation, return <span style="color:blue">_***HTTP status 201***_</span>, returning a Location header with a link to the newly-created resource with the <span style="color:blue">_***201 HTTP status***_</span>
---
## POST - Let's have a look

TODO
---
## EXERCISE
![Get](assets/tshirt.png)

---
TODO needs work
TODO I don't understand the use of this

**Context**
We build questionnaires that help businesses collect feedback from their customers. One of our recent client is TODO

**Architecture**
Master data can be cloned to different client’s dataset. Client can then customize the cloned data using web services (REST API’s)


---
Your table needs to split into 3 parts:

Request/Response  
Client  
Server  

---
The t-shirts are the verbs
One person wears the t-shirt
The correct verb has to be written on the t-shirt  

---

At the client create the request
Each request needs - 
The correct verb
Any headers required
Any body required
TODO Anything else?
---

Take the request to the server
At the server create the response
Each response needs -
The correct status code
Any headers required
Any body required

---

There will be a decision made on correctness

---

TODO Poster with HTTP verbs
TODO Poster with status codes

TODO 
:Client:
URL - on the card
Headers - on the card
BODY for POST, PATCH - on the card
:Server:
RESPONSE code - write on sticky
RESPONSE BODY - on the card

---

