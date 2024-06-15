# Namaste React  
## Live Class 01 (Assignment) 
1.	What is Emmet ?
	Emmet is a plugin for text editors that allows for high-speed coding and writing of HTML and CSS with shortcuts. For example, typing ul>li*3 and expanding it with Emmet would generate:
    <ul>
    <li></li>
    <li></li>
    <li></li>
    </ul>

2.	Difference between Library and Framework?
Library: A collection of pre-written code that you can call to perform tasks. Eg: jQuery, Bootstrap
	Framework: `library` is a collection of packages that perform specific operations whereas a `framework` contains the basic flow and architecture of an application. Eg: Angular JS, Tailwind CSS

3.	What is CDN? Why do we use it?
	CDN (Content Delivery Network): A network of distributed servers that deliver web content to users based on their geographical location.
	Fast Load Times : content serve form servers.
	Reduce latency : Minimizes delays in content delivery.
	Scalability : handles high traffic loads efficiently.
	Reliability : Redundant servers ensure availability even if one server fails.

4.	Why React is known as React?
	The name React is derived from its core feature called reactive programming. React allows you to create interactive UIs by efficiently updating and rendering components in response to changes in data.
	Example: in React , when the state of a component changes, React “reacts” by re-rendering the component to reflect the new state.

5.	What is ‘crossorigin’ in script tag`?
	The `crossorigin` attribute sets the mode of the request to an HTTP CORS Request. The purpose of crossorigin attribute is used to share the resources from one domain to another domain. Basically, it is used to handle the CORS request. It is used to handle the CORS request that checks whether it is safe to allow for sharing the resources from other domains.

6.	What is diference between React and ReactDOM?
	React : react contains the core library for building UIs.
	ReactDOM : React DOM provides DOM-specific methods to render and update react components in browser

7.	What is difference between react.development.js and react.production.js files via CDN?
	react.development.js : initiated for development environments.
o	includes useful warnings and  errors with actionable advice for development/debugging. 
o	large file size due to additional development tools and non-minified code.
o	Less optimized for performance.
	 react.production.js :  optimized for production environment.
o	Code is minified and compressed to improve loading times.

8.	What is async and defer?
	 async and defer is used in <script> tags to control the loading and execution of external js file .
	Defer : load js asynchronously but executes it only after the HTML parsing is complete.
	Async : loads js asynchronously and execute it as soon as it’s download.
