

<h4>Single-responsiblity Principle</h4>

<p>The Single Responsibility Principle (SRP) is one of five design principles of the SOLID design framework for object-oriented software design. The SRP dictates that classes should have only a single reason to change. Multiple reasons for change indicate more tightly-coupled designs that are more rigid and harder to maintain.</p>

<p>We don’t want objects that know too much and have unrelated behavior. These classes are harder to maintain. For example, if we have a class that we change a lot, and for different reasons, then this class should be broken down into more classes, each handling a single concern. Surely, if an error occurs, it will be easier to find.</p>

<h4>God Object</h4>
<p>God Object - Object that know too much and or do too much, it is basically a class with lots of responsibilities and spaghetti code. It is an anti pattern of Single Responsibility Principle</p>