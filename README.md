# getElementById()
~~~
The Document method getElementById() returns an Element object representing the element whose id property matches the specified string. 
~~~
# What is DOM?
~~~
when a webpage or HTML page loads in the browser,browser 
create a DOM.

Document=HTML page
OBJECT=Tag or Element & attributes in a html page.

Model=Tree structure of Html Element.
~~~

# DOM Nodes
~~~
The entire document is a document node
Every HTML element is an element node
The text inside HTML elements are text nodes
Every HTML attribute is an attribute node 
All comments are comment nodes
~~~
# InnerHTML
~~~
The innerHTML property to retrieve the content of an HTML element.
~~~

# nodeName Property
~~~
nodeName is read-only
nodeName of an element node is the same as the tag name
nodeName of an attribute node is the attribute name
nodeName of a text node is always #text
nodeName of the document node is always #document
~~~
# The addEventListener() method
~~~
The addEventListener() method attaches an event handler to the specified element.

The addEventListener() method attaches an event handler to an element without overwriting existing event handlers.

You can add many event handlers to one element.

You can add event listeners to any DOM object not only HTML elements. i.e the window object.

The addEventListener() method makes it easier to control how the event reacts to bubbling.

When using the addEventListener() method, the JavaScript is separated from the HTML markup, for better readability and allows you to add event listeners even when you do not control the HTML markup.

You can easily remove an event listener by using the removeEventListener() method.
~~~~
