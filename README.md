# A Simple Game

This is a simple raindrop game made from an old tutorial on creating a first game with **libGDX** game framework, and developed using **Eclipse IDE**. Press left and right arrow keys to move the bucket in order to get as much water drops as possible.

## **Setup Instructions**

### **1. Clone the Repository**
Run the following command in your terminal or command prompt:
```sh
git clone https://github.com/jocarthaens/a-simple-game
cd <your-project-folder>
```

### **2. Download Dependencies**
LibGDX and its dependencies are managed by Gradle. To ensure everything is properly downloaded, run:

#### **On Windows:**
```sh
gradlew.bat clean build
```

#### **On Mac/Linux:**
```sh
./gradlew clean build
```

This will automatically download and configure all required libraries.

### **3. Import the Project into Eclipse**
1. Open Eclipse.
2. Select **File > Import > Existing Gradle Project**.
3. Choose the cloned project directory.
4. Click **Finish** and wait for the Gradle build to complete.

### **4. Run the Project**
After importing the project, run the **desktop launcher**:
1. Navigate to the `desktop` module in Eclipse.
2. Right-click `DesktopLauncher.java`.
3. Select **Run As > Java Application**.

