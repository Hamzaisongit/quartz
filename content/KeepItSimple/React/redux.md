- a state management framework.. used when app size grows and complexity/unpredictability of states of component increases 
- not limited to react only
- main lingo terms : state, store, action, actionGenFunc, reducer, dispatch, ..
- state : data(str,obj,number,array..)
- store : a particular ref variable through which everything will manifest
- action : an object with different info abt an action like type, payload
- actionGenFunc : a function returning an action obj to be called while dispatching
- reducer : a centeral function associated with store creation that will handle different action scenarios and chnage state accordingly
- dispatch methode: the process of calling an action
- other imp concepts :
	- adding listeners to a redux : subscribe
	- combining multiple reducers : combineReducers & rootReducer
	- handling asynch js with redux : applyMiddleWare & Thunk

## React-redux
- Two main things to make this redux store thing work as an API end point for the React-App..: Provider and connect
- Provider : a Wrapper object with a prop store = {storeName}.. it will be wrapping the main App component and thereby providing redux store access to all it's child components
- connect : used to connect Presentational component to react 