# Solution

Remember the use case for adding to your scripts so that your scene changes from one to another.

In the last chapter, we saw how to add Scene Manager library to our script.  Did you get the solution yet to the problem of changing scenes?

![](https://media.giphy.com/media/J685Df41XlbOl9oR5W/giphy.gif)

Here is a code snippet that can help you accomplish the task:

```
switch(levelStatus)
{
  case LevelStatus.Locked:
    Debug.Log("Can't play this level until unlocked")
    break;
  
  case LevelStatus.Unlocked:
    SceneManager.LoadScene(LevelName);
    break;  
  
  case LevelStatus.Completed:
    SceneManager.LoadScene(LevelName);
    break;   
}
```

Remember you need to have the Scene Management library imported to your script file.

And that's it! See you in the next one.
