
# Class 04

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

[React Docs - Forms](https://reactjs.org/docs/forms.html)

*What is a ‘Controlled Component’?*

- A controlled component is basically a HTML form element used in React. When an input form element is in place, React controls the value. This is a way to use a form in React.

*Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.*

- I think we should wait because updating the state constantly will be inefficient.

*How do we target what the user is entering if we have an event handler on an input field?*

- The ```value``` attribute.

[The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

*Why would we use a ternary operator?*

To shorten an  ```if``` ```else``` statement.

```
condition ? value if true : value if false
```

*Rewrite the following statement using a ternary statement:*

```
  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
```

```
x===y ? console.log(true) : console.log(false);
```

## Things I want to know more about
