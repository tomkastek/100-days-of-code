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

### Day 3: July 19, Friday

**Today's Progress**: Implemented the bloc pattern into my puzzle game project. Initialized a random state instead of a static one

**What I've learned**:
- How to use Random class in Flutter

**Thoughts** I still struggle in figuring out what code needs to be in my bloc and what kind of code needs to be contained in my state. I think I have to do some tutorials next.

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)

### Day 4: July 20, Saturday

**Today's Progress**: Implemented tired in the night. Tried to add a Draggable to my gaming app -didn't worked

**Thoughts** Combination of grid cell states with interchangeable object on them is not that easy for me. 

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)

### Day 5: July 21, Sunday

**Today's Progress**: Items for puzzle game are draggable. Extended the GridBloc on the game to include a dragging event and state.

**What I've learned**:
- Draggables child, feedback and childWhenDragging
- How to place Draggables feedback

**Thoughts** I was way to tired yesterday. More success on my plans today. I should not forget to further study the bloc tutorials. 

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)

### Day 6: July 22, Monday

**Today's Progress**: The draggable items in my puzzle game can be now changed (Worked with DragTargets, added a new event to Bloc)

**Thoughts** Nothing special today, just lost time because I was to dumb to realise I changed an x with y Position at some point.

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)

### Day 7: July 23, Tuesday

**Today's Progress**:  My puzzle game has a first working puzzle mechanic.

**Thoughts** Still not sure how to handle faster user interaction than bloc building. But it was fun to try some workarounds. Happy with my first version :) 

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)

### Day 8: July 24, Wednesday

**Today's Progress**:  Only refactored my puzzle game.

**Thoughts** I need to find out if its better to get the bloc state and pass the state to underlying widget or if I should build a blockbuilder in ever subtree.

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)

### Day 9: July 25, Thursday

**Today's Progress**:  More refactoring and a frist test on my puzzle game.

**Thoughts** -

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)

### Day 10: July 26, Friday

**Today's Progress**: I changed a string representation to a object one, fixed a bug because of draggable and startet a branch to resolve my puzzled board.

**Thoughts** -

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)

### Day 11: July 27, Saturday

**Today's Progress**: Added a grid model to my puzzle game, started to think about resolving of the puzzle

**Thoughts** -

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)

### Day 12: July 29, Monday

**Today's Progress**: Resolving my puzzle board as a first version.

**What I've learned**: List are not directly compareable. I need to check this one as my grid is a List.

**Thoughts** Missed a day: feeling bad now :( but I finalized the first resolving version of my puzzle board. Still a lot of optimization, animations will follow after.

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)

### Day 13: July 30, Tuesday

**Today's Progress**: My puzzle is solving without delay. Did refactoring for code reduction and extracting a custom Point object.

**Thoughts** The plan to let fall down my items and spawn new ones after will be later. First I need a better solving of my puzzle. The goal is to not only solve in one direction but crosses and boxes also.

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)

### Day 14: July 31, Wednesday

**Today's Progress**: Last step to resolve all possible combinations I can think of right now in my puzzle game.

**Thoughts** It was an interesting challenge to think in all possible directions. Next I need to refill the board.

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)