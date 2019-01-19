1.) What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

        Proptypes are basically rules placed on a prop that make sure the type of prop passed in is correct, 
        based on the type definition that was provided in the prop type. They help developers define what prop types
        a component needs, which makes it easier for other developers to understand what types of props the component
        is looking for if they are working with your code.

2.) Describe a life-cycle event in React?

        A React lifecycle event is just a method that you call on a component class or a component function. A good example
        would be componentDidMount, which you can use to load data into your component right at the beginning of its lifecycle.

3.) Explain the details of a Higher Order Component?

        When a component is passed into a function that then returns a new component, it's called a Higher Order Component.
        HOCs allow us to readily reuse logic in our code.

4.) What are three different ways to style components in React? Explain some of the benefits of each.

        The three different ways of styling in React are through the Reactstrap library, the styled components library, or just regular CSS.
        Reactstrap allows you to take advantage of pre-built components that are already styled for you, using Bootstrap. The biggest
        downfall to Reactstrap is that the components are difficult to re-style if you needed to change anything major on them.
        They styled components library allows you to write reusable styled components of CSS in JavaScript, so it's nice because you can do
        all of your styling in the JS file and not have to deal with extra CSS files. For me personally, this biggest downfall of
        styled components is that it makes my JS look  more cluttered. You can get around this by creating one styled components file and
        importing styled components as needed.
        CSS is nice because it allows all of the styling to be done separately. I don't honestly know if there are big pros or cons for CSS. I think it's
        sp close to using styled components it's probably just personal preference. 