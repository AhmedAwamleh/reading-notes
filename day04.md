## What is a ‘Controlled Component’?
A controlled component is a component that renders form elements and controls them by keeping the form data in the component's state. In a controlled component, the form element's data is handled by the React component (not DOM) and kept in the component's state.

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? 
Why.
we should update the state with the user's responce when they submit the form to prevent our react app from crashing because otherwise the app will re-render with each input

## How do we target what the user is entering if we have an event handler on an input field?

this.setState({value: event.target.value} inside the event handler this.state.value for targeting current value

## Why would we use a ternary operator?
to Shorten the condition into one line of code with the conditional operator

## Rewrite the following statement using a ternary statement:
```
     x===y ? console.log(true) : console.log(false)
```

## Bookmark and Review
- [React Bootstrap - Forms](https://react-bootstrap.github.io/forms/overview/)
- [React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)

## Things I want to know more about
about react dom
