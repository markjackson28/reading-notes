
# Class 09

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

[Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

What is functional programming?

- ‘Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — Wikipedia'

What is a pure function and how do we know if something is a pure function?

- A function that ‘returns the same result if given the same arguments (it is also referred as ```deterministic```)’. ‘	It does not cause any observable side effects’

What are the benefits of a pure function?

- Easier to test and debug.

What is immutability?

- Something that is unable to change after creation.

What is Referential transparency?

- ‘A function that consistently yields the same result for the same input.’

[Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

What is a module?

- A module is a block of code that usually contains a specific function within a bigger block of code.

What does the word ‘require’ do?

- Allows you to run the module wherever you are; like another file.

How do we bring another module into the file the we are working in?

- ```require(‘./<filename>’);```

What do we have to do to make a module available?

- Add ```module.exports = <module/functionName>``` to the file where the module lives.

- Then on the destination file for the module, set your ```require``` to a variable.

- ```let <module/functionNameFrommodule.exports> =  require(‘./<filename>’);```

## Things I want to know more about

 - Pure functions
