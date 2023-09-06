Evolution of the web

The internet has come a long way since its inception in the late 20th century. From basic websites with static text and images to advanced web applications capable of personalized experiences and complex functionalities, the internet has evolved into Web 3.0.
WEB 1.0: 
Web 1.0 is the ancestor of the internet that we use today. It was a static web, where users could only read or view the content and had no ability to interact with it. Websites were designed using HTML and CSS, and it was a one-way communication with web pages composed of plain text and images. There was no database connectivity and the pages were not interactive. The search engines of this time like Yahoo operated as web directories as they were manually analyzed and categorized by human editors. The characteristics of Web 1.0 were limited, there was no social media or user-generated content. Most people were not yet aware of the power of the internet, and it was used primarily for personal homepages. Online marketing and advertising were also not yet widely adopted. The design was basic with a simple layout and color scheme.
WEB 2.0:
Web 2.0 refers to the second generation of the World Wide Web characterized by interactive and user-centered web applications and sites. Unlike Web 1.0 which was static, Web 2.0 websites are more dynamic, collaborative and feature-rich.Sites such as Wikipedia, Facebook, YouTube, and Twitter are all examples of Web 2.0 sites. They are built with the user in mind, allowing the user to easily create, collaborate and share content.But what distinguishes Web 2.0 from its earlier counterpart, Web 1.0? The first major difference is that Web 2.0 uses dynamic content, whereas Web 1.0 uses static content. Web 2.0 also encouraged participation and collaboration with other users, allowing for more user-generated content. Web 2.0 sites are also characterized by their use of open-source software and web applications that operate without the need to install software on a user’s device. This allows for increased convenience and mobility, as the user can access their accounts on other devices. Overall, Web 2.0 has revolutionized the way we interact online. From social media to job networking, e-commerce, and digital marketing, Web 2.0 sites have transformed the internet landscape beyond recognition. It’s safe to say that, without Web 2.0, our digital lives would be very different today.
WEB 3.0:
 Web 3.0 is the future of the Internet that is characterized by advanced technologies and applications that provide a more personalized and relevant experience to the user. It uses machine-based intelligence, natural language processing, and ontology-based metadata to create comprehensive databases of information that can be easily accessible and understandable. With the emergence of Blockchain, Artificial Intelligence, and the Internet of Things, the Web 3.0 environment will continue to evolve and thrive.



https://www.linkedin.com/pulse/evolution-internet-web-10-20-30-deepak-lyngdoh#:~:text=In%20this%20article%2C%20we%20will,exciting%20world%20of%20web%20evolution!&text=Web%201.0%20is%20the%20ancestor%20of%20the%20internet%20that%20we%20use%20today.


//////////////////////////////////////////////////////////////////////////////////////////////////////////////
The Rendering Process in the Past: Exploring how web documents were displayed in earlier times:
The rendering phase includes 8 sub-phases:
* 		The main thread in the renderer process “translates” the HTML document to DOM tree
* 		It conveys CSS into the computed style
* 		It creates a layout tree based on the DOM tree and computed style
* 		From a layout tree, it generates a layer tree
* 		Lastly, it establishes paint records
* 		The compositor thread carries over the paint records, starts tilling based on the current viewport
* 		Multiple raster threads raster tiles into bitmaps with the help of the GPU process.
* 		The browser process receives the Draw Quad command from the browser process, then it displays a frame of the page in front of us.
* 
Two threads in the renderer process are involved in:
* 		The main thread takes care of the 1–5 phases
* 		The compositor thread manages the 6–8 phases




https://cabulous.medium.com/how-does-browser-work-in-2019-part-iii-rendering-phase-i-850c8935958f

//////////////////////////////////////////////////////////////////////////////////////////////////////////////
Problem-Solving with React:
* Understanding the Problem
* Analyzing and Breaking Down the Problem
* Formulating a Solution
* Implementing and Testing the Solution
* Iterating on the Solution


https://www.cronj.com/blog/finding-react-developers-focus-on-problem-solving-and-debugging-skills/

//////////////////////////////////////////////////////////////////////////////////////////////////////////////
Benefits of Framework Utilization: 
1-A basic code structure is already developed, reduces time, and improves efficiency in building new applications.
2-Minimizes time invested in building essential application components, saving time and overhead associated with application development.
3-Developer productivity is improved by allowing developers to focus on the unique requirements of their application instead of spending time on application infrastructure (“plumbing”).
4-Ability to reuse code that has been pre-built and pre-tested. 
5-A framework can help establish better programming practices and naturally enforce appropriate use of design patterns and new programming tools. 
6-Reinforces Security.
7-Improves Database Proficiency.
8-Makes easier the Development Process
9- Eases Debugging and Application Maintenance
10-Reduces Code Length

https://www.profoundlogic.com/benefits-of-frameworks/#:~:text=Frameworks%20provide%20improved%20code%20readability,Reinforces%20Security.
https://www.creative-tim.com/blog/educational-tech/benefits-frameworks-development/


//////////////////////////////////////////////////////////////////////////////////////////////////////////////
Framework vs. Library:
framework
1-It is tough to incorporate a framework seamlessly into an existing project.
2-A framework inverts the control of the program. It tells the developer what they need.
3-the framework controls the flow and calls your code.
4-Frameworks consist of a lot of APIs, compilers, toolsets, support programs, libraries, etc.
5-Despite the fact that frameworks generate new codes for developers. These codes cannot be altered or modified later. Unlike libraries, frameworks do not allow users to modify their pre-written codes, so you don’t have to worry about deleting or changing them.
6-you can only call and use what belongs to a Framework within the same Framework. 
7-Using them, you can build and deploy applications in a standard way as the framework already provides code to perform common tasks and uses code provided by a developer for custom functionality.
8-Frameworks provide general functionality. Because of this, they are built to be extensible, which allows developers to incorporate app-specific features without modifying the framework’s source code.
9-Frameworks are difficult to replace.
10-Developing a framework requires a lot of coding, which increases loading times and decreases performance.
11-Frameworks can be used for performing a wide range of tasks.
12-Incorporating frameworks seamlessly into an existing project is impossible.
13-Faster programming, support from the community, great support for MVC (Model View Controller) pattern, etc.




library
A library is a group of pre-written codes that make jobs easier to complete. A library is a collection of pre-defined methods and classes that developers can use to ease their work and accelerate development. As a result, developers do not need to write code to achieve specific features. Most programming languages include standard libraries, but developers can create their own customized libraries.
1-Libraries can be simply linked into existing programs to add specific functionality.
2 The programmer calls the library where and when they need it.
3-Libraries provide developers with predefined functions and classes to make their work easier and boost the development process.
4- you can control the flow of the application and call the library. 
5-Generally, libraries are a collection of helper modules, objects, classes, functions, message templates, pre-written code, etc.
6-Codes in libraries are geared toward a particular program or to solve a specific development problem. Therefore, developers must modify library code to meet their needs.
7-It is possible to call a library out of context. You may use the library wherever you see fit in your code.
8-n the program linking and binding process, they play an important role.
9- libraries aren’t designed for extensibility; they are designed to accomplish a specific purpose.
10-It is easy to replace a library with another library.
11-Less code is required to build libraries, which leads to faster loading times and better performance.
12-The purpose of libraries is to perform a defined and specific task.
13-You can integrate libraries seamlessly into existing projects to add functionality. 
14-Good code quality, reusability, and control, enhanced speed and performance of the program, etc.


https://www.sencha.com/blog/difference-between-framework-vs-library-snc/#:~:text=Both%20the%20framework%20vs%20library%20is%20precoded%20support%20programs%20to,to%20develop%20a%20complete%20application.
https://www.freecodecamp.org/news/the-difference-between-a-framework-and-a-library-bd133054023f/
https://www.interviewbit.com/blog/framework-vs-library/



//////////////////////////////////////////////////////////////////////////////////////////////////////////////
Differentiating between client-side and server-side in web applications:
server-side : 
	Server-side processes are executed on the web server before the web application is delivered to the user's device.
	Server-side processes have more access to resources and are more secure
	requires a server and services environment to compile and execute.
	Languages used: PHP, Python

client-side:
	Client-side processes are executed on the user's device after the web application is delivered.
	client-side processes have less access to resources and are potentially less secure
	It’s easy to learn
	needs only a browser to run
	Languages used: HTML, CSS, JavaScript


https://enonic.com/blog/what-is-the-difference-between-server-side-and-client-side#:~:text=In%20summary%2C%20server%2Dside%20and,executed%20on%20the%20user's%20device.

//////////////////////////////////////////////////////////////////////////////////////////////////////////////
Advantages of Client-Side Development:
* It’s easy to learn
* It gives you the chance to show off your creative side
* You can create really cool sh*t that’s dynamic and fun to use
* 99% of client-side libraries and development tools are free to use, with only a few resources that have a cost attached


https://medium.com/@donotapply/client-side-vs-server-side-whats-the-difference-a933341cd60e
//////////////////////////////////////////////////////////////////////////////////////////////////////////////

Advantages of Server-Side Development:
1-It’s complicated, dynamic, and yes, we’re also gonna say that it’s beautiful and artistic.
2-Connecting websites to databases
3-Restoring and backing up files


https://www.indeed.com/career-advice/career-development/client-side-vs-server-side

https://medium.com/@donotapply/client-side-vs-server-side-whats-the-difference-a933341cd60e
//////////////////////////////////////////////////////////////////////////////////////////////////////////////

React's Rendering Mechanism:
-Rendering is a process that is triggered by a change of state in some component of your application, when a state change occurs React.
-The render phase is the initial phase of the rendering process. In this phase, the JSX code is converted to a JavaScript representation of what the HTML structure should look like.
On the initial render, it starts from the root component and works its way down, building out a React element tree of what the actual DOM should look like.
Re-rendering follows a similar approach but with a key difference: it creates a new JavaScript representation of the DOM, identifying all the components marked as needing an update. After this, it uses a process known as diffing to identify the changes between the old and new tree of React elements (aka the virtual DOM).

https://dev.to/mateo_garcia/understanding-rendering-in-react-i5i
https://www.telerik.com/blogs/understand-how-rendering-works-react

//////////////////////////////////////////////////////////////////////////////////////////////////////////////

The Document Object Model (DOM):
The Document Object Model (DOM) connects web pages to scripts or programming languages by representing the structure of a document—such as the HTML representing a web page—in memory. Usually it refers to JavaScript, even though modeling HTML, SVG, or XML documents as objects are not part of the core JavaScript language.
Document Object Model (DOM) is a platform and language-neutral interface that allows programs and scripts to dynamically access and update the content, structure, and style of a document.
The Document Object Model, usually referred to as the DOM, is an essential part of making websites interactive. It is an interface that allows a programming language to manipulate the content, structure, and style of a website. JavaScript is the client-side scripting language that connects to the DOM in an internet browser.

https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model
https://www.w3schools.com/js/js_htmldom.asp
https://www.digitalocean.com/community/tutorial-series/understanding-the-dom-document-object-model

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Virtual DOM:
The virtual DOM (VDOM) is a programming concept where an ideal, or “virtual”, representation of a UI is kept in memory and synced with the “real” DOM by a library such as ReactDOM. This process is called reconciliation.
A virtual DOM object has the same properties as a real DOM object, but it lacks the real thing’s power to directly change what’s on the screen.
Manipulating the DOM is slow. Manipulating the virtual DOM is much faster because nothing gets drawn onscreen. Think of manipulating the virtual DOM as editing a blueprint, as opposed to moving rooms in an actual house.
A virtual DOM object is the same as a real DOM object, except that it is a lightweight copy. This means that it cannot manipulate on-screen elements. Moreover, upon any change of a property, it only updates the corresponding nodes and not the entire tree. That makes it a quick and efficient alternative.

https://legacy.reactjs.org/docs/faq-internals.html
https://www.codecademy.com/article/react-virtual-dom
https://www.educative.io/answers/what-is-the-difference-between-virtual-and-real-dom-react

//////////////////////////////////////////////////////////////////////////////////////////////////////////////

Pros and Cons of the Virtual DOM
pros:
	It is a lightweight copy of the original DOM
	Performance is fast and UX is optimised
	Highly efficient as it performs batch updates
	Updates are lightweight
	 Simple Use

cons:
 Memory Overhead
It is not easily integrated into many other frameworks.


https://www.geeksforgeeks.org/reactjs-virtual-dom/

//////////////////////////////////////////////////////////////////////////////////////////////////////////////


React vs. jQuery:
React:
* Using React gives the developer access to React code snippets and components, thus they can create specific parts of an User Interface
* By using JSX you can directly manipulate DOM
* It also provides a Virtual DOM to improve the performance of the website
* It is an open source project
* There is a React library to attend to whatever specific UI function a developer needs to address
* The React library is growing exponentially, along with the community’s curated library add-ons

jQuery:
* jQuery supports HTML/DOM manipulation
* It also wraps HTML event methods
* It provides CSS manipulation
* It is easier to use effects and animations with jQuery
* AJAX calls are simplified on jQuery
* It is a library full of different utilities, including plugins for almost any kind of task out there
* jQuery runs exactly the same on almost all major browsers

https://www.upgrad.com/blog/jquery-vs-react/
