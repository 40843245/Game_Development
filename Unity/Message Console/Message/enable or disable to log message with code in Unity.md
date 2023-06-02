# Q: enable or disable to log message with code in Unity 
It is very simple. Just fetch default logger. Then enable or disable to log it.

To fetch default logger, just access 
              
    Debug.unityLogger
    
To enable it, just set the property logEnable to true.

    Debug.unityLogger.logEnabled = true ; 
    
To disbale it, just set the property logEnable to false.

    Debug.unityLogger.logEnabled = false ; 
    
    
## Example 
### Code
  
    ILogger logger = Debug.unityLogger;
      logger.Log("Yes", "Hello");
      logger.LogWarning("Yes", "Hello");
      logger.LogError("Yes", "Hello");

      logger.logEnabled=false;

      logger.Log("No", "Hello");
      logger.LogWarning("No", "Hello");
      logger.LogError("No", "Hello");

      logger.logEnabled=true;

      logger.Log("Ok", "Hello");
      logger.LogWarning("Ok", "Hello");
      logger.LogError("Ok", "Hello");

### Result

![image](https://github.com/40843245/Game_Development/assets/75050655/cee4b447-7b80-42e3-91e7-76745918af19)

## Ref
From Unity Scripting API,

About the interfaces ILogger,

https://docs.unity3d.com/2020.2/Documentation/ScriptReference/ILogger.html

About the property logEnabled,

https://docs.unity3d.com/2020.2/Documentation/ScriptReference/ILogger-logEnabled.html
