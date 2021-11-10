# Advanced State Management Sprint Challenge

### Technologies
React, Redux, Redux Thunk

### See Live

### Project Requirements

### Notes for Future Developers

### Validation

### Testing

### Future Improvements
* Click guest name to hide details
* Reset form on submit
* Add new guest to top of list for user experience

## API documentation 

* **[GET]** to `http://localhost:3333/smurfs`: returns the list of all smurfs objects.
* **[POST]** to `http://localhost:3333/smurfs`: creates a new smurf object. Pass smurf data through the `body` of the request.

* **Smurf Object Structure** 
```js
[
  {
    id:"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9",
    name:'Poppa Smurf',
    position:'Village Leader',
    nickname: 'Pops',
    description: 'Papa is the practical village leader and the father figure of 100 or so young Smurfs. He is easily identified by his red Smurf hat, pants, and a shortly-trimmed white beard and moustache.'
  }
];
```
 
