# Top Down Template
###### For UPBGE 0.2.3
This template was created to help Blender Game Engine (UPBGE) users to create games or any kind of interactive thing that request a Top Down Controller. Easy to use, easy to attach to your project.

To use, just download the files, open it on UPBGE (version 0.2.3 recommended) and you're done!
You can use this template in your projects, even for commercial projects. Just credit me for this.:)
It's very easy to use in your projects: Just load this script into your .blend file (or paste them in the same folder that your .blend is), select the object that you want, and attach the script into the object's components.

## Camera Drag Component
This component will allow the player to move the camera (or other objects) by simple holding a mouse button (you decide what button) and dragging the mouse around. Very useful for top down games.
It will also allow the player to move the camera (or other objects) by pressing W, A, S, D keys.
There is some configuration to help you adapting this logic to better fit in your project. If you want to drag the camera in a vertial way, to create a side scroller game, for example, you can easly change the "Up Axis" to allow this.
You can attach this component into your camera or into other objects. It's very simple to configure:
- **Show Mouse**: Enable if you want to show the mouse
- **Mouse Movement**: Enable if you want to activate the mouse drag logic
- **Mouse Button**: Which mouse button you want to use
- **Keyboard Movement**: Enable if you want to move the object using W,A,S,D
- **Up Axis**: Select the UP axis.
- **Local Movement**: Local or Global movement? You decide!
- **Mouse Sensibility**: The mouse sensibility!
- **Keyboard Speed**: If you enabled the Keyboard Movement, control the speed here!
- **Limit Area**: You can limit the area that the object can stay by playing around with this values. If you don't want, just set to 0.

## Mouse Click Component
This component will allow you to teleport an object right into the point that the player clicks. You can limit the scope of the clicks by adding a property. This feature is very useful for top down/point and click games, because you need a pivot to point where the player wants the character to go.
It's very simple to configure:
- **Activate**: Activate or deactivate the logic
- **Mouse Button**: Which mouse button you want to use
- **Align To Normal**: Enable if you want to align the object to the mouse over normal.
- **Property**: The property that you want to interact with (leave this blank if you want to interact with everything).

## Object Chaser Component
This component will make the object chase a target (another object) when they have certain distance. Note that is necessary to have a navmesh in your scene.
You can also change the Target object in realtime by calling the function setTarget().
It's very simple to configure:
- **Activate**: Activate or deactivate the logic.
- **Navmesh Name**: The name of your navmesh.
- **Target Object**: The name of your target.
- **Min Distance**: The minimum distance that you want the object from the target.
- **Tolerance Distance**: Once the object is already near the target, the extra tolerance distance that they can have before it starts chasing again.
- **Speed**: The speed of the object while chasing the target.
- **Front Axis**: The front Axis (put Y axis if you don't know).
- **Up Axis**: The up Axis (put Z if you don't know).
- **Smooth Turn**: To smooth the path following turns.

Created by **Guilherme Teres Nunes**

Access my youtube channel:
## [Uniday Studio on Youtube](youtube.com/UnidayStudio)