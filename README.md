#solid Principle
 <h2>SOLID Design Principles</h2>
 
<h3><b>SOLID Design Principles</b></h3>
<p>The SOLID design principles are the design principles that help us solve most software design problems. They provide us with multiple ways to move tightly coupled code between software components, making software designs more understandable, flexible, and maintainable.</p>
 <h2><b>Advantages of SOLID Design Principles in C#</b></h2>
  <p>As a developer, while designing and developing any software application, you need to consider the following points:</p>
    <ul>
        <li>Maintainability</li>
        <li>Testability and Extensibility</li>
        <li>Parallel Development</li>
    </ul>

<h3><b>1. What is the Single Responsibility Principle?</b></h3
<p>The Single Responsibility Principle states that "Each software module or class should have only one reason to change.
 " In other words, we can say that each module or class should have only one responsibility.</p>
<p>
We need to design the software so that everything in a class or module relates to a single responsibility. That does not mean your class should contain only one method or property; you can have multiple members (methods or properties) as long as they are related to a single responsibility or functionality. With the help of SRP in C#, the classes become smaller, cleaner, and easier to maintain.
</p>
Note:if we don't follow the SRP than we end up having 
<ul>
<li>Difficult to Understand</li>
<li>Difficult to Test</li>
<li>Chance of duplicating the logic of other parts of the application</li>
</ul>


<hr>

<h3><b>What is the Open-Closed Principle?</b></h3>

<p>The Open-Closed Principle states that software entities such as modules, classes, functions, etc. should be open for extension, but closed for modification.</p>

<p>Let us understand the above definition in simple words. Here we need to understand two things. The first thing is <b>Open for Extension</b> and the second thing is <b>Closed for Modification</b>. The Open for Extension means we need to design the software modules/classes in such a way that the new responsibilities or functionalities should be added easily when new requirements come. On the other hand, Closed for Modification means we should not modify the class/module until we find some bugs.</p>

<p>The reason for this is, we have already developed a class/module and it has gone through the unit testing phase. So we should not have to change this as it affects the existing functionalities. In simple words, we can say that we should develop modules/classes in such a way that it should allow its behavior to be extended without altering its source code.</p>






