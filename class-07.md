# Class 7 Reading Notes

## Why These Topics Matter

These topics matter because they will make our code easier to read. They also cut the time in just using prototypes instead of creating individual objects.

### Explain why we need domain modeling

A domain model can validate the understanding of a specific problem. It is a communication tool, that defines a vocabulary and can be used within and between both technical and business teams. Not only does domain modeling ease communication it provides flexibility.

### Why should tables not be used for page layouts?

- Tables reduce accessibility for visually impaired users
- Tables produce tag soup
- Tables are not automatically responsive

### List and describe 3 different semantic HTML elements used in an HTML < table>.

- < td>: table cell, the smallest container inside a table
- < tr>: stop rows from growing and start placing subsequent cells on a second row
- < th>: creates a header
- < col>: styles the columns

### What is a constructor and what are some advantages to using it?

A constructor is a function that creates an instance of a class which is typically called an “object”. A advantage of using a constructor is it can create multiple similar objects with the same properties and methods.

### How does the term this differ when used in an object literal versus when used in a constructor?

The difference of this in object literal versus constructor is you have to bind this to the new object, so you can refer this in your constructor.

### Explain prototypes and inheritance via an analogy from your previous work experience.

A prototype is an object that is associated with every functions and objects by default in JavaScript. Instead of creating separate objects to manage methods, we just put each methods in a funtions prototype. A example of this from my previous work experience would be using supply and demand in GCSS(our Army online vehicle profiles). Each vehicle needs a special kit when being serviced and we can order each one per vehicle like seperated objects. Or I can use supply and demand method which would act like my prototype. Supply and demand allows me to have a kit automatically ordered when a service in a vehicle is complete online, since it knows we just expended a kit on the service conducted.

### Sources

- [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)
- [HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
- [Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)
- [Object Prototypes Using A Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)

### Things I want to know more about