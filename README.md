# Android-programming-Questions
---

### **📌 5 Long-Answer Questions (10 Marks Each)**
#### **Q1: Explain the history and evolution of Android.**  
**Answer:**  
Android is an open-source mobile operating system developed by Google. It was initially created by **Android Inc.** in **2003**, founded by Andy Rubin. Google acquired Android Inc. in **2005** and released the first Android version, **Android 1.0**, in **2008** with the HTC Dream (T-Mobile G1) smartphone.  

**Evolution of Android:**  
- **2008:** **Android 1.0** – Basic features like Gmail, Maps, and browser.  
- **2010:** **Android 2.2 (Froyo)** – Introduced Flash support and performance improvements.  
- **2011:** **Android 3.0 (Honeycomb)** – Optimized for tablets.  
- **2013:** **Android 4.4 (KitKat)** – Better memory management and Google Now.  
- **2015:** **Android 6.0 (Marshmallow)** – Introduced **Doze Mode** and **App Permissions**.  
- **2017:** **Android 8.0 (Oreo)** – Picture-in-picture mode.  
- **2020:** **Android 11** – Chat bubbles, screen recording.  
- **2023:** **Android 14** – Battery optimization, security enhancements.  

Android continues to evolve with a focus on **security, AI, and better user experience**.  

---

#### **Q2: Explain the Android Architecture with a neat diagram.**  
**Answer:**  
Android architecture is layered into four main components:  

1. **Linux Kernel**  
   - Handles **hardware** (camera, Bluetooth, Wi-Fi).  
   - Manages **memory**, **power**, and **drivers**.  

2. **Hardware Abstraction Layer (HAL)**  
   - Provides an **interface** between hardware and Android system.  
   - Manages **camera, sensors, and audio**.  

3. **Native C/C++ Libraries**  
   - Includes SQLite (database), OpenGL (graphics), and Media framework.  

4. **Android Runtime (ART)**  
   - Executes Android apps using **Just-In-Time (JIT) Compilation**.  

5. **Application Framework**  
   - Provides services like **Activity Manager, Location Manager, and Notification Manager**.  

6. **Applications**  
   - The user layer where apps like **Gmail, Chrome, and Instagram** run.  

*(Diagram representation should be drawn with labeled sections.)*  

---

#### **Q3: Describe the different Android Development Tools and their purposes.**  
**Answer:**  
Android development tools help in building, testing, and debugging Android apps. The key tools are:  

1. **Android Studio**  
   - Official **Integrated Development Environment (IDE)** for Android.  
   - Features like **Code Editor, Emulator, and Debugging Tools**.  

2. **Android SDK (Software Development Kit)**  
   - Provides libraries, compilers, and APIs to develop Android apps.  

3. **Android Virtual Device (AVD) Emulator**  
   - Simulates an Android device for testing.  

4. **Gradle Build System**  
   - Helps in **dependency management** and **automated builds**.  

5. **Android Debug Bridge (ADB)**  
   - Allows communication between a computer and an Android device for debugging.  

6. **Logcat**  
   - Displays system messages and debugging logs.  

---

#### **Q4: Discuss the key features and advantages of the Android Operating System.**  
**Answer:**  
Android OS is widely used due to its **open-source** nature and flexible architecture.  

**Key Features:**  
1. **Open-Source:** Anyone can modify and customize Android.  
2. **Multitasking:** Run multiple apps simultaneously.  
3. **Rich UI:** Supports **XML-based UI design, animations, and custom themes**.  
4. **Security Features:** Introduced **biometric authentication, app sandboxing, and permissions**.  
5. **Cross-Device Support:** Works on **smartphones, tablets, TVs, and wearables**.  

**Advantages:**  
✔ Huge community support.  
✔ Large app ecosystem (Google Play Store).  
✔ Cost-effective for manufacturers.  
✔ Custom ROM support for better customization.  

---

#### **Q5: Compare Android and other mobile operating systems (iOS, Windows, etc.).**  
**Answer:**  

| Feature         | Android               | iOS                 | Windows Phone (Discontinued) |
|---------------|----------------------|----------------------|-----------------------------|
| **Developed by** | Google | Apple | Microsoft |
| **Customization** | High (Custom ROMs) | Limited | Moderate |
| **App Store** | Google Play | App Store | Microsoft Store |
| **Programming Language** | Java, Kotlin | Swift, Objective-C | C# |
| **Open-Source** | Yes | No | No |
| **Device Support** | Multiple brands | Only Apple devices | Only Microsoft devices |
| **Market Share** | ~72% | ~27% | Discontinued in 2019 |

Android dominates the market due to its **affordability and flexibility**.

---

### **📌 7 Medium-Answer Questions (3 Marks Each)**  

#### **Q1: What is Android?**  
**Answer:**  
Android is an **open-source, Linux-based mobile operating system** developed by Google. It is widely used in **smartphones, tablets, and IoT devices**.  

#### **Q2: What are the key components of Android Architecture?**  
**Answer:**  
Android consists of:  
1. **Linux Kernel** – Manages hardware.  
2. **Native Libraries** – Provides support for SQLite, OpenGL.  
3. **Android Runtime (ART)** – Runs apps.  
4. **Application Framework** – Manages UI and system services.  
5. **Applications** – User-installed apps like Gmail, WhatsApp.  

#### **Q3: What are the main development tools for Android?**  
**Answer:**  
- **Android Studio (IDE for development)**  
- **Android SDK (provides APIs and tools)**  
- **Gradle (build automation system)**  
- **ADB (debugging tool)**  

#### **Q4: What is the role of the Android Runtime (ART)?**  
**Answer:**  
ART is a **runtime environment** that compiles Java/Kotlin apps into **native machine code**, improving **performance and efficiency**.  

#### **Q5: How is Android different from iOS?**  
**Answer:**  
- **Android** is **open-source** while **iOS** is closed-source.  
- Android allows **third-party app stores**, whereas iOS does not.  
- Android uses **Java/Kotlin**, whereas iOS uses **Swift/Objective-C**.  

#### **Q6: What is ADB in Android development?**  
**Answer:**  
ADB (Android Debug Bridge) is a command-line tool used for **communicating with a device for debugging**.  

#### **Q7: What is Gradle in Android?**  
**Answer:**  
Gradle is a **build automation tool** that helps manage dependencies and compile Android applications.  

---

### **📌 10 Short-Answer Questions (1-2 Marks Each)**  
1. What is the latest version of Android?  
2. Name three Android versions named after desserts.  
3. What is the official language for Android development?  
4. What does AVD stand for?  
5. What is the role of the Linux Kernel in Android?  
6. Define "APK" in Android.  
7. What is Logcat used for?  
8. Name two Android IDEs.  
9. What is the function of AndroidManifest.xml?  
10. What is an Activity in Android?  

---

## **📌 5 Long-Answer Questions (10 Marks Each)**  

### **Q1: Explain the core OOP principles in Java with examples.**  
**Answer:**  
Object-Oriented Programming (OOP) in Java is based on four fundamental principles:  

1. **Encapsulation**  
   - Wrapping data (variables) and code (methods) together in a class.  
   - Example:  
     ```java
     class Student {
         private String name;
         public void setName(String n) { name = n; }
         public String getName() { return name; }
     }
     ```

2. **Abstraction**  
   - Hiding implementation details and showing only essential information.  
   - Example:  
     ```java
     abstract class Vehicle {
         abstract void start();
     }
     class Car extends Vehicle {
         void start() { System.out.println("Car starts with key"); }
     }
     ```

3. **Inheritance**  
   - One class acquires properties and behaviors of another class.  
   - Example:  
     ```java
     class Animal { void eat() { System.out.println("Eating..."); } }
     class Dog extends Animal { void bark() { System.out.println("Barking..."); } }
     ```

4. **Polymorphism**  
   - A single interface or method can have multiple implementations.  
   - Example:  
     ```java
     class Shape { void draw() { System.out.println("Drawing shape"); } }
     class Circle extends Shape { void draw() { System.out.println("Drawing Circle"); } }
     ```

OOP makes Java **modular, scalable, and reusable**, making it ideal for Android development.

---

### **Q2: Differentiate between Overloading and Overriding with examples.**  
**Answer:**  

| Feature       | Method Overloading | Method Overriding |
|--------------|------------------|------------------|
| **Definition** | Multiple methods with the same name but different parameters in a class. | A subclass redefines a method from its parent class. |
| **Return Type** | Can be different | Must be the same |
| **Parameters** | Must be different | Must be the same |
| **Scope** | Happens in the same class | Happens in a subclass |

#### **Example of Overloading:**
```java
class MathOperations {
    int add(int a, int b) { return a + b; }
    double add(double a, double b) { return a + b; }
}
```

#### **Example of Overriding:**
```java
class Parent {
    void show() { System.out.println("Parent class method"); }
}
class Child extends Parent {
    void show() { System.out.println("Child class method"); }
}
```

---

### **Q3: Explain the concept of Java Threads and their importance in Android development.**  
**Answer:**  
A **Thread** in Java is the smallest unit of execution. Multithreading allows multiple tasks to run simultaneously, making applications **efficient and responsive**.  

#### **Creating Threads in Java:**  
1. **Extending Thread class**  
   ```java
   class MyThread extends Thread {
       public void run() { System.out.println("Thread is running"); }
   }
   ```
2. **Implementing Runnable interface**  
   ```java
   class MyRunnable implements Runnable {
       public void run() { System.out.println("Runnable thread running"); }
   }
   ```

#### **Importance in Android:**  
- **Main (UI) Thread**: Handles user interface operations.  
- **Worker Threads**: Run background tasks (e.g., downloading files).  
- **AsyncTask & Handler**: Used to update the UI from background threads.  

Example in Android:  
```java
new Thread(new Runnable() {
    public void run() {
        System.out.println("Background process running");
    }
}).start();
```

---

### **Q4: What is JVM? Explain its working and components.**  
**Answer:**  
The **Java Virtual Machine (JVM)** is an engine that runs Java applications by converting **bytecode** into machine code.  

#### **Working of JVM:**  
1. **Java Code Compilation:** Java files (`.java`) are compiled into bytecode (`.class`).  
2. **Class Loader:** Loads class files into memory.  
3. **Bytecode Execution:** **JIT (Just-In-Time) Compiler** converts bytecode into machine code.  
4. **Runtime Management:** Handles memory, garbage collection, and security.  

#### **Components of JVM:**  
- **Class Loader:** Loads classes into memory.  
- **Method Area:** Stores class-level metadata.  
- **Heap:** Stores objects.  
- **Stack:** Stores method calls.  
- **Execution Engine:** Runs the program.  

The JVM makes Java **platform-independent** by allowing the same code to run on different OS.

---

### **Q5: Explain the difference between Abstract Class and Interface in Java.**  
**Answer:**  

| Feature          | Abstract Class | Interface |
|-----------------|---------------|-----------|
| **Definition**  | A class that cannot be instantiated and may have abstract methods. | A collection of abstract methods that must be implemented. |
| **Methods**     | Can have both abstract and non-abstract methods. | Can only have abstract methods (before Java 8). |
| **Variables**   | Can have instance variables. | Only has public static final variables. |
| **Multiple Inheritance** | Not supported | Supported |

#### **Example of Abstract Class:**
```java
abstract class Animal {
    abstract void makeSound();
    void eat() { System.out.println("Eating..."); }
}
```

#### **Example of Interface:**
```java
interface Drawable {
    void draw();
}
class Circle implements Drawable {
    public void draw() { System.out.println("Drawing Circle"); }
}
```

---

## **📌 7 Medium-Answer Questions (3 Marks Each)**  

### **Q1: What is Polymorphism? Give an example.**  
**Answer:**  
Polymorphism allows a single method to have multiple implementations.  
Example:  
```java
class Animal { void sound() { System.out.println("Animal makes a sound"); } }
class Dog extends Animal { void sound() { System.out.println("Dog barks"); } }
```

---

### **Q2: Define Multithreading and its advantages.**  
**Answer:**  
Multithreading allows multiple tasks to run simultaneously, improving performance.  
**Advantages:**  
- Better CPU utilization.  
- Faster execution.  
- Non-blocking UI in Android apps.  

---

### **Q3: What is method overriding? Provide an example.**  
**Answer:**  
When a subclass provides a specific implementation of a method from its superclass.  
Example:  
```java
class Parent { void display() { System.out.println("Parent method"); } }
class Child extends Parent { void display() { System.out.println("Child method"); } }
```

---

### **Q4: What is the difference between a Process and a Thread?**  
**Answer:**  

| Feature   | Process | Thread |
|-----------|---------|--------|
| **Definition** | A running instance of a program | A lightweight unit of a process |
| **Memory** | Separate memory for each process | Shares memory within a process |
| **Communication** | Inter-process communication needed | Shared memory |

---

### **Q5: Explain the concept of Encapsulation.**  
**Answer:**  
Encapsulation hides the internal implementation of a class.  
Example:  
```java
class Account {
    private double balance;
    public void setBalance(double b) { balance = b; }
    public double getBalance() { return balance; }
}
```

---

## **📌 10 Short-Answer Questions (1-2 Marks Each)**  

1. What is an Object in Java?  
2. Define **Inheritance**.  
3. What is the difference between `final` and `abstract`?  
4. Name two ways to create a thread in Java.  
5. What is the purpose of the `super` keyword?  
6. What is the default garbage collection mechanism in JVM?  
7. What does JIT compiler do?  
8. Can a constructor be overridden?  
9. What is the difference between a `Runnable` and `Thread`?  
10. What is the base class of all Java classes?  

---

## **📌 5 Long-Answer Questions (10 Marks Each)**  

### **Q1: Explain the steps to install and configure Eclipse with the ADT Plugin for Android development.**  
**Answer:**  
To set up Eclipse for Android development using the **Android Development Tools (ADT) plugin**, follow these steps:  

1. **Download & Install Eclipse:**  
   - Download Eclipse IDE for Java Developers from the official Eclipse website.  
   - Install Eclipse on your system.  

2. **Install Android SDK:**  
   - Download the Android SDK from the Android Developer website.  
   - Install it and set the **SDK path**.  

3. **Install ADT Plugin in Eclipse:**  
   - Open Eclipse → Go to **Help** → **Eclipse Marketplace**.  
   - Search for **ADT Plugin** and install it.  

4. **Configure Eclipse with ADT:**  
   - Go to **Window** → **Preferences** → **Android**.  
   - Set the **SDK Location** where Android SDK is installed.  

5. **Create an Android Virtual Device (AVD):**  
   - Go to **Android Virtual Device Manager**.  
   - Click on **Create** → Select device configuration → Save.  

6. **Create a New Android Project:**  
   - Open **Eclipse** → **File** → **New** → **Android Application Project**.  
   - Provide the project name, package name, and target SDK.  

7. **Run the Project on Emulator or Physical Device:**  
   - Select **Run** → **Run As Android Application**.  

This setup enables **Android app development** using Eclipse and ADT.

---

### **Q2: Describe the process of installing and configuring an Android Emulator for development.**  
**Answer:**  
An **Android Emulator** simulates a real Android device on a computer for testing.  

#### **Steps to Install & Configure Emulator:**  

1. **Install Android Studio or Eclipse with ADT** (if not installed).  
2. **Open AVD Manager:**  
   - In Android Studio: **Tools** → **Device Manager**  
   - In Eclipse: **Window** → **Android Virtual Device Manager**  

3. **Create a New Virtual Device:**  
   - Click **Create Virtual Device**.  
   - Choose a device type (e.g., Pixel 4, Nexus 5X).  

4. **Select System Image:**  
   - Choose an **Android version** (e.g., **Jelly Bean, Ice Cream Sandwich**).  
   - Click **Download** if needed.  

5. **Configure Emulator Settings:**  
   - Set RAM size, CPU cores, screen size, and SD card storage.  
   - Enable hardware acceleration for better performance.  

6. **Launch Emulator:**  
   - Click **Start** → Wait for boot-up.  

7. **Run an Android App on Emulator:**  
   - Open Android Studio or Eclipse.  
   - Select **Run App** → Choose Emulator.  

This allows testing Android apps without a physical device.

---

### **Q3: What are Intents in Android? Explain types and use cases with examples.**  
**Answer:**  
An **Intent** in Android is used to communicate between components (Activities, Services, etc.).  

#### **Types of Intents:**  
1. **Explicit Intent** (Used to start specific activities)  
   ```java
   Intent intent = new Intent(MainActivity.this, SecondActivity.class);
   startActivity(intent);
   ```
   **Use Case:** Navigating from **MainActivity** to **SecondActivity**.  

2. **Implicit Intent** (Used when the action is known but the target component is not)  
   ```java
   Intent intent = new Intent(Intent.ACTION_VIEW, Uri.parse("https://www.google.com"));
   startActivity(intent);
   ```
   **Use Case:** Opening a URL in a web browser.  

#### **Use Cases of Intents:**  
- **Start a new Activity** (Navigation).  
- **Open external apps** (Browser, Email, Camera).  
- **Broadcast messages** (e.g., Low Battery Warning).  

---

### **Q4: Explain the Android Activity Lifecycle with a diagram.**  
**Answer:**  
An **Activity** in Android has different lifecycle states:  

1. **onCreate()** → Called when the activity is first created.  
2. **onStart()** → Called when the activity is about to be visible.  
3. **onResume()** → Called when the activity starts interacting with the user.  
4. **onPause()** → Called when the activity goes into the background.  
5. **onStop()** → Called when the activity is no longer visible.  
6. **onDestroy()** → Called when the activity is completely removed from memory.  

#### **Diagram:**
```
    onCreate() → onStart() → onResume()
                     ↓
    onPause() → onStop() → onDestroy()
```

#### **Example:**
```java
@Override
protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);
    setContentView(R.layout.activity_main);
    Log.d("Lifecycle", "onCreate called");
}
```

Understanding the **Activity Lifecycle** is important to manage app state and memory.

---

### **Q5: Discuss the challenges of designing user interfaces for multiple screen sizes in Android.**  
**Answer:**  
Android devices come in **different screen sizes** and **resolutions**, making UI design challenging.  

#### **Challenges & Solutions:**  

1. **Different Screen Densities**  
   - **Solution:** Use `dp` (density-independent pixels) instead of `px`.  

2. **Different Aspect Ratios**  
   - **Solution:** Use **ConstraintLayout** for flexible UI.  

3. **Handling Orientation Changes**  
   - **Solution:** Use **onSaveInstanceState()** to preserve UI state.  

4. **Supporting Tablets & Phones**  
   - **Solution:** Use `sw600dp` qualifier for tablet layouts.  

5. **Localization & RTL Support**  
   - **Solution:** Use `values` and `values-rtl` for text direction.  

Using **responsive layouts**, `fragments`, and `ConstraintLayout` ensures **good UI across devices**.

---

## **📌 7 Medium-Answer Questions (3 Marks Each)**  

### **Q1: What is an Android Emulator, and why is it used?**  
**Answer:**  
An **Android Emulator** simulates a real Android device on a computer for testing. It allows developers to test apps without a physical device.  

---

### **Q2: Explain the difference between Explicit and Implicit Intents.**  
**Answer:**  
| **Explicit Intent** | **Implicit Intent** |
|---------------------|---------------------|
| Targets a specific component | Doesn't specify a target |
| Used for navigation between activities | Used for system-wide actions (e.g., opening a URL) |

Example of Explicit Intent:  
```java
Intent intent = new Intent(MainActivity.this, SecondActivity.class);
startActivity(intent);
```

---

### **Q3: Define Application Context in Android.**  
**Answer:**  
**Application Context** is a global context for the entire application. It is used for:  
- **Accessing app-wide resources**  
- **Managing long-running background operations**  

Example:  
```java
Context appContext = getApplicationContext();
```

---

### **Q4: What is the purpose of the Activity Lifecycle in Android?**  
**Answer:**  
It manages the different states of an **Activity**, ensuring smooth transitions and memory optimization.  

---

### **Q5: How do you deploy an Android app on a USB-connected device?**  
**Answer:**  
1. **Enable Developer Options & USB Debugging**.  
2. **Connect the device to the computer** via USB.  
3. **Run the app** using Android Studio.  

---

## **📌 10 Short-Answer Questions (1-2 Marks Each)**  

1. What is ADT in Eclipse?  
2. Define an Intent in Android.  
3. Name two advantages of using an Android Emulator.  
4. What does `dp` stand for in Android UI design?  
5. How do you handle screen orientation changes in Android?  
6. What is an AVD?  
7. Name two ways to test an Android app.  
8. What is the use of `onCreate()` in an activity?  
9. How do you specify layouts for tablets?  
10. What is `AndroidManifest.xml`?  

---

## **Unit-4: User Interface Design & Database in Android**  

Here is a **detailed breakdown** of **Unit-4**, covering **User Interface (UI) Design** and **SQLite Database** in Android.  

---

## **📌 5 Long-Answer Questions (10 Marks Each)**  

### **Q1: Explain different types of Form Widgets used in Android UI Design.**  
**Answer:**  
Form widgets are UI components that allow users to input and interact with the application.  

#### **Common Form Widgets in Android:**  

1. **Text Fields (`EditText`)**  
   - Used for text input like username, password, email.  
   - Example:
     ```xml
     <EditText
         android:id="@+id/editText"
         android:layout_width="wrap_content"
         android:layout_height="wrap_content"
         android:hint="Enter Name"/>
     ```
  
2. **Button (`Button`)**  
   - Used to trigger actions when clicked.  
   - Example:
     ```xml
     <Button
         android:id="@+id/button"
         android:layout_width="wrap_content"
         android:layout_height="wrap_content"
         android:text="Submit"/>
     ```
  
3. **Toggle Button (`ToggleButton`)**  
   - Used to switch between two states (ON/OFF).  
   - Example:
     ```xml
     <ToggleButton
         android:id="@+id/toggleButton"
         android:layout_width="wrap_content"
         android:layout_height="wrap_content"
         android:textOn="ON"
         android:textOff="OFF"/>
     ```

4. **Spinner (Combo Box) (`Spinner`)**  
   - Dropdown menu to select one item from multiple options.  
   - Example:
     ```xml
     <Spinner
         android:id="@+id/spinner"
         android:layout_width="wrap_content"
         android:layout_height="wrap_content"/>
     ```

5. **CheckBox (`CheckBox`)**  
   - Used for multiple-choice selections.  
   - Example:
     ```xml
     <CheckBox
         android:id="@+id/checkbox"
         android:layout_width="wrap_content"
         android:layout_height="wrap_content"
         android:text="Accept Terms"/>
     ```

6. **RadioButton & RadioGroup (`RadioButton`)**  
   - Used for single selection from multiple options.  
   - Example:
     ```xml
     <RadioGroup
         android:layout_width="wrap_content"
         android:layout_height="wrap_content">
         <RadioButton android:text="Male"/>
         <RadioButton android:text="Female"/>
     </RadioGroup>
     ```

These form widgets **enhance user interaction** and are used in forms like **login, signup, and surveys**.

---

### **Q2: Explain Layouts in Android and their types with examples.**  
**Answer:**  
Layouts define the **structure** and **arrangement** of UI components in an Android application.  

#### **Types of Layouts in Android:**  

1. **LinearLayout** (Arranges UI elements in a row/column)  
   ```xml
   <LinearLayout
       android:orientation="vertical"
       android:layout_width="match_parent"
       android:layout_height="match_parent">
       <TextView android:text="Hello World"/>
   </LinearLayout>
   ```

2. **RelativeLayout** (Positions elements relative to each other)  
   ```xml
   <RelativeLayout>
       <TextView android:id="@+id/text1" android:text="Label"/>
       <EditText android:layout_below="@id/text1"/>
   </RelativeLayout>
   ```

3. **ConstraintLayout** (Flexible layout for complex UI designs)  
   ```xml
   <androidx.constraintlayout.widget.ConstraintLayout>
       <Button
           android:text="Click"
           app:layout_constraintTop_toTopOf="parent"/>
   </androidx.constraintlayout.widget.ConstraintLayout>
   ```

4. **FrameLayout** (Single UI element per frame, used for overlays)  
5. **GridLayout** (Divides screen into equal-sized grids)  

Each layout serves a **specific purpose** in UI design.

---

### **Q3: Explain Menus and Dialogs in Android with examples.**  
**Answer:**  
#### **Menus in Android**  
Menus allow users to access **options and actions** in an app.  

1. **Options Menu** (Appears in the Action Bar)  
   ```xml
   <item android:id="@+id/settings" android:title="Settings"/>
   ```
   Java Code:
   ```java
   @Override
   public boolean onCreateOptionsMenu(Menu menu) {
       getMenuInflater().inflate(R.menu.menu_main, menu);
       return true;
   }
   ```

2. **Context Menu** (Appears on long press)  
3. **Popup Menu** (Temporary floating menu)  

#### **Dialogs in Android**  
Dialogs are **small pop-ups** for alerts and user interactions.  

1. **AlertDialog**
   ```java
   new AlertDialog.Builder(this)
       .setTitle("Warning")
       .setMessage("Are you sure?")
       .setPositiveButton("Yes", null)
       .show();
   ```

2. **ProgressDialog** (Shows loading progress)  
3. **Custom Dialogs** (User-defined designs)  

Menus and dialogs **improve user experience** by offering structured navigation.

---

### **Q4: What is SQLite? Explain its features and advantages in Android.**  
**Answer:**  
SQLite is a **lightweight, embedded database** used in Android apps for storing structured data.  

#### **Features of SQLite in Android:**  
1. **Self-contained & serverless** (No external dependency)  
2. **Small size** (Less than 1MB)  
3. **ACID-compliant transactions**  
4. **Fast read/write operations**  
5. **Uses SQL queries**  

#### **Advantages of SQLite:**  
- **Efficient for mobile apps**  
- **Works offline**  
- **Easy to integrate with Android apps**  

Example:  
```java
SQLiteDatabase db = openOrCreateDatabase("MyDB", MODE_PRIVATE, null);
db.execSQL("CREATE TABLE users (id INTEGER, name TEXT)");
db.execSQL("INSERT INTO users VALUES (1, 'Alice')");
```

SQLite is **widely used** in Android apps like **messaging, offline storage, and login systems**.

---

### **Q5: How to connect an Android app with an SQLite database? Provide an example.**  
**Answer:**  
To connect an Android app with SQLite, follow these steps:  

1. **Create a Database Helper Class:**  
   ```java
   public class DatabaseHelper extends SQLiteOpenHelper {
       public DatabaseHelper(Context context) {
           super(context, "MyDB", null, 1);
       }
       @Override
       public void onCreate(SQLiteDatabase db) {
           db.execSQL("CREATE TABLE users(id INTEGER PRIMARY KEY, name TEXT)");
       }
       @Override
       public void onUpgrade(SQLiteDatabase db, int oldVersion, int newVersion) {
           db.execSQL("DROP TABLE IF EXISTS users");
           onCreate(db);
       }
   }
   ```

2. **Insert Data into the Database:**  
   ```java
   SQLiteDatabase db = new DatabaseHelper(this).getWritableDatabase();
   ContentValues values = new ContentValues();
   values.put("name", "John");
   db.insert("users", null, values);
   ```

3. **Retrieve Data from the Database:**  
   ```java
   Cursor cursor = db.rawQuery("SELECT * FROM users", null);
   while(cursor.moveToNext()) {
       Log.d("DB", "User: " + cursor.getString(1));
   }
   ```

This helps in **storing and retrieving user data** efficiently.

---
### **📌 7 Medium-Answer Questions (3 Marks Each)**  

---

### **Q1: What is the purpose of a Spinner in Android?**  
**Answer:**  
A **Spinner** in Android is used as a dropdown list that allows users to **select one item** from multiple predefined options. It is similar to a **ComboBox** in other programming languages.  

#### **Example of Spinner in XML:**  
```xml
<Spinner
    android:id="@+id/spinner"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"/>
```
#### **Example of Spinner in Java:**  
```java
Spinner spinner = findViewById(R.id.spinner);
ArrayAdapter<String> adapter = new ArrayAdapter<>(this, android.R.layout.simple_spinner_item, new String[]{"Option 1", "Option 2"});
spinner.setAdapter(adapter);
```

---

### **Q2: How do you create a Toggle Button in Android?**  
**Answer:**  
A **ToggleButton** is used to switch between **two states** (ON/OFF).  

#### **Example of ToggleButton in XML:**  
```xml
<ToggleButton
    android:id="@+id/toggleButton"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:textOn="ON"
    android:textOff="OFF"/>
```

#### **Example of ToggleButton in Java:**  
```java
ToggleButton toggleButton = findViewById(R.id.toggleButton);
toggleButton.setOnCheckedChangeListener((buttonView, isChecked) -> {
    if (isChecked) {
        Toast.makeText(this, "Toggle is ON", Toast.LENGTH_SHORT).show();
    } else {
        Toast.makeText(this, "Toggle is OFF", Toast.LENGTH_SHORT).show();
    }
});
```

---

### **Q3: What is ConstraintLayout?**  
**Answer:**  
**ConstraintLayout** is a flexible layout in Android that allows **positioning UI elements relative to other elements or the parent container**. It is more efficient than **RelativeLayout** and **LinearLayout** for complex UI designs.  

#### **Example of ConstraintLayout in XML:**  
```xml
<androidx.constraintlayout.widget.ConstraintLayout
    android:layout_width="match_parent"
    android:layout_height="match_parent">
    
    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Click Me"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintStart_toStartOf="parent"/>
</androidx.constraintlayout.widget.ConstraintLayout>
```

---

### **Q4: Explain the difference between AlertDialog and ProgressDialog.**  
**Answer:**  
| Feature | AlertDialog | ProgressDialog |
|---------|------------|---------------|
| **Purpose** | Used to show **alerts, confirmations, or messages** | Used to show **loading progress** |
| **Interaction** | Can have buttons (YES, NO, CANCEL) | Usually does not have buttons |
| **Usage Example** | "Are you sure you want to delete?" | "Loading, please wait..." |

#### **Example of AlertDialog:**  
```java
new AlertDialog.Builder(this)
    .setTitle("Delete")
    .setMessage("Are you sure?")
    .setPositiveButton("Yes", null)
    .setNegativeButton("No", null)
    .show();
```

#### **Example of ProgressDialog:**  
```java
ProgressDialog progressDialog = new ProgressDialog(this);
progressDialog.setMessage("Loading...");
progressDialog.show();
```

---

### **Q5: Why is SQLite used in Android?**  
**Answer:**  
SQLite is **used in Android apps** because:  
- It is **lightweight** (small database size).  
- It does **not require a separate server**.  
- It supports **SQL queries** for data management.  
- It provides **fast read/write operations**.  
- It works **offline** (no internet required).  

SQLite is ideal for apps requiring **local data storage**, such as **note-taking apps, messaging apps, and offline dictionaries**.

---

### **Q6: How do you insert data into an SQLite database?**  
**Answer:**  
To insert data into an **SQLite database** in Android, follow these steps:  

#### **Step 1: Create a Database Helper Class**  
```java
public class DatabaseHelper extends SQLiteOpenHelper {
    public DatabaseHelper(Context context) {
        super(context, "MyDB", null, 1);
    }
    @Override
    public void onCreate(SQLiteDatabase db) {
        db.execSQL("CREATE TABLE users(id INTEGER PRIMARY KEY, name TEXT)");
    }
    @Override
    public void onUpgrade(SQLiteDatabase db, int oldVersion, int newVersion) {
        db.execSQL("DROP TABLE IF EXISTS users");
        onCreate(db);
    }
}
```

#### **Step 2: Insert Data into the Database**  
```java
SQLiteDatabase db = new DatabaseHelper(this).getWritableDatabase();
ContentValues values = new ContentValues();
values.put("name", "John Doe");
db.insert("users", null, values);
db.close();
```

---

### **Q7: Define SQLiteOpenHelper and its role.**  
**Answer:**  
`SQLiteOpenHelper` is a **helper class** in Android that helps manage SQLite databases.  

#### **Role of SQLiteOpenHelper:**  
- **Creates** and **upgrades** the database.  
- **Handles database versioning** automatically.  
- **Provides readable and writable database instances**.  

#### **Example of SQLiteOpenHelper:**  
```java
public class MyDatabaseHelper extends SQLiteOpenHelper {
    public MyDatabaseHelper(Context context) {
        super(context, "MyDB", null, 1);
    }
    @Override
    public void onCreate(SQLiteDatabase db) {
        db.execSQL("CREATE TABLE users (id INTEGER PRIMARY KEY, name TEXT)");
    }
    @Override
    public void onUpgrade(SQLiteDatabase db, int oldVersion, int newVersion) {
        db.execSQL("DROP TABLE IF EXISTS users");
        onCreate(db);
    }
}
```

---

## **📌 10 Short-Answer Questions (1 Mark Each)**  

---

### **Q1: What is a Form Widget in Android?**  
**Answer:** A Form Widget is a UI component like **EditText, Button, CheckBox, RadioButton, Spinner**, etc., used to **collect user input**.

---

### **Q2: What is the purpose of an EditText in Android?**  
**Answer:** `EditText` is used for **text input fields**, such as entering a **username, password, or email**.

---

### **Q3: What is the difference between RadioButton and CheckBox?**  
**Answer:**  
- `RadioButton`: Used for **single selection**.  
- `CheckBox`: Used for **multiple selections**.

---

### **Q4: Name any two types of Layouts in Android.**  
**Answer:**  
1. **LinearLayout**  
2. **ConstraintLayout**

---

### **Q5: What is the use of a Menu in Android?**  
**Answer:** A **Menu** provides a list of **options and actions** in an app (e.g., **Settings, Logout**).

---

### **Q6: What is the purpose of an AlertDialog?**  
**Answer:** `AlertDialog` is used to show **warnings, confirmations, or messages** (e.g., "Are you sure you want to delete?").

---

### **Q7: What is SQLite?**  
**Answer:** SQLite is a **lightweight, embedded database** used in Android for **storing structured data locally**.

---

### **Q8: How do you retrieve data from an SQLite database in Android?**  
**Answer:** Using an SQL query:  
```java
Cursor cursor = db.rawQuery("SELECT * FROM users", null);
```

---

### **Q9: What is an Intent in Android?**  
**Answer:** An **Intent** is used for **navigation** between activities or passing data.

---

### **Q10: What is an Activity in Android?**  
**Answer:** An **Activity** represents a **screen in an Android app** where the user interacts.

---
