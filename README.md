# monoprocessing.github.io

mono:Processing is a framework/wrapper built overtop MonoGame that implements the processing language as a basis for the 2D side, along with box 2D physics, an entity component system inspired by the unity framework, 3D animations using Aether.Extras, Bepu-Based 3D physics, and IMGUI as a debugging/GUI tool. This framework was created with a primary focus on allowing flexibility, and lower level control while simultaneously supplying the user with tools for quickly creating games or creative applications.

In mono:Processing, gameObjects are used to contain entities, and also to initialize/update entities. This means you can create entities without using gameObjects, or even from within other gameObjects as they are two mostly decoupled systems. Any standard class can be used as a component on an entity seeing as they are meant to just hold data or methods, however the gameobjects provide a way of controlling that data by using monocomponents.

Monocomponents are interfaces which attach themselves onto your gameobject and do whatever you want them to do. It's very similar to adding a component to a gameObject in unity.

The "Processing" class functions as your "game" which contain "scenes" that hold your "gameObjects" as well as pointers to the "entities" within them. This means you can have multiple scenes running at the same time, with in one instance of the processing class.

As of right now i'm working on this project myself, I'm currently implementing 3D animation using Aether.Extras, then I'll move on to 2D physics. After this, i'll make the first version of the engine publiclly available, my hope is that it should work on mac, linux, and windows!
