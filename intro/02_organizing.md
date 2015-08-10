## 2. Organizing your project</h1>
**The use of namespaces for your objects**

<p>Once you decide on a project structure, it is best to organize your code. We will start with creating namsepaces for each
type of Backbone object (Models, Views, Collections, and Routers).</p>

<script src="https://gist.github.com/code-for-coffee/f16270321e3d01c61c60.js"></script>

<p>Inside of the namespaces, you can then store your Backbone objects like so:</p>

<script src="https://gist.github.com/code-for-coffee/f321460914e3a5f90cf4.js"></script>

<p>By namespacing your objects, you make them globally accessible! You also keep your object types organized together.</p>

<script src="https://gist.github.com/code-for-coffee/30ae561ffa229deb4a74.js"></script>

<p>However, we can step our game up - if we an organize our base types, why not do the same with our instantiated objects?
To do so, we'll need to declare object containers for <em>active</em> elements. Please don't hesistate to change the naming
of your namespaces; the provided ones are just for an example.</p>

<script src="https://gist.github.com/code-for-coffee/7207e0008e9d3a4be97b.js"></script>

<p>Now you'll be able to globally access any Backbone object type or any instantiated object whenever you need to.</p>
