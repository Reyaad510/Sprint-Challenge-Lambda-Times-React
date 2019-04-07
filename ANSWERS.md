

 1. What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

PropTypes are used to check to make sure that the props we are passing down from the state to other components are the correct types of JS types. For example if we are passing down an array as a prop we would use proptypes to check to inform the developer that an array is being passed down and not a string, object, boolean, function, number, etc. It is important because we may not receive an error from React itself and we may run into a problem that will take a much longer time to figure out unless we used PropTypes.



2. Describe a life-cycle event in React?

An example of a life-cycle event in React would be componentDidMount() which is a method that runs after the component output has been rendered to the DOM. You use this if you need to load data froma remote endpoint.




3. Explain the details of a Higher Order Component?

A HOC is a function that takes a component and returns a new component. It creates DRY code because you can have multiple components that may have the same implementation and this will allow the developer to not have to retype redundant code over and over. It is also used for Login pages by either showing the user the Log In page if they are not logged in yet or if they are logged in to show them the user profile.




4. What are three different ways to style components in React? Explain some of the benefits of each.

One way is to use styled-components which allows the developer to utilize CSS right into their Javascript in the component it is being used for. You import it the the particular component you want to use it for and then start typing the css away using a particular syntax described in the docs. It is great because can promote DRY code by allowing reusability by using a styled component and passing props down to it creating a totally new component without the redundant typing of an entirely new component.

Second way is to import a libray such as bootstrap, material UI, etc. It has predesigned buttons, carousels, etc so not much coding is needed to do. It saves alot of time and is extremely helpful if just wanting to get a general idea of how a developer wants their site to look. A bad thing is that the developer is limited by restrictions of libraries templates.

Third was is to manually do your own CSS and use any preprocessers that you'd like. This allows unlimited possibilites for the designer to do whatever they want with styling and creates organized CSS or preprocessor folder fr whatever component they are designing.


