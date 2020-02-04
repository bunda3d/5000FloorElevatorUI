# 5000FloorElevatorUI
The 5000 Floor Elevator Controls User Interface: For an imagined 5,000-story building and its elevator controls UI/UX. 

<img src="e5kui\src\assets\img\launch\bunda3d5000FloorElevatorControlsFigmaPrototypeFirstScreen.png" width="800px" height="auto"> 

<img src="e5kui\src\assets\img\launch\bunda3d5000FloorElevatorControlsFigmaPrototypeLastScreen.png" width="800px" height="auto">

# Dev Plans
Eventually I plan to develop the prototype into reality using Angular (at least as the front end), and that's why I started this repo. 

# View Prototype (interactive)
I made a High-Fidelity (interactive) prototype in Figma, you can try it here: 
https://www.figma.com/proto/iczbAgh449JT7lhwDP8wkb/5000FloorElevatorUI.1?node-id=1%3A3&viewport=-5167%2C945%2C0.49883145093917847&scaling=contain 

Those of you with prototyping experience will understand a routing view like this. I could have incorporated the "Direct Entry" (keypad entry) navigation with the other navigation, but felt the animation transitions were getting complicated enough, and so I pulled those frames out (they're the 4 in the bottom row).  

<img src="e5kui\src\assets\img\launch\bunda3d5000FloorElevatorControlsFigmaPrototypeFileRouting.png" width="800px" height="auto">

Since it is a high-fidelity prototype with a lot of animated transitions, I've noticed it only works "smoothly" on my work PC with a high-end Radeon Pro card. It still works on mobile or other machines, but often VERY SLOWLY. Watch the videos, linked below, to see how it is designed to transition between.

# Discovering new considerations for model construction
Here's an idea of how I organized and named the the colors and font styling for easier eventual development styling and element building. 

<img src="e5kui\src\assets\img\launch\bunda3d5000FloorElevatorControlsFigmaPrototypeFileOrganization.png" width="800px" height="auto">

Also, you can get an idea of how I had to structure components and the tree order I chose to enable the cleanest, "smartest", most orderly transition animations. I learned a lot about Figma doing this very graphically-intensive prototype than from other website or traditional CRUD app mockups. Because of this, and for now, I'm liking Figma better than other prototyping platforms I've tried. Most of their rules make sense, even when you're very far down the rabbit hole on an edge use case.

# View Prototype file: 
To view the file (not the interactive prototype), click here: 
https://www.figma.com/file/iczbAgh449JT7lhwDP8wkb/5000FloorElevatorUI.1?node-id=52%3A20978 

<img src="e5kui\src\assets\img\launch\YouTube Thumbnail5000FloorElevatorControlsFigmaPrototype.png" width="800px" height="auto">

# Watch videos of the prototype on YouTube: 

Prototype file walkthrough and animation: https://youtu.be/eYP8sS7FDjM 

Shorter: https://youtu.be/pwAiDiq0su0 

# App Stub
After installing the new ng app (Angular 8), I saw I could enable the Ivy Rendering engine, which I think isn't fully supported until Angular 9. I wonder if it will make a difference on more graphics-intensive aplications like this UI? (right time, right place?)

<img src="e5kui\src\assets\img\launch\try_Ivy_rendering_in_angular_8.png" width="800px" height="auto">
