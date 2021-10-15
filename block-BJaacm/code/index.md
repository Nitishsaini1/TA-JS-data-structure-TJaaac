```js
let user = {
  name: 'Arya',
  sibling: ['Robb', 'Ryan', 'John'],
};
let allBrothers = ['Robb', 'Ryan', 'John'];
let brothersCopy = user.sibling; //true
let usename = user.name; //true
let newUser = user; //true
```

1. Memory representation

- Create the memory representation of the above snippet on notebook.
- Take a photo/screenshot and add it to the folder `code`

<!-- To add this image here use ![name](./hello.jpg) -->

2. Answer the following with reason:

- `user == newUser;` // true because both are from same refrence
- `user === newUser;` //  true because both are from same refrence
- `user.name === newUser.name;` // true because both are from same address
- `user.name == newUser.name;` //  true because both are from same address
- `user.sibling == newUser.sibling;`//true because both are from same address
- `user.sibling === newUser.sibling;` //true because both are from same address
- `user.sibling == allBrothers;` //true because both are not from same address
- `user.sibling === allBrothers;`//true because both are not from same address
- `brothersCopy === allBrothers;`//true because both are not from same address
- `brothersCopy == allBrothers;`//true because both are not from same address
- `brothersCopy == user.sibling;`//true because both are from same address
- `brothersCopy === user.sibling;` //true because both are from same address
- `brothersCopy[0] === user.sibling[0];` //true both hve same value
- `brothersCopy[1] === user.sibling[1];`//true both hve same value
- `user.sibling[1] === newUser.sibling[1];`//true both hve same value
