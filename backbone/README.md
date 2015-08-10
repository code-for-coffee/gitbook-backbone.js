# Re-thinking Backbone.js

<p>You may have noticed that whenever you create a new Model, Collection, View, or Router that you <code>extend</code>
from Backbone.<code>type</code>. But what is <code>extend</code>?
<a href="http://backbonejs.org/" target="_blank"></a>The official documentation</a> states that
<em><strong>extend</strong> correctly sets up the prototype chain, so subclasses created with extend can be further
extended and subclassed as far as you like</em>. Since Backbone offers us the ability to create subclasses, a well
developed Backbone application can consist of a variety of classes.
</p>
