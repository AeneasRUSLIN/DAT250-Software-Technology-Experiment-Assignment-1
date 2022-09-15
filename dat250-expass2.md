# DAT250-Software-Technology-Experiment-Assignment-2

## Experiment 1: JPA tutorial

No technical problems were met during the installation.

I used the maven project experiment-1 instead of creating another project and manually moving the .jar files.

I followed the vogella tutorial and copied the code from the tutorial while changing the appropriate file names and dependencies.

I was able to visualize the database tables by using IntelliJ.

![ScreenHunter 393](https://user-images.githubusercontent.com/95423689/190444275-5aff36f2-585d-47e2-a8fc-9d8d01a620d6.png)


## Experiment 2 : Banking/Credit Card example JPA

Lombok was installed and used for the implementation of the domain model for credit cards. However, Eclipse IDE  didn’t recognize Lombok. When using @Data, @Getter and @Setter for instance, we got the following error message : “ the import lombok cannot be resolved”. 

Reinstalling Lombok through the Eclipse with the following steps : 

- Click on the “Help” tab
- Select the “Install New Software…” option
- Writing the link : “https://projectlombok.org/p2” into the text box
- Selecting Lombok and clicking on finish
- Restarting Eclipse and rebuilding the project

This seems to have solved the issue.


After doing the rest of the configurations and mappings, when the MainTest was ran, an error appeared. The database couldn’t be created or found. To solve the issue, the path of the database in the persistence.xml file was changed to a more accessible location. We suspect that the issue is probably linked to the firewall or administrator rights.


After solving the previous issues and running successfully the MainTest, IntelliJ was used to look at the database. We get the following schema : 

![ScreenHunter 392](https://user-images.githubusercontent.com/95423689/190428938-ae194904-2105-4787-a1b9-0394f6dc7424.png)

The created tables seem to correspond to the diagram of the assignment.

Link to the code of experiment 2 : https://github.com/AeneasRUSLIN/dat250-jpa-example/tree/master/eclipselink/experiment-2

No other pending issue remains.

Side Note :
This lab assignement was done in collaboration with the following people : Jingwen CHEN and Anthony LEBLANC.
