# PPP.nvim

> 🚧 It is under development. 🚧

## TODO

- [ ] find nearest comments, starts with func
``` typescript
// func {identifier}
// comments about the function
```
- [ ] request to codegemma
    - [ ] insert response under the comment
``` typescript
// func {identifier}
// comments about the function

function {identifier} () {
  return;
};
```
- [ ] generate RAG of the project
``` markdown
Code conventions
...
Function
arrow function expression is recommended
```
``` typescript
// func {identifier}
// comments about the function

const {identifier} = () => {
  return;
};
```
