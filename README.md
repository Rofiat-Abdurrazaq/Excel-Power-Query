Do you still believe Excel is just a basic spreadsheet tool for simple calculations and nothing more?🤔
![image](https://github.com/user-attachments/assets/f391c80f-4f5c-478e-9646-fe197ed592ce)

What if I told you that Excel is a powerhouse with advanced features that transform Excel from a basic tool into a versatile solution for complex data management? Power Query, pivot tables, charting tools, and other functions make Excel a game-changer for organizing, analyzing, and visualizing data effortlessly. 
In this post, I will debunk the myth about Excel's capabilities. Whether you are a beginner or an experienced data analyst, Power Query provides intuitive tools to clean, transform, and structure data with remarkable ease. By the end, you'll see how Excel can become your go-to tool for any data-driven task.
RAW DATA
The dataset for this project is a tab-delimited CSV file that needed to be structured. Below is a screenshot of the raw data before cleaning.
The tool used for this task is Power Query (a hidden gem in Microsoft Excel), which makes data structuring seamless. However, as evident in the raw data, the challenges included inconsistent formatting, lack of a clear table structure, and incoherent values.

CHALLENGES
One major hurdle was working with Power Query and a CSV file. While the functions worked perfectly during the process, I encountered a frustrating issue: saving and closing the document disconnected the query from the data source leaving just the final result.
Funny😁, I had to redo this project five times😱! Not because I could not achieve the result, but because I had not converted the CSV file into an Excel workbook (.xlsx) before starting.
Lesson learned📝: Always convert your file to .xlsx before diving into Power Query if you want to maintain connections and edits.

DATA EXPLORATION AND CLEANING
Let's dive into how I transformed the messy dataset into a clean, structured table.
Step 1: Load the data
Start by opening an Excel Workbook (.xlsx). On the Ribbon, navigate to "Data → Get & Transform Data".
From here, the next step depends on your data source (location of your data). You can choose from options like "From Table/Range, From web source, From Text/CSV" among others.
For this project, I selected "From Table/Range" since the document was opened directly in Excel. This action launches Power Query, where the real magic happens.
Step 2: Transforming data
The beauty of Power Query is its flexibility. There is no fixed way to play your data as long as you have a goal. Here are some of the key transformations I used during this project.

Merging Columns: Combine columns with related or similar values to streamline the dataset. For instance, some participants' first names ended up in the 7th column due to splitting by delimiters, but they were meant to be in the "first_name" column. This function made the correction possible.
Replace Values: Corrected incorrect or inconsistent values using this simple find-and-replace function.
Trimmed Text: Removed unnecessary spaces between text entries for a cleaner look. For instance " John " was corrected to "John" to ensure proper alignment.
Split Column by Delimiter: Used to separate values within a column based on a specific delimiter and in this case was tab as well as splitting numbers from letters in the same column.
Changed Type: Adjusted the data types of columns to suit the requirements (e.g., numbers, text, or dates).
