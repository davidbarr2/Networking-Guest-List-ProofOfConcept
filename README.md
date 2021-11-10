# Advanced State Management Sprint Challenge

### Technologies
React, Redux, Redux Thunk

### See Live
https://uyi2r.csb.app/

Filling Out Form
![Filling Out Form](https://user-images.githubusercontent.com/48306510/141159949-128037bc-db9a-465b-be30-a47c172f940c.png)

Added Entry
![Added Entry](https://user-images.githubusercontent.com/48306510/141159952-0f2f1bdd-361d-4969-a61a-553edd98e4fe.png)

### Project Requirements

### Notes for Future Developers

### Validation
Failed GET
![Failed GET](https://user-images.githubusercontent.com/48306510/141159932-65f18dd1-3260-4bd7-9602-4ec66ea923ec.png)

Invalid Form
![Invalid Form](https://user-images.githubusercontent.com/48306510/141159939-7fc16284-0877-42a8-a966-8d6e34eadacf.png)

### Testing

### Future Improvements
* Click guest name to hide details
* Reset form on submit
* Add new guest to top of list for user experience
* Leverage Yup for additional form validation

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
 
