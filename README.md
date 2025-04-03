# My libGDX Project

This is a **libGDX** project developed using **Eclipse IDE**.

## **Setup Instructions**

### **1. Clone the Repository**
Run the following command in your terminal or command prompt:
```sh
git clone https://github.com/jocarthaens/a-simple-game/
cd <your-project-folder>

2. Download Dependencies

LibGDX and its dependencies are managed by Gradle. To ensure everything is properly downloaded, run:
On Windows:

gradlew.bat clean build

On Mac/Linux:

./gradlew clean build

This will automatically download and configure all required libraries.
3. Import the Project into Eclipse

    Open Eclipse.

    Select File > Import > Existing Gradle Project.

    Choose the cloned project directory.

    Click Finish and wait for the Gradle build to complete.

4. Run the Project

After importing the project, run the desktop launcher:

    Navigate to the desktop module in Eclipse.

    Right-click DesktopLauncher.java.

    Select Run As > Java Application.
