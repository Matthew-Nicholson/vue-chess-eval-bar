## Chess Eval Bar

#### Live demo at [chess.mattnicholson.ca](https://chess.mattnicholson.ca/).

To install:  
```npm i vue-chess-evaluation-bar```

Then use it like any other vue component:  
```import EvalBar from 'vue-chess-evaluation-bar'```
##### Props:

`**width**: { type: String, default: "20px" }`  
`**height**: { type: String, default: "100%" }`  
`**rounded**: { type: Boolean, default: false }`  
`**numericEval**: { type: Boolean, default: false }`  
`**transitionDuration**: { type: String, default: "2s" }`  
`**whiteColor**: { type: String, default: "#F7F7FF" }`  
`**blackColor**: { type: String, default: "#131112" }`  
`**evalRange**: { type: [Number, String], default: 5 //ie. -5 shows all black and +5 shows all white eval.`  
`**evaluation**: { type: [Number, String], default: 0.0 }`