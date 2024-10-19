# Image Management
![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/windick/png/imagemanagement.png "imagemanagement")

# List Builder
- Base-List (.base) ⬦ appx/feat/comp/serv/task/drvr source database for building lists
    - Generated from a Windows virtual disk image or current environment

![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/windick/png/listbuilderbase.png "listbuilderbase")
- Base-Group (.base) ⬦ group database for building lists
  - tweaks.base is a Base-Group

![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/windick/png/listbuildertweaks.png "listbuildertweaks")
- Miscellaneous
![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/windick/png/listbuildermisc.png "listbuildermisc")

# List Execute
- Exec-List (.list) ⬦ queue of items for execution ⬦ target prompt always
  - Executes entire list from top to bottom, ignoring groups

![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/windick/png/imagemanagementlog.png "imagemanagementlog")

  - Multi-List (.list) ⬦ group database for execution ⬦ target prompt optional
    - Assembles groups into a menu, then executes upon menu choice
    - tools.list is a Multi-List
