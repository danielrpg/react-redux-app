# install react redux
- npm install reduxt --save-dev

## important methods to be aware in Redux 

- getState for reading the current state of the application
- dispatch for dispatching an action
- subscribe for listening to state changes

## To see the changes in the console please 
- yarn start
- store.getState();
// output: {articles: Array(0)}
- store.subscribe(() => console.log('Look ma, Redux!!'));
- store.dispatch( addArticle({ title: 'React Redux Tutorial for Beginners', id: 1 }) );
- store.getState();
// output: {articles: Array(1)}