# About this project
This project gives a comprehensive while remains simple example on Redux. 
The state will be changed when a book is selected from a list of predefined books.


To dispatch an action in component, you need to first bind an action creator(on the right) to a React `props`(on the left). Finally you also need to use the `connect()`.
```
function mapDispatchtoProps(dispatch){
  return bindActionCreators({selectBook: selectBook},dispatch);
}
```
so that you can use it like this
```
this.props.selectBook(book)
```

# Available Scripts
```
npm install
npm start
```
