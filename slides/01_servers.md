# Internet Fundamentals
By Ray Villalobos

<small>Use arrow keys to advance or esc</small>

---

# How the internet works
![Client Server Communication](images/clientserver.png)<!-- .element:  style="height: 200px"-->

- Client makes a request to a server.<!-- .element: class="fragment"-->
- The server routes the request to a service<!-- .element: class="fragment"-->
- Server sends data back to client<!-- .element: class="fragment"-->
- ...This happens a lot<!-- .element: class="fragment small"-->

---

# Internet Protocols

- Communication happens through protocols <!-- .element: class="fragment"-->
- The languages of the internet<!-- .element: class="fragment"-->
- Various server apps handle different<!-- .element: class="fragment"--> [protocols](http://en.wikipedia.org/wiki/Internet_Protocol)
- HTTP, Mail(pop, smtp), Chat, Video, FTP<!-- .element: class="fragment"-->

---

# Asking Servers for Resources
## **U**niform **R**esource **L**ocator

---

#**U**niform **R**esource **L**ocator

[http://www.youtube.com:80/watch?v=JSmGjB-G6v8&t=1m12s#top](http://www.youtube.com:80/watch?v=JSmGjB-G6v8&t=1m12s#top)

- The initial request/command<!-- .element: class="fragment"-->
- Tells the server what to do<!-- .element: class="fragment"-->
- Protocol, subdomain, domain, tld, port, path, query/parameters, fragments<!-- .element: class="fragment"-->

---

#**U**niform **R**esource **L**ocator
**http://** www.youtube.com:80/watch?v=JSmGjB-G6v8&t=1m12s#top</div>
## Protocol<!-- .element: class="blue"-->

- The language of the request<!-- .element: class="fragment"-->
- So server can send to the right place<!-- .element: class="fragment"-->
- http, mail, pop3, smtp, https, telnet, ftp, etc. <!-- .element: class="fragment"-->

---

#**U**niform **R**esource **L**ocator

http:// **www**.youtube.com:80/watch?v=JSmGjB-G6v8&t=1m12s#top</div>

## Subdomain<!-- .element: class="blue"-->

- A domain inside another domain<!-- .element: class="fragment"-->
- Helps you divide requests (images.google.com, mail.google.com)<!-- .element: class="fragment"-->
- Can also be used to forward requests (lynda.planetoftheweb.com)<!-- .element: class="fragment"-->

---

#**U**niform **R**esource **L**ocator

http:// www. **youtube** .com:80/watch?v=JSmGjB-G6v8&t=1m12s#top</div>

## Domain<!-- .element: class="blue"-->

- The location of a service<!-- .element: class="fragment"--> [on the internet](https://www.google.com/search?q=ip+address)
- Converted to IP addresses by DNS Servers<!-- .element: class="fragment"-->
- IP addresses = Zip Codes<!-- .element: class="fragment"-->
- DNS Servers = Post Office<!-- .element: class="fragment"-->

---

#**U**niform **R**esource **L**ocator

http:// www. **youtube** .com:80/watch?v=JSmGjB-G6v8&t=1m12s#top</div>

## A crucial decision<!-- .element: class="blue"-->

- Makes it easy or hard to find you<!-- .element: class="fragment"-->
- Most important SEO decision<!-- .element: class="fragment"-->
- Easy to remember, hard to misspell<!-- .element: class="fragment"-->
- careful of bad combos (gotahoe.com, penisland.com)<!-- .element: class="fragment"-->
- Use<!-- .element: class="fragment"--> [bust-a-name](http://bustaname.com)<!-- .element: class="fragment"-->

---

#**U**niform **R**esource **L**ocator

http:// www.youtube  **.com** :80/watch?v=JSmGjB-G6v8&t=1m12s#top</div>

## Top Level Domains<!-- .element: class="blue"-->

- Supposed to identify domain type<!-- .element: class="fragment"-->
- .com, .net, org, .gov<!-- .element: class="fragment"-->
- Can be country specific<!-- .element: class="fragment"--> [Monopo.ly](http://Monopo.ly)  <!-- .element: class="fragment"--> [Instagr.am](http://instagr.am)<!-- .element: class="fragment"-->

---

#**U**niform **R**esource **L**ocator

http:// www.youtube.com **:80** /watch?v=JSmGjB-G6v8&t=1m12s#top</div>

## Port Number<!-- .element: class="blue"-->

- A way to divide app requests<!-- .element: class="fragment"-->
- Different services on a server have defaults<!-- .element: class="fragment"-->
- :80 Web, :21 FTP, :25 SMTP <!-- .element: class="fragment"-->
- Can be used to hide services<!-- .element: class="fragment"-->
- Optional if using default<!-- .element: class="fragment"-->

---

#**U**niform **R**esource **L**ocator

http:// www.youtube.com:80 **/watch** ?v=JSmGjB-G6v8&t=1m12s#top</div>

## Path<!-- .element: class="blue"-->

- The App, page, file or service you want<!-- .element: class="fragment"-->
- Often a folder/file structure<!-- .element: class="fragment"-->
- Important for SEO ( iviewsource.com/?p=200 vs iviewsource.com/codingtutorials/its-time-to-add-lesssass-to-your-workflow )<!-- .element: class="fragment"-->

---

#**U**niform **R**esource **L**ocator

http:// www.youtube.com:80/watch **?v=JSmGjB-G6v8&t=1m12s** #top</div>

## Query/Parameters<!-- .element: class="blue"-->

- Information to pass along to an App<!-- .element: class="fragment"-->
- Name and Value Pairs separated by ampersands<!-- .element: class="fragment"-->

---

#**U**niform **R**esource **L**ocator

http:// www.youtube.com:80/watch?v=JSmGjB-G6v8&t=1m12s **#top**</div>

## Fragments<!-- .element: class="blue"-->

- Another way to pass info to an App<!-- .element: class="fragment"-->
- Normally a page within a page<!-- .element: class="fragment"-->
- Can be used for other purposes<!-- .element: class="fragment"-->

---

# Understanding Servers
## Your own piece of the net

---

#Understanding Servers
## Rent vs Own

- Every computer can be a server<!-- .element: class="fragment"-->
- Not all of them should be<!-- .element: class="fragment"-->
- Servers need: reliable power, fast connection, maintenance<!-- .element: class="fragment"-->

---

#Understanding Servers
## Types of servers

- Shared<!-- .element: class="fragment"-->
- Virtual<!-- .element: class="fragment"-->
- Dedicated<!-- .element: class="fragment"-->
- Cloud<!-- .element: class="fragment"-->
- App Hosting<!-- .element: class="fragment"-->

---

#Understanding Servers
## What to look for

- Throughput not speed/storage<!-- .element: class="fragment"-->
- Domains/Subdomains<!-- .element: class="fragment"-->
- Languages: PHP, Python, Sharepoint, .NET<!-- .element: class="fragment"-->
- Databases: How many?<!-- .element: class="fragment"-->
- Customizability<!-- .element: class="fragment"-->

---

# Web Developer Workflow
## Using the File Transfer Protocol

---

# Web Developer Workflow
## Getting a text editor

[![Adobe Brackets](images/brackets.png)<!-- .element: style="max-height:350px;"-->](http://www.brackets.io)

- Free Mac/PC Open Text Editor <!-- .element: class="fragment"-->
- Others: Sublime Text, Notepad++, Coda, Espresso, Dreamweaver  <!-- .element: class="fragment small"-->

---

# Web Developer Workflow
## Working with local files
1. Create a folder on desktop<!-- .element: class="fragment"-->
2. Create a new document<!-- .element: class="fragment"-->
3. Use the .html file extension<!-- .element: class="fragment"-->
4. Save it to folder<!-- .element: class="fragment"-->
5. Open with a browser to preview<!-- .element: class="fragment"-->
6. This is your local copy<!-- .element: class="fragment"-->

---

# Web Developer Workflow
##Getting an FTP Application

[![Cyberduck](images/cyberduck.png)<!-- .element: style="max-height:350px;"-->](http://www.cyberduck.io)

- Free Mac/PC FTP Application<!-- .element: class="fragment"-->
- Others: Transmit<!-- .element: class="fragment small"-->

---

# Web Developer Workflow
## Remote Workflow
- Download an FTP application<!-- .element: class="fragment"-->
- Set it up<!-- .element: class="fragment"-->
- Log onto your server<!-- .element: class="fragment"-->
- Upload your folder<!-- .element: class="fragment"-->
- Open the URL on a browser<!-- .element: class="fragment"-->
- students.pixelprowess.com/rvillalobos/filename<!-- .element: class="fragment"-->

---

# Web Developer Workflow
##Setting up Cyberduck

[![Cyberduck](images/cyberduck_setup.png)<!-- .element: style="max-height:350px;"-->](http://www.cyberduck.io)

- Type in domain, username and password<!-- .element: class="fragment small"-->
- Leave defaults<!-- .element: class="fragment small"-->

---

![Unix File Structure](images/unixfilestructure.png)

- Unix is a User Based System<!-- .element: class="fragment small"-->
- The root is the base folder of a file system<!-- .element: class="fragment small"-->
- Domains can be mapped to a folder<!-- .element: class="fragment small"-->
- A domain has its own root<!-- .element: class="fragment small"-->

---

# Web Site Folder Structure

![Unix File Structure](images/domainroot.png)

- Subdomains mapped to any folder<!-- .element: class="fragment small"-->
- If inside a domain it has 2 URLs<!-- .element: class="fragment small"-->
- index.html is the default<!-- .element: class="fragment small"-->

---

# Using sub-domains

![Unix File Structure](images/subdomains.png)

- Subdomains mapped to any folder<!-- .element: class="fragment small"-->
- If inside a domain it has 2 URLs<!-- .element: class="fragment small"-->
- index.html is the default<!-- .element: class="fragment small"-->

---

# The End
