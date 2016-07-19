# Redux Notes

- redux is a state container
- it is a collection of all the data that the app uses.

- react controls the views.

- Centralize all the apps data into a single object
  - that object is called 'state'
  - application level state is what is refered to in redux,m rather than component level
  


- a reducer5 is a function that returns a piece of the application state

- because the app can have many different pieces of state, we can have many diffferent reducers

- a container is a react componenet that has a direct connection 6to the state of redux.

- Containers are often called 'smart components' as opposed to 'dumb components'

- a dumb component has no direct connection to redux.

- the most parent component that needs a state shoudl be the container

- containers should only be components that care about a particular piece os state.

- only the most parent component that cares about that piece of state needs to be connected to redux.

- react-redux is the glue between react and redux
- they are all three, seperate libraries with little to do with eachother.

-connect  take s a function and a component, then produces a container, the container5 is a component that is aware of the state that is containeed by redux.

- the mapStateToProps function takes state as an argument, and returns an object, whatever object is returned will be available to the component as this.props.

- whenever application state changes, the container will instantly re-render with a new list of books.

- by using connect to create a container, whenever the app state changes, the object in the state function will be assigned as props to the components. 




