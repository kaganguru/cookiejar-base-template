### Project Settings

We have our own set of project settings (project.godot) to run the process smoothly on our platform. We have our default project.godot that your project will be subject to. You can use the default cookie jar template to start creating, immediately by simulating a cookie jar template.

**Your changes to project settings will be disregarded** when you export for the cookie jar app. 

Therefore, 

- you can’t use autoloads (singletons)
- you can’t use custom input configurations
    
    however, since it will be a mobile games, you will not need it that much. just use the touch events.
    
- you cannot change the window size/window mode- it’s 3:5
- you can’t change the quality settings
    
    they’re carefully configured to suit well for all devices including low-end ones.
    

**Basically you don’t want to touch  project settings.**