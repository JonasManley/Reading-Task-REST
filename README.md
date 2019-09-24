# Reading-Task-REST

<h3>DESCRIPTION</h3>

* In year 2000, the software engineer and researcher <a href=https://roy.gbiv.com/>Roy Fielding</a> published his <a href=https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm>PhD thesis</a>, entitled: <br>
Architectural Styles and the Design of Network-based Software Architectures, in which he introduced and defined the concept behind the now so popular abbreviation REST.

<h2>Read the document and try to find the answers of the following questions:</h2>

**1. What exactly is REST? How does the context of it fits to the title of the dissertation?**

* REST stands for **RE**presentational **S**tate **T**ransfer. 
When a REST webservice (REST API) is called, the server will transfer a representation of the state of the requested resource to the client. <br>
E.g. if you ask Facebooks API about a specific user, you will get the whole state: username, name, birthday, emial etc.

* **Client-Server**:<br>
By separating the user interface concerns from the data storage concerns, we improve the portability of the user interface across multiple platforms and improve scalability by simplifying the server components.

* **Stateless**:<br>
Communication must be stateless in nature, such that each request from client to server must contain all of the information necessary to understand the request, and cannot take advantage of any stored context on the server. Session state is therefore kept entirely on the client.

* **Cache**: <br>
Cache constraints require that the data within a response to a request be implicitly or explicitly labeled as cacheable or non-cacheable. If a response is cacheable, then a client cache is given the right to reuse that response data for later, equivalent requests.<br>
The advantage of adding cache constraints is that they have the potential to partially or completely eliminate some interactions, improving efficiency, scalability, and user-perceived performance by reducing the average latency of a series of interactions. The trade-off, however, is that a cache can decrease reliability if stale data within the cache differs significantly from the data that would have been obtained had the request been sent directly to the server.

* **Uniform Interface**:<br>
By applying the software engineering principle of generality to the component interface, the overall system architecture is simplified and the visibility of interactions is improved. Implementations are decoupled from the services they provide, which encourages independent evolvability. The trade-off, though, is that a uniform interface degrades efficiency, since information is transferred in a standardized form rather than one which is specific to an application's needs.

* **Layered System**:<br>
Layered system style allows an architecture to be composed of hierarchical layers by constraining component behavior such that each component cannot "see" beyond the immediate layer with which they are interacting. By restricting knowledge of the system to a single layer, we place a bound on the overall system complexity and promote substrate independence.

* Unlike SOAP, REST is not constrained to return data in XML, but instead can return XML, JSON, YAML or any other format depending on what the client requests.


**2. Why is the dissertation considered so important for the software-architectural world?**
I has become very simple and light weight and fast with the introduction of the REST webservice! 


**3. Which is the most valuable outcome you personally get from it?**
* They are easy to use & create and works very well in applications that handles different data and data requests.

**4. How could you implement it in your own practice as a software developer?**
* use them as much as posible? 


_Submit the answers here and read the answers of at least three of your colleagues, to validate your and their vision<br>_

_The task is individual._
