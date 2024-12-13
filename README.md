Do you still believe Excel is just a basic spreadsheet tool for simple calculations and nothing more?🤔
![image](https://github.com/user-attachments/assets/f391c80f-4f5c-478e-9646-fe197ed592ce)

What if I told you that Excel is a powerhouse with advanced features that transform Excel from a basic tool into a versatile solution for complex data management? Power Query, pivot tables, charting tools, and other functions make Excel a game-changer for organizing, analyzing, and visualizing data effortlessly. 

CHALLENGES
One major hurdle was working with Power Query and a CSV file. While the functions worked perfectly during the process, I encountered a frustrating issue: saving and closing the document disconnected the query from the data source leaving just the final result.

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

CONCLUSION.

Voila! With just a few simple but powerful steps, our once messy dataset is now clean, structured, and ready for analysis whether it is for visualization, reporting, or any other purpose. I hope this post has taught you a trick or two and shifted your perception of Excel, inspiring you to explore its full potential. It is far more than just a basic tool for calculations, it is a true powerhouse for tackling complex data challenges with ease.

Please feel free to reach out if you face any challenges.
