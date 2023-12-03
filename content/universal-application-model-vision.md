# Universal Application Model

### Where does this idea come from?
For more than 4 decades now, I am developing software. And strangely enough I have the impression that I've been doing the same thing for most of the time. Most of my work had to do with applications that ... . The last 2 decades I worked for a company that creates software for banks. 

Technology has changed a lot during my career. I started in a time that client/server was something new. The PC was... There were no handhelds or tablets. Internet didn't exist. Remote communciations were over a beeping modem and the active memory of my PC was 512 kB. (Yes, kilo not mega or tera bytes)

But the programs already resembled . I created forms to . I started with . I've used Oracle, 
In those days . 
I started with dBase III on my father's PC. After that there was later from Ashton-Tate, Microsoft Access
I learned Visual Basic (6.0) and SQL Server to create real client/server programs. Then I moved to a company which also used Oracle and started to use that. Oracle had his own . I made some ... to the and worked with PowerBuilder . I remember
Then .NET came along and Microsoft 

All-in-all a lot of new technologies and new things to learn. But on closer inspection everything we build resembled. ... it were applications to view and manipulate data stored in a database with a set of forms. Those forms were , but if . I need a form to display a list of items that satisfy a set of search criteria and I want to be able to modify the items using a form This form sho

Oh, isn't it magic, abstaction. Remove See a primitive thing as a 
... that it can describe a flashy modern app on my iPhone the same way a primitive dbBase program the s

## Vision

There are a lot of [application frameworks](https://www.techopedia.com/definition/6005/application-framework) for different environments. However, when we make abstraction of implementation details, we find that most of them share common features and concepts. The model that comprises and structures these shared concepts, is what I coin as the ***<span class="concept-intro">Universal Application Model</span>***. This model serves as the domain model for data-driven application development. It provides a formal representation of the concepts that developers use to create such applications. This application model should not be confused with the domain model of specific application being developed, although it does build upon it.

One could say that we are talking here about domain-driven development with a dual domain: the data domain targeted by the application and the application domain. If we take the example of a bank, the former would include concepts like bank account and customer and the latter form, pages and menus.