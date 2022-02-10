# Scene Manager

So, essentially Scenes contain all the objects of your game or bits and pieces of it if you are using multiple scenes for your game. In each scene, you will place your environments, obstacles, and decorations, essentially designing and building your game in pieces, you can also think of scenes as individual levels if there are multiple levels in your game. So how do you perform the scene related functions you ask? There is a library ofcourse.

![Q!](https://media.giphy.com/media/8mndEBLsg9Whg2Sduv/giphy.gif)

The library that can be used to import the scene related important functions is shown below:
using UnityEngine.SceneManagement;

![script_sceneManagement](https://user-images.githubusercontent.com/44625252/152946079-576e14cd-cab0-4183-b1bc-4fbc8743aec1.png)

Implementing the above in any script allows us to use the functions related to a scene, listed below are some of the common ones that are used:

**sceneCount** – Total number of currently loaded scenes

**sceneCountBuildSettings** – Number of Scenes in build settings

**CreateScene** – Create an empty new scene at runtime with the given name

**GetActiveScene** – Fetch the currently active scene

**GetSceneByBuildIndex** – Get a scene struct from a build index

**GetSceneByName** – As can be inferred, this fetches the scene with the given name

**LoadScene** – Loads the scene by its name or index in Build settings

**SetActiveScene** – Set the scene to be active

A complete list of all functions can be found in the Unity documentation -

[https://docs.unity3d.com/ScriptReference/SceneManagement.SceneManager.html](https://docs.unity3d.com/ScriptReference/SceneManagement.SceneManager.html)

On to the field to dirty your hands soldier! Think of how different scenes in a battle transitions and where some of these functions can be used.

![Got!](https://media.giphy.com/media/3oEjI1erPMTMBFmNHi/giphy.gif)
