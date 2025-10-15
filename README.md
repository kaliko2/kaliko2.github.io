<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>MindTap Coding Chapters 1-6</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 20px; line-height: 1.6; color: #333; }
    h1, h2 { color: #2c3e50; }
    section { margin-bottom: 40px; }
    pre { background: #f4f4f4; padding: 15px; overflow-x: auto; }
    code { font-family: Consolas, monospace; }
  </style>
</head>
<body>
  <h1>MindTap Coding: Chapters 1-6 Overview</h1>
  
  <section id="chapter1">
    <h2>Chapter 1: Introduction to HTML</h2>
    <p>Basics of HTML, elements, tags, and webpage structure.</p>
    <pre><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
  &lt;head&gt;
    &lt;title&gt;My First Page&lt;/title&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;h1&gt;Hello World!&lt;/h1&gt;
  &lt;/body&gt;
&lt;/html&gt;
</code></pre>
  </section>

  <section id="chapter2">
    <h2>Chapter 2: CSS Fundamentals</h2>
    <p>Styling HTML elements with CSS for colors, fonts, and layout.</p>
    <pre><code>body {
  background-color: lightblue;
  font-family: Arial, sans-serif;
}
h1 {
  color: navy;
}</code></pre>
  </section>

  <section id="chapter3">
    <h2>Chapter 3: JavaScript Basics</h2>
    <p>Introduction to JavaScript programming, variables, and output.</p>
    <pre><code>console.log("Hello, JavaScript!");</code></pre>
  </section>

  <section id="chapter4">
    <h2>Chapter 4: JavaScript Functions and Events</h2>
    <p>Understanding functions, event listeners, and interactive webpage elements.</p>
    <pre><code>function greet() {
  alert("Welcome to JavaScript Functions!");
}

document.getElementById("myBtn").addEventListener("click", greet);
</code></pre>
    <p>Example button to trigger JavaScript:</p>
    <button id="myBtn">Click Me</button>
  </section>

  <section id="chapter5">
    <h2>Chapter 5: DOM Manipulation</h2>
    <p>How to access and change HTML elements dynamically using JavaScript.</p>
    <pre><code>document.getElementById("demo").innerHTML = "Hello from JavaScript!";</code></pre>
    <p>Example:</p>
    <p id="demo">This text will change.</p>
    <button onclick="document.getElementById('demo').innerHTML = 'Text changed!'">Change Text</button>
  </section>

  <section id="chapter6">
    <h2>Chapter 6: Introduction to Arrays and Loops</h2>
    <p>Using arrays to store data and loops to iterate over data.</p>
    <pre><code>let fruits = ["Apple", "Banana", "Cherry"];

for(let i = 0; i &lt; fruits.length; i++) {
  console.log(fruits[i]);
}</code></pre>
  </section>

</body>
</html>
