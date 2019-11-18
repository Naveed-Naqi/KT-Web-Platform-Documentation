<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>index.html</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><h1 id="design-doc">Design Doc</h1>
<p><a href="http://google.com">a relative link</a></p>
<h1 id="dev-log">Dev Log</h1>
<h1 id="style-guide">Style Guide</h1>
<h1 id="workflow">Workflow</h1>
<p><a href="https://reactjs.org/docs/thinking-in-react.html">Thinking in React</a><br>
Keep an up to date react component diagram for the entire project.<br>
Work from the bottom up.</p>
<h1 id="github">Github</h1>
<h1 id="testing">Testing</h1>
<h2 id="postman">Postman</h2>
<p>In order to test our backend API, please download <a href="https://www.getpostman.com/">Postman</a></p>
<h2 id="front-end">Front End</h2>
<p>Please download the <a href="https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en">React Developer Tools Chrome Extension</a> to make local testing and debugging easier.<br>
It will allow you to view React components and hierarchies in the Chrome Development Console.</p>
<h1 id="technologies">Technologies</h1>
<h2 id="node.js">Node.js</h2>
<h3 id="serverside-dependencies">Serverside Dependencies</h3>
<h3 id="clientside-dependencies">Clientside Dependencies</h3>
<h2 id="express.js">Express.js</h2>
<h2 id="mongodb-with-mongoose">MongoDB With Mongoose</h2>
<h3 id="mongodb">MongoDB</h3>
<h3 id="mongoose">Mongoose</h3>
<h2 id="react--redux-with-material-ui">React + Redux with Material UI</h2>
<h3 id="react">React</h3>
<p>If you are using Visual Studio Code, please download the following extensions:</p>
<ul>
<li><a href="https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel">Babel Javascript</a>
<ul>
<li>Provides excellent syntax highlighting</li>
</ul>
</li>
<li><a href="https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets">ES7 React/Redux/GraphQL/React-Native snippets</a>
<ul>
<li>Allows very quick setup of new react components
<ul>
<li>“rcc” + tab for a new class based component</li>
<li>“rfc” + tab for a new function based component</li>
</ul>
</li>
</ul>
</li>
<li><a href="https://medium.com/@eshwaren/enable-emmet-support-for-jsx-in-visual-studio-code-react-f1f5dfe8809c">Make these changes to your settings.json</a></li>
</ul>
<h4 id="things-to-know">Things to know</h4>
<ul>
<li><a href="https://daveceddia.com/why-not-modify-react-state-directly/">Do not update state directly!</a></li>
<li><a href="http://projects.wojtekmaj.pl/react-lifecycle-methods-diagram/">Lifecycle Methods Diagram</a></li>
<li><a href="https://reactjs.org/docs/faq-state.html#what-is-the-difference-between-state-and-props">state vs props</a></li>
<li><a href="https://medium.com/@lcriswell/destructuring-props-in-react-b1c295005ce0">Destructure props</a></li>
<li>Class based components:
<ul>
<li>Contain state.</li>
<li>Contain lifecycle hooks.</li>
<li>Don’t care about UI</li>
</ul>
</li>
<li>Function based components:
<ul>
<li>Do not have state.</li>
<li>Get data from props.</li>
<li>ONLY care about UI</li>
</ul>
</li>
</ul>
<h3 id="redux">Redux</h3>
<p>Central data store for all app data.<br>
Any component can access data from it, which means we no longer have to juggle component data.</p>
<h3 id="material-ui">Material UI</h3>
<h1 id="services">Services</h1>
<h2 id="aws-lightsail">AWS Lightsail</h2>
<h3 id="setting-up">Setting up</h3>
<h3 id="deploying-application">Deploying Application</h3>
<h2 id="mongodb-atlas">MongoDB Atlas</h2>
<h3 id="setting-up-1">Setting Up</h3>
<h3 id="connecting-to-aws">Connecting to AWS</h3>
</div>
</body>

</html>
