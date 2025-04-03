# My libGDX Project

This is a **libGDX** project developed using **Eclipse IDE**.

## **Setup Instructions**

### **1. Clone the Repository**
Run the following command in your terminal or command prompt:
```sh
git clone <your-repository-url>
cd <your-project-folder>
```
Replace `<your-repository-url>` with the actual GitHub repository URL.

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

## **License**
[Specify your project’s license if applicable.]
