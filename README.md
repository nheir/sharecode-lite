# sharecode-lite
Share code with WebRTC

The app uses WebRTC to implement a master-students code sharing interface. Only one user can write, using a token controlled by the master.

The master broadcasts the code to all students and may give the token to a student. In this case, the student sends the code to the master who relays it to all students.

## Requirement

 * [Codemirror](https://codemirror.net/) with `addon/selection/active-line.js` and `mode/meta.js`
 * [PeerJS](https://peerjs.com/)

## Minimal structure
```
├── codemirror
│   ├── addon
│   │   └── selection
│   │       └── active-line.js
│   ├── lib
│   │   ├── codemirror.css
│   │   └── codemirror.js
│   └── mode
│       └── meta.js
├── index.html
└── peerjs.min.js
```
