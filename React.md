# React Js
-----

- React Js is an JavaScript Library for Front-end devlopement and 
  It is used for component builliding .
	Note :- In React The main Key feature is the Component based UI buillding . Hence we are reusing the componet and using the what 
		  exactly we required .
 -Basic Exmple of Js :- 
	` const element = <h1> Hello World </h1> `
- DOM :- Document Object Manupaletion 
- ReactDOM.render() :- is used to render the html elements in display .
example :- 
	
```js 
	<div id="id01">Hello World!</div>

	<script type="text/babel">
	ReactDOM.render(
    <h1>Hello React!</h1>,
    document.getElementById('id01')

``` 

- React elements are **Immutable**.
- The only way to change the react elements is the every time we have to create the 
  new element .
- The React componets are know as Javascript Functions.

 ```js 
 
	//Example :- 
	<div id="root"></div>
	
	function welcome (){
		return <h1> Hello World ! </h1>

	}
	ReactDOM.render(<welcome />, document.getElementById('root')) 
	
``` 
	
- React Componts and Properties.
```js 
	function hello(props){
		return <h1> Hello {props.name} </h1>

	}
	ReactDOM.render(</hello name = "Rushikesh Gaikwad">, deocument.getElementById('root')
```
- Creating React Application .
```sh
 $ npx create-react-app my-app 
	It Creates the react app for you.
 $ npm start 
 	Start the server.
 $ npm test 
 	Strarts the test runner.
 $ npm run eject 
 	Coppies the tool Dependancies and removes the tool.
 $ npm build 
	It builds the Project.

```

