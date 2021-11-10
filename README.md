# Advanced State Management Sprint Challenge

### Technologies
React, Redux, Redux Thunk

### See Live
https://uyi2r.csb.app/

Filling Out Form
![Filling Out Form](https://user-images.githubusercontent.com/48306510/141159949-128037bc-db9a-465b-be30-a47c172f940c.png)



Added Entry
![Added Entry](https://user-images.githubusercontent.com/48306510/141159952-0f2f1bdd-361d-4969-a61a-553edd98e4fe.png)


Failed GET
![Failed GET](https://user-images.githubusercontent.com/48306510/141159932-65f18dd1-3260-4bd7-9602-4ec66ea923ec.png)


Invalid Form
![Invalid Form](https://user-images.githubusercontent.com/48306510/141159939-7fc16284-0877-42a8-a966-8d6e34eadacf.png)

### Project Requirements
* Display list of guests
* Have form to add guest and have it rendered in the guest list
* Validate that all name, position, and nickname are filled in
* Leverage Redux for state management

### Future Improvements
* Click guest name to hide details
* Reset form on submit
* Add new guest to top of list for user experience
* Leverage Yup for additional form validation

### Notes for Future Developers
For this Proof of Concept, a mock server is used rather than a live API.
* **[GET]** to `http://localhost:3333/guests`: returns the list of all guest objects.
* **[POST]** to `http://localhost:3333/guests`: creates a new guest object. Pass guest data through the `body` of the request.

* **Guest Object Structure** 
```js
[
  {
    id:"JzdWIiOiIxMjM0NTY3ODkwIiwibmFtZ",
    name:'Donna Clark',
    position:'Senior VP of Engineering at Cardiff Electric',
    nickname: 'Matriarch of Mutiny',
    description: 'Donna wears many hats as investor, hardware engineer, software engineer, and executive. She is motivated by the desire to create the future.'
  }
];
```


 
