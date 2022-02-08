# Introduction

Scene Management is another concept used in Unity to manage scenes. A game can have as many scenes required but will definitely require one scene at least. Let us understand what is a scene first.
For any new script file, we need to write at the beginning - using UnityEngine.SceneManagement; which gives us access to the Scene and SceneManager Class related functions.
Scene: A scene can be defined as an asset which contains all or part of a game or application, this is where you get to work with content in Unity. To create a new scene go to File ->  New Scene or Ctrl+N (hotkey shortcut).

![Scene_File](https://user-images.githubusercontent.com/44625252/152945409-69f8bbc3-b5a4-4af2-8509-7a14b575819a.png)

When you create a new scene for the first time in some unity versions, a Camera and Directional Light gameObjects may be provided to you by default as most of the time, a scene needs these 2 basic gameObjects, of course, you can delete them and create whatever gameObjects you want but Unity just gives a starting point for you. You can also create a new scene from Assets -> Create -> Scene as shown:

![Assets_Scene](https://user-images.githubusercontent.com/44625252/152945488-09af9e73-7f36-4592-be01-e2336d4d86a2.png)

Other options from File at the top, you can also use “Open Scene” to open any other scene in the Editor, and “Save” or “Save As” to save the current scene or any edits on top of it.

Unity also provides the ability to edit multiple scenes using the “Open Scene Additive” as shown, right-clicking any scene will pop-up this option. Another way to get this option is by dragging one or more scenes from the Project Window into the Hierarchy Window.
When you have multiple scenes open in the editor, each scene’s contents are displayed separately in the hierarchy window. Each scene’s contents appears below a scene divider bar which shows the scene’s name and its save state.

![Multi_Scene](https://user-images.githubusercontent.com/44625252/152947503-2b8a5919-762a-4d69-93a2-5dddf9774220.png)

---
<aside>

> 💡 🚀 **[Join Discord Server](https://discord.gg/J5zDscnzms) → Get your doubts solved by experts instantly**
</aside>

![discord_png](https://user-images.githubusercontent.com/44625252/152947589-0a46eccb-669b-4b0c-a73b-b9b168446a8b.png)

---
