# Interviews
Questions to study or use in technical interviews.

### What NPM stands for? 
`frontend` `backend`

NPM stands for "Node Package Manager". It is a package manager for the JavaScript programming language, primarily used for managing dependencies of Node.js applications. NPM allows developers to easily install, manage, and share packages of code that can be used in their projects. It is one of the most popular package managers in the JavaScript ecosystem.

### What is scope in JavaScript? 
`frontend` `backend`

JavaScript scope refers to the accessibility and visibility of variables and functions within a specific portion of a program. There are two types of scope: global, which means variables and functions can be accessed from anywhere in the program, and local, which means they can only be accessed within a particular function or block. JavaScript uses lexical scoping to determine the scope of a variable based on its position in the code. This affects how variables are accessed and manipulated in a program, making it essential to understand scope for writing efficient and maintainable code.

### What is Strict Mode?
`frontend` `backend`

Strict Mode is a feature introduced in ECMAScript 5 for JavaScript that enforces a stricter set of rules for writing JavaScript code. It helps prevent common programming mistakes, making code more secure and reliable. Some key features of Strict Mode include disallowing the use of undeclared variables, requiring unique property names in objects, preventing duplicate function parameters, disallowing the deletion of certain variables or function names, and preventing the use of eval or arguments as variable names. To enable Strict Mode, add the string literal 'use strict' at the beginning of a JavaScript file or function. When enabled, it will throw errors for any violations of the rules, making it easier to identify and fix potential issues.

### Ways to decrease page load time?
`frontend` `backend` `devops`

To decrease page load time, optimize images by compressing and reducing their size, minimize HTTP requests by using CSS sprites and combining files, use a content delivery network (CDN) to distribute content, enable browser caching, minify code to remove unnecessary characters, and choose a fast and reliable web hosting provider. Implementing these optimization techniques can help improve your website's load time and provide a better user experience to your visitors.

### What is Version Control System (VCS)?
`frontend` `backend` `devops`

A version control system (VCS) is a software tool that helps developers manage changes to source code, documents, and other files. It tracks and records changes made to files over time, enabling users to retrieve specific versions of a file or project and collaborate with others on shared files. VCS provides a centralized repository where users can access and work on files, and it also enables multiple users to work on the same file simultaneously, merging changes into a single version. With VCS, developers can keep track of changes, review code, identify and fix bugs, and roll back to previous versions if needed. VCS is widely used in software development and is essential for maintaining code quality, ensuring stability and security, and supporting collaboration among team members.

### How to migrate from Node 16 to Node 18?
`frontend` `backend`

1. Update Node.js: Install the latest version of Node.js (version 18) on your system. You can do this using a package manager like npm or yarn, or by downloading the binary directly from the Node.js website.
2. Check for breaking changes: Review the Node.js release notes for version 18 to identify any breaking changes that may impact your project. Make sure to update any code or dependencies that are affected by these changes.
3. Test your project: Run your project's test suite to ensure that everything still works as expected with the updated version of Node.js. Be sure to test all aspects of your application, including any third-party libraries and frameworks you are using.
4. Update dependencies: If you encounter any issues during testing, check if there are any updates available for your project's dependencies. Update any dependencies that are outdated or incompatible with Node.js version 18.
5. Deploy your project: Once you have successfully tested your project with Node.js version 18 and updated any dependencies, you can deploy it to production.

### How to generate a .pdf using JavaScript?
`frontend`

To generate a PDF using JavaScript, you can use a library such as jsPDF or PDFKit. These libraries provide APIs to create PDF documents and add text, images, and other elements to them. You can use JavaScript to dynamically generate content and then use these libraries to create a PDF document from that content. Once the PDF is generated, you can choose to save it to the server or allow the user to download it directly.

### What is debouncing in web development?
`frontend`

In web development, debouncing is a technique used to handle performance problems caused by input events, such as button clicks or typing in input fields. Without debouncing, these events can trigger excessive actions, such as network requests or UI updates, overloading the system and affecting the user experience.

The debouncing technique involves delaying the execution of the action triggered by the input event, waiting for a brief period of time before allowing the action to be executed. If the input event occurs again during this period, the timer is reset and the delay is extended. When the delay expires without the occurrence of another input event, the action is finally executed.

For example, when handling a form submit button, it is common to use the debouncing technique to prevent duplicate or unnecessary submissions. The same can be applied to input fields, such as search fields, where debouncing can be used to delay the execution of the search until the user has finished typing or to minimize the number of requests to the server.
