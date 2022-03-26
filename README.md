# react

| npm | install | -g | create-react-app |  
| :---: | :---: | :---: | :---: |  
| runs npm | install a package | install this package globally so that we can run it from the terminal | name of the package we want to install |  

whenever we create a new react app it comes with *Babel*, *Webpack*, *DevServer*.  

### Component
A component is a function or class that produces HTML to show the user(*using JSX*) and handles feedback from the user(*Using Event Handlers*)

### JSX 
```jsx 
<div>Amaterasu</div>
```
Babel converts this JSX to react/javascript code
```javascript
React.createElement("div", null, "Amaterasu");
```
JSX is a special dialect of JS(its not HTML)  
Browsers don't understand JSX Code! We write JSX then run tools(*Babel*) to turn it into normal JS  
