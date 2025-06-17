## PlantSim
A Multi-Agent simulation utilizing Repast Simphony that models the behavior of the growth of Sorghum and Maize. Created under research grant to model the root and shoot of a plant simultaneously

## installing PlantSim
 1. Install Repast Simphony [here] (https://repast.github.io)
   > This simulation uses RepastSimphony-2.10.0
 2. Download the simulation model PlantSim.zip
 3. Ensure you have java JDK 11 installed
 > it may work without it, but if the simulation fails, that might be the issue.

## Importing PlantSim
1. open Eclipse with Repast Simphony
>the Eclipse application may be named Repast Simphony if you didn't have Eclipse installed previously
>
>If you see an error appear in the middle of the screen, that's normal. It will not effect anything you can minimize it and it will leave you alone
 2. in the top left, click File > Import
>Ensure that the PlantSim.zip folder is extracted somewhere you can find it
 3. under General, click "Existing Projects into Workspace"
 4. Ensure "select root directory" is highlighted, change the directory to the "PlantSim" folder
 5. Select the PlantSim project and click "Finish" on the bottom
  > the project should show under the "projects" section. If it does not, make sure the correct directory is selected for step 3.

The project should be imported.

## Eclipse Housekeeping
 Eclipse can have some funky interactions if not set up properly, so follow these steps to make sure everything works

 1. On the top, click "Project" > "Properties"
 2. Under "Java Compiler", ensure "Compiler compliance level" is set to "11"

## Running PlantSim
1. near the top of the window, there should be a green arrow, click the gray "down" arrow next to it.
> this should open a dropdown menu
2. click PlantSim Model

IF PLANTSIM MODEL ISNT THERE...
1. in the package explorer window, right click on the PlantSim directory
  >if the package explorer isnt open, click "Window" > "Show Viiew" > "Package Explorer"
2. hover over "Run As"
3. click "Java Application
4. Select "RepastMain - repast.simphony.runtime" > Ok

>this will launch the application and you should be able to follow the first steps now.

You can now run the PlantSim in Repast Simphony, if you do not know how to use Repast Simphony, read the [documentation] (https://repast.github.io/docs/ReLogoGettingStarted.pdf)
