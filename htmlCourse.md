# HTML Course documentation (Mosh Hamedani)

### Tools used ⚙
- VS code
- Chrome
- Live Server (VS extension)

### What we will learn
- The languages & tools of web development 
- Key concepts (eg URL, HTTP, DOM, etc) 
- How websites work 
- Inspect network traffic using DevTools 
- Basics of HTML & CSS Validating web pages 

### Languagues
- **HTML** Hypertext Markup Language 
- **CSS**  Cascading Stylesheet, Styling Language
- **JavaScript** Programming Language 

### Roadmap
<br>

![image](https://user-images.githubusercontent.com/82268112/157718796-0497c1c8-be71-4e55-a93e-9bd53f2d62e0.png)

### How web works? 🌐
<br>

![image](https://user-images.githubusercontent.com/82268112/157720040-dd5004ee-43b6-460f-b0ba-208d7ef5696b.png)\
The user (client) send a http request(url) containing resource, and host name. The server process the request and sends back a response containing the required document(html, image, etc).\
The browser then construct the DOM(Document Object Model) based on the response it recieves from the server. The browser may also some request parallely if there are some objects in the document that require some images or any other assets store in some other location. And then render the response properly. \

### Developer Tools 💻
``` (Ctrl + Shift + I) ``` to open developer tab.
Under **Network** tab we can see all the request the browser is making to the server and what response it is getting. How much mb of data is transferred between the browser and the server and also the number of request in the bottom of the tab.

### HTML Basics 🔠
- Html is **case-insensitive** language.
- Basic structure.
<br>

![image](https://user-images.githubusercontent.com/82268112/157735959-ca2c2f8c-e76d-4e15-af14-b3fc77005404.png)

### Validation of HTML and CSS, Inspecting in browser ✅
We can inspect in browser and fix or adjust some ui elements. We should use Html and CSS validator to check for the issues or error we have in the following documents and best practices.

### Stuffs to learn 📃
<br>

- Texts
- Links 
- Images
- Tables
- Container Elements
- Structural Elements

### Head part
 
The head contains title, and some meta data about our html document.
Meta description contains description about our page. It will be displayed on the browser as a description of this document.
Meta keywords for search engine optimization.
charset and so on...

### Texts 🅰
Texts contains lot of different class like p and h for headings.\
We have 6 different types of headings h1 ... h6.\
The most important thing for heading is they should be in heirarchy.\
There should be only 1 h1 in whole html document depicting the importance of h1. It says what this page is all about.\
If we use more than one then it confuses the Search Engine and It makes it less optimistic.\

### Entities 
starts with ```&``` and ends with ```;```.
&lt; gives -> <
&gt; gives -> >
&copy; gives ©

### Links













