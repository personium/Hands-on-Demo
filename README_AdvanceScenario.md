# Hands-on Demo 2017  
Instructions of hands-on demo for participant.  

# Advance Scenario  
You get to modify the [MinimalApp](https://github.com/personium/template-app-cell) and launch it from HomeApp.  

1. Access the MinimalApp cell from the [Cell Manager](  
https://demo.personium.io/app-minimal/io_personium_demo_cell-manager/src/login.html)  
[![](doc/minimal_app_cell_manager_login.png)](https://demo.personium.io/app-minimal/io_personium_demo_cell-manager/src/login.html)  

1. Click "main" to display the contents of the main box.  
[![](doc/minimal_app_cell_manager.png)](https://demo.personium.io/app-minimal/io_personium_demo_cell-manager/src/login.html)  

1. Click profile.json to download it.  
[![](doc/minimal_app_cell_manager_main_box.png)](https://demo.personium.io/app-minimal/io_personium_demo_cell-manager/src/login.html)  

1. Modify the downloaded file (profile.json). 
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
Click App Market  
![](doc/john_doe_app_market.png)  
1. Click MinimalAppModified to display the description.  
![](doc/john_doe_app_market_minimal_app_description.png)  
1. Install the app and confirm that it is displayed in the Home screen.  
![](doc/john_doe_app_market_minimal_app_installed.png)  
1. Launch it  
1. You can also try to modify the app.html in the main box's src folder.  
(Go back to procedure No.1)

# Extra Scenario  
For challengers, when you got back to your office, you can follow the deployment instructions in [GitHub](https://github.com/personium/template-app-cell) to create a [minimal app](https://github.com/personium/template-app-cell) and launch it from HomeApp.  
