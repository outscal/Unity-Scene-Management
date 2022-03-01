# Solution

Remember the use case for adding to your scripts so that your scene changes from one to another.

In the last chapter, we saw how to add Scene Manager library to our script. 


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

