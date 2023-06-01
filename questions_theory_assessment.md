# CFGDEGREE

### Section 1: Theory Questions 

1. Designing system to align with users exceptation, thoughts about the expected product derived from their expeirences in real, especially system behavior, interactions consistent and intuitive for users. 
The advantages: Error prevention, user satisfaction (user feel comfortable, confident, easy to use/interact and does not take too much effort when using the system and ), 

2. Purpose of "single source of truth" is particular piece of information is stored and maintained in single, safe and stable source as much as possible. 
Connection with redux is javscript object store from central store. 
The advantages: 
- Predictability (easy to understand and predict how the state changes in application. App state should be well organized and traceable)
- Debugging  (redux provide built-in support for time-travel debugging)
- Easy intagration (can intagrate lots of framworks and libraries, like react)

3. Main difference between them is based on how they handle and manage data.
- Stateless/functional component
JavaScript functions and do not have their own internal state. They focus on presenting the UI and don't track or manage any data over time. it is generally iput props they receive and return a rendered output.
- Stateful component
It has own internal state and is responsible for managing and updating that state over time. They extend the React.Component class. Stateful components are used when you need to maintain and update data within the component.

4.Exploratory Testing:

The advantages:

-Flexibility allows us to adapt and respond quickly to changes in requirements and project dynamics. Testers easily explore the software system, uncovering unexpected issues and gaining a deeper understanding of its behavior.

-Early Bug Detection

-User Perspective: It focuses on the end-user perspective, enabling testers to evaluate software from a user's point of view. It helps uncover user experience problems, and inconsistencies in the application's behavior.

The disadvantages:

-Lack of Documentation

-Time and Resource Intensiveis sometimes time consuming and resource intensive.

-Incomplete Coverage: Due to its unscripted nature, there is a risk of overlooking certain test scenarios or failing to cover all possible combinations. The coverage may be subjective and dependent on the tester's knowledge and experience.


Scripted Testing:

The advantages:

-Reproducibility (It makes easier to reproduce issues and verify fixes)
-Ensures consistency (It helps in comparing results, tracking progress, and identifying regressions)
-Scalable for large projects
-Provides documentation

The disadvantages:

-Limited flexibility (It may miss out on exploring potential defects that can be discovered through more dynamic approaches)
-Maintenance overhead ( for large number of test script can be time consuming)
-May lack user perspective
-Late bug detection (it could make a result in rework and delays)
