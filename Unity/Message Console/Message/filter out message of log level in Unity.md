# Q: filter out message of log level in Unity.
Just simply to fetch the default logger then set the filter of the log level to determine which kind of message are displayed in Unity Console.

To fetch the default logger, just access
        
        Debug.unityLogger
        
 To set the filter of log level, just change the value of the property 
        
        filterLogType
        
  ## Example
  ### Example 1
  #### Code 
      ILogger logger = Debug.unityLogger;
      logger.filterLogType=LogType.Error;
      //logger.filterLogType=~(LogType.Error | LogType.Log);

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
#### Result
![image](https://github.com/40843245/Game_Development/assets/75050655/6b3535f4-9550-4fe8-a4dd-ed5dda901e91)

## Ref
From Unity Scripting API,

About the filterType property,

https://docs.unity3d.com/ScriptReference/LogType.html
