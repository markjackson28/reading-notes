# Class 01

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*Describe (in plain English) what Array.map() does*
- `array.map()` returns a new array with whatever function it is given.

*Describe (in plain English) what Array.reduce() does*
- `array.reduce` uses a reduce function(which is set by the dev) that performs a calculation. 

*Provide code snippets showing how to use superagent() to fetch data from a URL and log the result*

```
superagent.get('https://swapi.dev/api/people')
  .then( data => {
    console.log(data.body.results);
  })
```

*With normal Promise .then() syntax*

```
let evenNumCheck = (numArr) => {
  return new Promise( (resolve,reject) => {
    setTimeout( () => {
      if(numArr % 2 === 0) { 
        resolve('True'); 
        }
      else { 
        reject('False'); 
        }
    }, 1000);
  });
}

evenNumCheck(numArr)
  .then(status => console.log('status', status))
  .catch(err => console.error('error', err))

for( let i = 1; i < numArr.length; i++) {
  evenNumCheck(i)
    .then( result => console.log(i, result) )
    .catch( err => console.log(i, err) )
}
```

*Again with async / await syntax*
```
handleCreate = async (bookInfo) => {
  try {
    let response = await axios.post('http://localhost:3001/post-books', bookInfo);
    const newBook = response.data;
    this.setState({
      books: [...this.state.books, newBook]
    });
  } catch (err) {
    console.log(err);
  }
}
```

*Explain promises as though you were mentoring a Code 301 level student*
- A promise is a different version of an if/else statement. If a set function is ‘fulfilled’ then it will promise a result. If not fulfilled, it will give you an error. 

*Are all callback functions considered to be Asynchronous? Why or Why Not?*
- Yes because it has to be triggered/called. It is skipped until the function is invoked.

### Resources
- [MDN Web Docs](https://developer.mozilla.org/en-US/)
