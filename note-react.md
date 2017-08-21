- Redux: 
  - data(state) container in the application 
  - contralize all data in the application, different from Flux, AngularJS
  - critical in designing state
  
- React: view container in the applicaton
- react-redux library to connect react & redux libraries
- Container: a React component that has direct access to state produced by Redux

- Reducer: a function that returns a piece of application state
- Different reducers to returns different pieces of application state



return this.props.books.map( (book) => {
      return (
        <li key={book.title} className="list-group-item">{book.title}</li>
      );
});

// don't forget to assign key for each item in a list when conducing some functions



// BookList, BookDetail: smart components or containers: have connection to redux
// App: dumb components: no access to data
