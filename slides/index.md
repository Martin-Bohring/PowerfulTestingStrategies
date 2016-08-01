- title : Powerful testing strategies
- description : Powerful testing strategies by using powerful tools
- author : Martin Bohring
- theme : night
- transition : default

***
- data-background: images/Blackboard.jpg

### Powerful testing strategies

- Testing software is still a challenge
- Automatic testing even more so
- How can we be confident about the quality of our software?
- How can we ensure the long time quality of software?
- There are different views on testing with different goals
- There are different approaches to testing
- There are lots of tools for testing

***

- data-background: images/Blackboard.jpg

### There are different views on testing

- The developers view on testing
- The testers view on testing
- Standards view on testing (ISO IEC 90003)
- Agile view on testing
- Modern view on testing

***

- data-background: images/Blackboard.jpg

### Standards views on testing

Software development standards have a clear but simple view on testing.

Lets define test types depending on the scope of the SUT (system under test)

- Unit tests
- Integration tests
- System tests
- Acceptance tests

We need to delve a little bit into those definitions.

***

- data-background: images/Blackboard.jpg

### What are unit tests then?

- Unit tests obviously test units of software
- But what is a unit of software?
- Everybody knows the units of mass (ton, kg, etc.)
- but nobody has an exact definition of a software unit

***

- data-background: images/Blackboard.jpg

### Definition from IEC 90003 2004

> Unit tests are stand alone tests of software components.

Well, that is really helpful, isn't it?
Lets define software units in terms of another definition (components)

So it is up to you to define what software units are for your project.

***

- data-background: images/Blackboard.jpg

### So what are integration tests then?

- They test the integration, stupid
- But what does that mean?
- Integration of what?
- What do the experts say?

***

- data-background: images/Blackboard.jpg

### Definition from IEC 90003 2004

> Integration tests examine aggregations of individual software features and components
> in order to determine whether a new feature or component works with
> (or integrates with) existing features and components.

*Integration tests* are used to prove that all software features and components work together.

So they test the integration of software units, but we still need to define what a unit of software is.

***

- data-background: images/Blackboard.jpg

### What is powerful

- Easy to write
- Easy to run
- As close to the production environment as possible
- As close to the business point of view (end user view) as possible