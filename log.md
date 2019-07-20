# 100 Days Of Code - Log

### Day 1: July 17, Wednesday

**Today's Progress**: Worked in bloc [tutorial](https://felangel.github.io/bloc/#/gettingstarted) until implementing first example.

**What I've learned**:
- Bloc needs an event and a state
- I have to define a initialState in flutter_bloc
- I have to override mapEventToState which takes an event and returns a state depending on it

**Thoughts** Easy to use in a first place. I know there is more complicated stuff but the tutorial is awesome. Also I want to learn to use the CupertinoAppBar correctly (or app bar in the bottom instead of top in general) and keep the floating button on the screen while animating between them (work for a long time later not the next days)

**Link(s) to work**
1. [Flutter Counter Tutorial](https://felangel.github.io/bloc/#/fluttercountertutorial)
2. [My repository](https://github.com/tomkastek/BLoC_tutorials_felangel)

### Day 2: July 18, Thursday

**Today's Progress**: Did the second example of flutter_bloc. Implemented a timer app for that

**What I've learned**:
- It is nice to define the state and event of blocs in additional classes.
- for each state in mapEventToState I can define a additional function that I return for readability
- how to use StreamSubscription for Streams
- condition for BlocBuilder is awesome <3

**Thoughts** I want to learn how I can animate my view depending on the state change. In the timer app for example animate two buttons moving together to one (and also one is splitting into two etc)

**Link(s) to work**
1. [Flutter Timer Tutorial](https://felangel.github.io/bloc/#/fluttercountertutorial)
2. [My repository](https://github.com/tomkastek/BLoC_tutorials_felangel)

### Day 3: July 19, Thursday

**Today's Progress**: Implemented the bloc pattern into my puzzle game project. Initialized a random state instead of a static one

**What I've learned**:
- How to use Random class in Flutter

**Thoughts** I still struggle in figuring out what code needs to be in my bloc and what kind of code needs to be contained in my state. I think I have to do some tutorials next.

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)

### Day 4: July 20, Friday

**Today's Progress**: Implemented tired in the night. Tried to add a Draggable to my gaming app -didn't worked

**Thoughts** Combination of grid cell states with interchangeable object on them is not that easy for me. 

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)