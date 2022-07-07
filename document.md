# Server-Side and Client-Side Rendering

### Server-Side Rendering
 * With server-side rendering, we deliver the content of a page by converting HTML files in the server into usable information for the browser.
  
 * When we visit a website, our browser makes a request to the server which contains the contents of the website. After the request, server renders and delivers the rendered HTML response. After our browser receives the response, it displays the page on our screen. 

 * If we decide to visit a different page, our browser will make a request again for that new page. This process will repeat as long as we ask for new pages. (If the browser doesn't have the page in its cache.)

 * Even only one line of HTML code changes, browser has to make a request for entire page.

<img title="Server-Side Rendering" src="./ssr.png">

#
### Client-Side Rendering
 * With client-side rendering, we are rendering the content in the browser with the help of client-side scripting languages like JavaScript. 
  
 * So the server delivers bare HTML document with JavaScript file (or with any other server-side scripting language) and allows the browser to render the website.

<img title="Server-Side Rendering" src="./csr.png">