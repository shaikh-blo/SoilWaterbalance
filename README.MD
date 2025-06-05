Soil Water Balance Calculator (Java)
This Java program simulates daily soil water balance for agricultural fields using rainfall data. It calculates runoff, crop water uptake, soil moisture, and percolation to groundwater based on soil type (deep/shallow).

Requirements
Java JDK 8 or later installed
Any text editor or IDE (e.g., VS Code, IntelliJ IDEA,Eclipse)
Terminal or Command Prompt access

📥 Input File: rainfall.csv


How to Run:-

✅ Steps to Run Java Program in Eclipse IDE
📦 1. Open Eclipse and Create a New Java Project
Open Eclipse IDE

Click on File → New → Java Project

Enter Project Name: SoilWaterBalance

Click Finish

📁 2. Add the Java Class File
Right-click on the src folder → New → Class

Name it: SoilWaterBalanceCSV

Check the checkbox public static void main(String[] args)

Click Finish

Paste the full Java code into the editor, replacing the default content.

📄 3. Add the rainfall.csv File
Right-click on your project folder (not src) → New → File

Name it: rainfall.csv

Paste your rainfall data into it (the data you shared earlier).

✅ Make sure the file is placed in the root of your project folder, not inside src.

▶️ 4. Run the Program
Right-click on SoilWaterBalanceCSV.java

Click Run As → Java Application

Eclipse will compile and run your program.

📤 5. Check Output CSV File
After the program runs:

The output file soil_water_balance_output.csv will be created in the project root folder (where rainfall.csv is).

You can open it in Excel or Notepad to view the table output.

✅ Run Java Program Using Notepad & CMD
📝 1. Write Your Java Code in Notepad
Open Notepad

Paste your full Java code (e.g., class name is SoilWaterBalanceCSV)

Save the file as:

Copy
Edit
SoilWaterBalanceCSV.java

📁 Save it in a folder, for example: C:\SoilProject

📄 2. Add Your rainfall.csv File
Open Notepad again

Paste your rainfall data

Save it in the same folder as:

Copy
Edit
rainfall.csv
🧪 3. Compile the Java Program
Open Command Prompt

Navigate to your folder using:

bash
Copy
Edit
cd C:\SoilProject
Compile the Java file:

nginx
Copy
Edit
javac SoilWaterBalanceCSV.java
✅ If no errors, it will create a file SoilWaterBalanceCSV.class

▶️ 4. Run the Program
Now run the program using:

nginx
Copy
Edit
java SoilWaterBalanceCSV
It will process the rainfall.csv and create an output file:

Copy
Edit
soil_water_balance_output.csv
📤 5. View Output
Open the soil_water_balance_output.csv file in Excel or Notepad

It will show data in table format with columns like:

css
Copy
Edit
Day, Rainfall in mm, Runoff + excess runoff in mm, Crop water uptake in mm, Soil moisture in mm, Percolation to 

