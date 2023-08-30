The Evolution of the Web: Tracing the history and development of web technologies: 
-The internet has inarguably been the most important technology revolution in the history of mankind and fortunately, we have been in the right generation to keep up and observe the wide impact that it has on the world
-World Wide Web is the primary tool used by billions of people to share, read, and write information to interact with other people via internet.
-The first version of web Web 1.0 also referred as Syntactic web or read only web is the era(1990–2000) where the role of a user is limited to reading information provided by the content producers.
-The Web 2.0 also referred as Social Web or read-write web is the era(2000–2010 and continues even now) which facilitates interaction between web users and sites which intern allows users to communicate with other users.
-In this era every user can be a content producers and content is distributed and shared between sites.
-The Web 3.0 also referred as Semantic Web or read-write-execute is the era(2010 and above) which refers to the future of web.
- In this era computers can interpret information like humans via Artificial Intelligence and Machine Learning.
###############################

 Problem-Solving with React:
-Before you start writing code for your web application, you need to think about the problems that your web application is going to solve.
-It’s very important to understand that defining the problem as clearly and as early as possible is the most important step toward a successful solution—a useful web application.
-If you fail to define your problem early in your development process, or you define it inaccurately, then later on you’ll have to stop, rethink about what you’re doing, throw away a piece of the code that you have already written, and write a new one
-Each React component should represent a single user interface element in your web application. It should encapsulate the smallest element possible that can potentially be reused.
-Multiple React components should be composed into a single React component.
###############################


 Problem-Solving with React:
-Before you start writing code for your web application, you need to think about the problems that your web application is going to solve.
-It’s very important to understand that defining the problem as clearly and as early as possible is the most important step toward a successful solution—a useful web application.
-If you fail to define your problem early in your development process, or you define it inaccurately, then later on you’ll have to stop, rethink about what you’re doing, throw away a piece of the code that you have already written, and write a new one
-•	Each React component should represent a single user interface element in your web application. It should encapsulate the smallest element possible that can potentially be reused.
-Multiple React components should be composed into a single React component.
###############################


Framework vs. Library:
Library:
    1- A set of assistance modules, objects, classes, functions, pre-written code, and so on.
    2- Can be easily substituted by another library.	
    3- When we call a method from a library, we are in control.	
    4- Since developing a library needs less code, performance and load time are improved.	
    5-Libraries can be simply linked into existing programs to add specific functionality.	
Framework:
    	1-Includes a variety of APIs, compilers, support applications, libraries, and so on.
        2-Are tough to replace.
        3-Inversion of control, i.e. the framework calls us.
        4-The construction of a framework necessitates large amounts of code, which reduces performance and increases load time.
        5-It is tough to incorporate a framework seamlessly into an existing project.
###############################

 Understanding React's Inner Workings:
 React JS works by using a virtual DOM (Document Object Model) to efficiently update and render components. The virtual DOM is a lightweight representation of the actual DOM, and React JS uses it to track changes and only update the necessary components instead of re-rendering the entire page.
###############################


 server side vs clint side
Server-side processes are executed on the web server, while client-side processes are executed on the user's device.
###############################

clint side Advantages
1-Faster and more responsive websites
2-Improved user experience
3-Reduced server load
4-Cross-platform compatibility
5-Enhanced security
###############################


Server side Advantages
 1-Content theoretically easier to crawl and be indexed.
2-Faster load times.
3-Ideal for static websites.
4-More accurate user metrics
###############################


React’s rendering mechanism:
Rendering is React’s process of describing a user interface based on the application’s current state and props. The initial render in a React app is the first render when the application starts up, while re-rendering occurs when there is a change in the state to figure out which parts of the UI need an update
###############################


DOM
The Document Object Model (DOM) is an application programming interface (API) for HTML and XML documents. It defines the logical structure of documents and the way a document is accessed and manipulated.
###############################


 virtual Dom:
The virtual DOM (VDOM) is a programming concept where an ideal, or “virtual”, representation of a UI is kept in memory and synced with the “real” DOM by a library such as ReactDOM.
###############################




Pros and Cons of Virtual DOM 
 advantages  the Virtual DOM:
1-Speed and performance boost
 2-Lightweight
3-It is simple and clear
4- Amazing diffing algorithm
5- It can be used on other frameworks not just react
 disadvantage virtual DOM:
1- Higher memory usage problems as the diffing algorithms need to keep comparing the elements to know which components needs to be updated or changed.
2- It is not easily integrated into many other frameworks.
3- You can’t use it or target template engines.
###############################

react Vs jquery
jQuery:
jQuery supports HTML/DOM manipulation
It also wraps HTML event methods
It provides CSS manipulation
It is easier to use effects and animations with jQuery
AJAX calls are simplified on jQuery
It is a library full of different utilities, including plugins for almost any kind of task out there
jQuery runs exactly the same on almost all major browsers

React :
Using React gives the developer access to React code snippets and components, thus they can create specific parts of an User Interface
By using JSX you can directly manipulate DOM
It also provides a Virtual DOM to improve the performance of the website
It is an open source project
There is a React library to attend to whatever specific UI function a developer needs to address
The React library is growing exponentially, along with the community’s curated library add-ons
###############################

React for Multi-Platforms:
1-Fast: Applying a cross-platform approach, developers can create applications quickly. 
2-Easy to maintain: With cross-platform development, solution maintenance is easier, since developers only have to update a single codebase rather than multiple.
3-Consistent user experience:By using cross-platform technologies, developers can ensure the user experience is consistent across all platforms. 
4-Interchangeable team: Instead of hiring developers with diverse skill sets, you can get a team of JavaScript developers who will be able to cover all your needs
5-Cost-efficient:Creating a single app for multiple platforms significantly cuts costs, as you don’t need to create a separate codebase for each platform and keep various developers on staff.
6-Wide reach:You can cover a wide range of platforms with a single codebase and expand your pool of potential users.
7-Large app size: Even the simplest cross-platform app often weighs 80–100MB without optimization
8-Integration issues: Cross-platform technologies often don’t give access to all the possibilities of an operating system (OS) because they don’t keep up with OS updates.
9-Performance: Native technologies are more efficient than cross-platform technologies, as they use a platform’s core programming language and APIs to compile.
###############################




References:
https://enonic.com/blog/what-is-the-difference-between-server-side-and-client-side#:~:text=In%20summary%2C%20server%2Dside%20and,executed%20on%20the%20user%27s%20device

https://aspiringyouths.com/advantages-disadvantages/client-side-scripting/


 https://www.searchenginejournal.com/server-side-rendering/481581/


https://www.w3.org/TR/REC-DOM-Level-1/introduction.html

 https://legacy.reactjs.org/docs/faq internals.html#:~:text=The%20virtual%20DOM%20(VDOM)%20is,a%20library%20such%20as%20ReactDOM

https://www.knowledgehut.com/blog/web-development/react-virtual-dom#how-is-virtual-dom-faster?%C2%A0

https://blog.bitsrc.io/building-with-react-for-all-platforms-5-top-frameworks-and-tools-affd5baf3de3

https://medium.com/@vivekmadurai/web-evolution-from-1-0-to-3-0-e84f2c06739
https://dev.to/pragativerma18/evolution-of-web-42eh
https://morioh.com/a/f94f948f1fd5/how-to-solve-a-problem-with-react
https://www.sencha.com/blog/difference-between-framework-vs-library-snc/#:~:text=Both%20the%20framework%20vs%20library%20is%20precoded%20support%20programs%20to,to%20develop%20a%20complete%20application.
https://www.upgrad.com/blog/jquery-vs-react/
https://www.telerik.com/blogs/understand-how-rendering-works-react#:~:text=Rendering%20is%20React's%20process%20of,the%20UI%20need%20an%20update.
https://www.linkedin.com/pulse/building-cross-platform-apps-react-native-how-run-app-multiple
