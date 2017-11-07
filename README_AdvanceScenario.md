# Hands-on Demo 2017  
Instructions of hands-on demo for participant.  

# Advance Scenario  
You get to create a [minimal app](https://github.com/personium/template-app-cell) and launch it from HomeApp.  

1. Access the MinimalApp cell from the [Cell Manager](https://demo.personium.io/app-uc-unit-manager/__/unitmgr-light/login.html)  
1. Download and modify profile.json in the main box.   
    1. Before  

            {
                "CellType": "App",
                "DisplayName": {"en": "MinimalApp", "ja": "最小限アプリ"},
                "Description": {"en": "A minimal app that display the app's profile name.", "ja": "デモ用最小限アプリ"},
                ...
            }

    1. After (replace John Doe with your name) 

            {
                "CellType": "App",
                "DisplayName": {"en": "MinimalAppModified", "ja": "最小限アプリ"},
                "Description": {"en": "Hands-on Demo (John Doe): A minimal app that display the app's profile name.", "ja": "デモ用最小限アプリ"},
                ...
            }

1. Upload files  
1. Access the HomeApp of the cell created in Basic Scenario.  
1. Click App Market  
1. Click MinimalAppModified to display the description.  
1. Install the app  
1. Launch it  
1. You can also try to modify the app.html in the main box's src folder.  

# Extra Scenario  
For challengers, when you got back to your office, you can follow the deployment instructions in [GitHub](https://github.com/personium/template-app-cell) to create a [minimal app](https://github.com/personium/template-app-cell) and launch it from HomeApp.  
