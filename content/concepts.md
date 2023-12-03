An application consists of pages.

A page is the target of an URL.

A page can be navigated to.

A device has a particular display.

A viewport is a part of the display showing a page or part of it.

A page representation is often composed of parts that represent its context - like a header, a footer and side panes - and the representation of the actual page data.

A page consists of 

The same page can 

A page has a type, often related to the class of data it

(*What is the difference between a domain model and an entity model? The entity model represents that part of the domain model that is implemented by the application.*)

In UML terminology, a page is a classifier and like any classifier it can have instances. For example EditClient could be a page to display and modify the data of a particular Client, where Client is a class from the entity model. During run-time we can have one or more instances of the EditClient page, manipulating different instances of the Client class (or even of the same Client instance.)

This is an illustration of the dual domain. The Client class belongs to the data domain targeted by appliction, while the EditClient page class belongs to the application domain. It also illustrates the fact that the latter builds onto the former. Many properties of the EditClient class will depend on properties of the Client class. For instance, the types of the Client class's attributes will determine what type of widgets are appropriate on the EditClient page. To edit an eventual DateOfBirth attribute, we'll need a Date widget, while for the FirstName of LastName attributes, a Text widget is appropriate.

A lot more application features can be associated with the elements of the entity model. In this way they don't have to be specified by elements of the application model. For instance, business rules associated with the entity model elements, can be used as definitions for application features. For example, "Client.DateOfBirth <= Today" can be used as the definition of a validation rule on the corresponding widget on the EditClient page.

(It should be possible to create an algorithm to translate business rules of the form "field operator value" into proper validation messages in all languages supported by the application.)

### Device-independence
It is a good idea to make the distinction between a page and its representation. In this way the same page can have different representation for different environments. Examples of environments are devices and screen formats. (*ToDo: elaborate on responsive design*) Only a few features of a page representation are dependent on the environment and can most of the time be handled by the framework. The layout of the form being an important exception. (*ToDo: elaborate on the advantabe of automatic layouts*)


