# Q: enable or disable to log message with code in Unity 
It is very simple. Just fetch default logger. Then enable or disable to log it.

To fetch default logger, just access 
              
    Debug.unityLogger
    
To enable it, just set the attribute logEnable to true.

    Debug.unityLogger.logEnabled = true ; 
    
To disbale it, just set the attribute logEnable to false.

    Debug.unityLogger.logEnabled = false ; 

