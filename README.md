# Tic Tac Toe
In the project directory, you can run:
```sh
$ npm start
```

## Notes
*  In JavaScript classes, you need to always call super when defining the constructor of a subclass.
* All React component classes that have a constructor should start it with a super(props) call.
* To collect data from multiple children, or to have two child components communicate with each other, you need to declare the shared state in their parent component instead.
* In React, however, it is a convention to use on[Event] names for props which represent events and handle[Event] for the methods which handle the events.

### The Component Lifecycle
#### Mounting
* constructor()
* render()
* componentDidMount()
#### Updating
* render()
* componentDidUpdate()
#### Unmounting
* componentWillUnmount()
