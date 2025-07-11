# Image Management (List)
![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/windick/png/imagemanagementlist.png "imagemanagement")
# List Builder
![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/windick/png/listbuildermisc.png "listbuildermisc")
⠀\
**Base-List (.base)** \
⠀● Appx/feat/comp/cap/serv/task/drvr source database for building lists \
⠀● Generated from a Windows virtual disk image or current environment \
⠀\
![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/windick/png/listbuilderbase.png "listbuilderbase")
⠀\
**Base-Group (.base)** \
⠀● Group database for building lists \
⠀● Assembles groups into a menu ● builds list upon menu choice \
⠀● tweaks.base is a Base-Group \
⠀\
![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/windick/png/listbuildertweaks.png "listbuildertweaks")
# List Execute
**Multi-List (.list)** \
⠀● Group database for execution ● target prompt optional \
⠀● Assembles groups into a menu ● executes upon menu choice \
⠀● tools.list is a Multi-List \
⠀\
![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/windick/png/listexecutemulti.png "listexecutemulti")
⠀\
**Exec-List (.list)** \
⠀● Queue of items for execution ● target prompt always \
⠀● Executes entire list from top to bottom, ignoring groups \
⠀\
![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/windick/png/listexecutelog.png "listexecutelog")
⠀\

# Image Management (Pack)
![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/windick/png/imagemanagementpack.png "imagemanagement")
# Pack Builder
![Alt text](https://raw.githubusercontent.com/joshuacline/documentation/main/windick/png/packbuilder.png "packbuilder")
⠀\
⠀● May contain drivers, installers, and additional appx/cab/msu packages \
⠀● Functions are declared in package.list \
⠀● Exported drivers are integrated by executing the package or adding to a list \
⠀● Wim based and can be opened with a zip application \
