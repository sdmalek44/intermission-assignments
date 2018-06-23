## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page?  
First thing that happens is that your browser checks your cache to see if it knows the ip address for that site. If not it sends a request to the resolving name server asking if it knows the ip address of www.example.com. The resolving name server will tell check the correct root server for the answer. The root server will tell the resolving server which top level domain servers to ask about this url. The resolving name server will then ask the top level domain server, in this case .com server, if it knows the ip for this url. The .com server will tell the resolving name server to check the authoritative name server for www.example.com. The authoritative name server should respond with the ip address for this url. The resolving name server will take this response and give it back to your computer which allows you to access the website www.example.com. 
  
1. What does HTTP stand for?  
Hypertext transfer protocol declares how browser communicates with web servers. 
1. What protocol does the World Wide Web use?  
Hypertext transfer protocol is used by the world wide web. 
1. Each computer on the Internet is assigned an IP address, what does IP stand for?  
IP address stands for Internet Protocol address. 
1. What does DNS stand for?  
A. Domain Name System
  
1. How are text domain names matched to their respective numeric IP addresses.  
When you enter a url the browser checks the resolving name server. If it doesn't have the right ip address for that domain it will check the root server, then the top level domain server, and then the authoritative name server for the answer and then return it to the user for access to that website. 
    
1. What is the client?  
C. The software which requests information from a server (browser)
 
1. What does URL stand for?  
Uniform Resource Locator. It is the web address where the desired resources are located. 
   
1. What are protocols?  
D.	The standardised method for transferring data or documents over a network
 
1. What does DNS stand for?  
DNS stands for Domain Name System.
    
1. what is the `www` portion of a url?  
It stands for World Wide Web. It is a subdomain. 
   
1. What is The markup language used for all web documents?  
Hypertext Markup Language(HTTP) is used for all web documents. 
   
1. What is the organization that monitors web technologies?  
World Wide Web Consortium is an international community that develops web standards. 
   
1. What is the Protocol for transferring web documents on the Internet?  
Hypertext Transfer Protocol(HTTP)
   
1. What matches the domain names with numeric IP addresses?  
The DNS or Domain Name System matches domain names with numeric IP addresses. 
   




