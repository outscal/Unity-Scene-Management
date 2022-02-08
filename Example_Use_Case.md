# Example Use Case

A typical example of usage is shown below, which simply loads the scene based on the name of the scene:

![LoadScene](https://user-images.githubusercontent.com/44625252/152946474-6df2bcae-a3fb-4649-85fb-be7fb393c11b.png)

Remember to add the scenes in the list from File->Build Settings as shown:

![File_buildSettings](https://user-images.githubusercontent.com/44625252/152946574-cf3d12dc-a934-419e-99b5-d31b3493a255.png)

Doing this actually tells Unity the total number of scenes that are required to be built in the end when the application development has been completed and is ready to be published. This also allows the SceneManager related functions to be used for the mentioned scenes.

You can drag and drop the required scenes in the Build settings input window as shown:

![dragNDropScene](https://user-images.githubusercontent.com/44625252/152946640-bccd8b3e-0619-4474-9491-58b1cb554b7a.png)

Or you can click on “Add Open scenes” in the same window to add the required scenes:

![OpenScenes](https://user-images.githubusercontent.com/44625252/152946688-b40e18b6-7d04-4d56-82bb-058019567608.png)

The index number at the of each scene in this window mentioned towards the right side shows the order in which the scenes are listed, you can always use this index number to fetch the respective scene as well (for example, GetSceneByBuildIndex):

![SceneIndex](https://user-images.githubusercontent.com/44625252/152946754-0f32af13-3f0a-452b-86b6-6514e83fcb1c.png)

Also, you can reorder the scenes in this list as required for your game. Remember the first scene which is labelled 0 is the one that is loaded at first whenever the game is started from the build.

---
<aside>

> 💡 🚀 **[Join Discord Server](https://discord.gg/J5zDscnzms) → Get your doubts solved by experts instantly**
</aside>
![discord_png](https://user-images.githubusercontent.com/44625252/152805317-45a22cd7-fbf5-49cc-a13d-01282d498b03.png)

---
