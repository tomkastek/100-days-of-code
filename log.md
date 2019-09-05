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

### Day 15: August 01, Thursday

**Today's Progress**: After the grid is solved, all left items fall down. The board gets refilled and calculated again. This process continues until there is no row anymore.

**Thoughts** This was the last step of my first resolving version. I will start another side project now.

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)

### Day 16: August 02, Friday

**Today's Progress**: Startet a new project by converting my blog into an app.

**Thoughts** Was faster than expected. After three hours I had a first version I was really happy with. Now I need a lot of design optimizations, more post loadings etc. Probably will work further on a private repo.

**Link(s) to work**
1. [Blog to app repo](https://github.com/tomkastek/flutter_blog_to_app)

### Day 17: August 03, Saturday

**Today's Progress**: Added Hero animations to my "blog to app" project.  

**What I've learned**: Using Hero Animations (basics).

**Thoughts** It was so easy to implement and looks so great. I will definitly use them more often now.

**Link(s) to work**
1. Private Repository
2. [Hero Animations Docs](https://flutter.dev/docs/development/ui/animations/hero-animations)

### Day 18: August 04, Sunday

**Today's Progress**: Added a close hint to my "blog to app" project and played around with colors. 

**What I've learned**: AppBar is overriding the system behaviours for status bar brightness ... took way too long until I realized that.

**Thoughts** No big progress compared to the last days because I had too many problems with that appbar :D But thats okay.

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 19: August 05, Monday

**Today's Progress**: Only did some small UI changes on my blog project

**Thoughts** --

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 20: August 06, Tuesday

**Today's Progress**: Solving an html uncoding bug, integrated sqflite  to my blog project.

**Thoughts** sqflite is probably easier than I thought on first look. Have to try it out tomorrow

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 21: August 07, Wednesday

**Today's Progress**: Using sqflite to store posts locally and reload them on offline app start

**What I've learned**: Creating a table in sqflite, setting and updating data into it, loading in back.

**Thoughts** Forgot to commit changes on eob :( Basics of sqflite are totally understandable. Had some problems because I prepared the database for multiple blogs

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 22: August 08, Thursday

**Today's Progress**: Integrated flutter_bloc to handle post state. Added a first opening loading screen (after splash screen before showing table of content with loading bar)

**Thoughts** Happy that I am doing it now and not even later. I only need to think about states and changed one streambuilder to blocprovider. 

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 23: August 09, Friday

**Today's Progress**: Changed the sorting of articles (and reloading) by date instead of id. Changed ListView to SliverListView to add Pull to refresh

**What I've learned**: Basics of SliverLists

**Thoughts** Next step will be how to keep the scrolling position if new data is loaded and change the onRefresh callback to listen for a bloc callback. 

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 24: August 10, Saturday

**Today's Progress**: Needed to refactor my code because wordpress api is using local date instead of gmt/utc. for api calls. Also fixed that bloc is not yielding a new state if list of posts wasn't changing.

**What I've learned**: flutter_bloc not only needs a new state instance to rebuild. It also needs a newly created list by List.from() if a property is a list to rebuild.

**Thoughts** Still need to listen on the state change in my pull_to_refresh on_refresh function to hide the identicator.

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 25: August 11, Sunday

**Today's Progress**: Last step to bring my pull_to_refresh to work as expected. Added a fixed size to feature images so that they do not load after on fast scrolling. Did some changes to define code based on android or ios.

**What I've learned**: My math skills are a little rusty. Need to use a learning app again.

**Thoughts** Happy with my daily evening process although I was not 100% concentrated.

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 26: August 12, Monday

**Today's Progress**: I tried to keep scroll position if I load new posts (wip) so I added a ScrollController() for example.

**What I've learned**: ScrollController() can be used to easily keep scroll position if you laod new data at the end of the list but not if you load them in the beginning.

**Thoughts** Really struggling to get this one done.

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 27: August 13, Tuesday

**Today's Progress**: Shortly worked on my puzzle game again to fix a bug -> can play after one clear again. On my blog project: First solution to keep the scrollPosition on reload. It works but is not optimal

**Thoughts** I should write my thoughts about keeping the scroll position in a blog post. Really hard to get this one done.

**Link(s) to work**
1. [My puzzle_game repository](https://github.com/tomkastek/puzzle_game)
2. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 28: August 14, Wednesday

**Today's Progress**: Found a final solution how to rebuild my list with new posts loading on top.

**Thoughts** Still not happy because there is a small flash.

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 29: August 15, Thursday

**Today's Progress**: Implemented an endless scroll at the end of my list to load older posts all the time.

**Thoughts** It looks so much smoother than loading posts on top of the list :/ Flutter should support this behaviour.

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 30: August 17, Friday

**Today's Progress**: Started to create a login/register flow with firebase. Followed the flutter_bloc tutorial for this.

**What I've learned**: How to use firebase_auth in flutter

**Thoughts** -

**Link(s) to work**
1. [flutter_bloc Firebase Login Tutorial](https://felangel.github.io/bloc/#/flutterfirebaselogintutorial)
2. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 31: August 18, Sunday

**Today's Progress**: Added registration screen for firebase_auth.

**Thoughts** Still OAuth configuration missed

**Link(s) to work**
1. [flutter_bloc Firebase Login Tutorial](https://felangel.github.io/bloc/#/flutterfirebaselogintutorial)
2. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 32: August 19, Monday

**Today's Progress**: Added a tabbar and a ability to log out into my app.

**Thoughts** -

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 33: August 20, Tuesday

**Today's Progress**: Started to implement a onboarding into my app. Having a simple gridview showing gonly gaming category right now.

**Thoughts** I need to do more planning on how the onboarding should look like.

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 34: August 21, Wednesday

**Today's Progress**: Interviewed my friends to find a good name for my project. App Onboarding contains some categories with pictures from pixabay. On click the picture blurs with a checkmark on top and a next button appears. Deselecting all categories lets the button disappear.

**What I've learned**: How to create a blur effect.

**Thoughts** I hate the process of finding a good name for a project. But I have some good alternatives now.

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)
2. [Blur on StackOverflow](https://stackoverflow.com/questions/43550853/how-do-i-do-the-frosted-glass-effect-in-flutter)

### Day 35: August 22, Thursday

**Today's Progress**: Implemented my first animation into the blog project. Needs some refactoring now.

**Thoughts** I miss swift enums :(

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 36: August 23, Friday

**Today's Progress**: Somme refactoring, added another Animation on a button. Changed project name (no final decision yet)

**Thoughts** Deciding for a project name is still the hardest decision I can do.

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 37: August 24, Saturday

**Today's Progress**: No Internet today, added another animation

**Thoughts** Plan was to search some blogs to create a testing area. Complicated without internet.

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 38: August 25, Sunday

**Today's Progress**: Prepared a first page for the next onboarding page (recommended blogs) and refactoring a small piece of animation code.

**Thoughts** No big progress today. 

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 39: August 26, Monday

**Today's Progress**: A lot of refactoring and implemented a new bloc for the onboarding progress.

**Thoughts** Refactoring is important, was a good day.

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 40: August 27, Tuesday

**Today's Progress**: Again some refactoring. I was not coding a lot. Was searchin about 3 hours for possible company names. Still no final decision.

**Thoughts** -

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 41: August 28, Wednesday

**Today's Progress**: Finally more functionality. I created a connection to Firestore to load recommended blogs depending on onboarding category selection.

**Thoughts** I need to do a course to learn Firestore best practices. 

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 42: August 29, Thursday

**Today's Progress**: Nearly finished second page on onboarding. After recommended blogs are loaded, they are animating in like the first onboarding page and you can also select now blogs on this page.

**Thoughts** Next step is to save those blogs as followed on Firestore and load the home page after. I need to take a course for this because I have to less experience in Firestore.

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 43: August 30, Friday

**Today's Progress**: For testability I added a function to my auth bloc to get back on the main page even without firebase interaction. I was thinking what solution I should use so that I do not depend on slow wordpress api (RSS? Own plugin?) and had a first look into Firebase CLoud Functions.

**Thoughts** I start thinking that 100 days of code stops me in my progress as I am changing from a process of coding only to a lot of planning. Planning what solutions I shall use in my project, planning how I will gain customers and what their best value from this app will be.

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Day 44: August 31, Saturday

**Today's Progress**: Added more tabs to my bottom tabbar. Also Added a top tabbar on my "Home"-Page and NotificationsPage.

**Thoughts** I need to rethink my UX into a direction I want my platform to be like my vision of it.

**Link(s) to work**
1. [Private Repository](https://github.com/tomkastek/blog_to_app)

### Why I quit 100 days of code

I was not posting any updates on GitHub for 3 days now. And it makes me feel free. I love this challenge. Before I started 100 Days of Code I was a person who was mainly gaming in the evening. Now I take the evening to do something "useful". I started by learning stuff in Flutter I wanted to learn for months. I copied a playstyle of my favorite game I wanted to copy since months. This challenge motivated me. After about a month I had the feeling that I want to create something that I can maybe upload onto the App/ Play Store. I got so much into it that I was not doing anything else. But as I want to use this project to test even more of starting your own business I need time to do something else as well. I only have about 2 hours every evening I can spend on this project. If I completely spend it into programming I have no time anymore to spend it into other stuff around it. For example, I used about three evenings just to find a name for my project. I still made no decision. Two of those evenings I was coding only small stuff like code refactoring or writing comments so that I do not use my brain a lot. And this is bad. I should have done no code and concentrate on what's important for me: Finding this name. And this is only one example for which I need time to do something else. 

**What I learned**: As I said, this challenge was so important to me. I learned to find motivation for myself to do something every evening. I learned to not come home and say "Oh, I worked the day in the office, now I need to calm down and play video games until I sleep". This was so important to me and I felt so good for the last two months. I was happy about my progress, happy that I did just anything. So I continue the "100 Days of" challenge myself. But it is not "100 Days of Code" anymore. It is "Do something to publish a successful app every day". Maybe I will start a blog about it because it was interesting for me to hear from other startups and their process in the beginning.

P.S. Probably I will use the upcoming 1-2 weeks only to structure my app etc.