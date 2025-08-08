# SmartPick-Optimized-Warehouse-Order-Picking-System
## Short Description
SmartPick is a warehouse automation project that helps speed up the order-picking process by locating items in the warehouse and generating an optimized picking path to minimize travel time.

The system uses item location metadata (Aisle, Row, Column) and a path optimization algorithm to provide step-by-step instructions for warehouse workers.

## 🚀 Features
- 📍 Item Location Mapping – Finds the location of each requested item.
- 🧠 Path Optimization – Decides the most efficient sequence to pick items.
- 🖥 Easy to Integrate – Works with basic datasets of items and their locations.
- 📊 Workflow Visualization – Can be extended to show animations or diagrams.

 ## 📂 Tech Stack
- Python – Core logic & algorithms
- Pandas – Dataset handling
- Custom Path Optimization Algorithm – Minimizes travel time
- (Optional) Matplotlib / Animation – For visual workflows

  ## 📋 Example Output
  ```
  Laptop is in Electronics at Aisle C, Row 5, Column 2.  
  Tape is in Stationery at Aisle B, Row 3, Column 8.  
  Wireless Earbuds is in Electronics at Aisle C, Row 3, Column 6.  

  Optimized Path:  
  1. Pick 'Laptop' from Aisle C, Row 5, Column 2  
  2. Pick 'Wireless Earbuds' from Aisle C, Row 3, Column 6  
  3. Pick 'Tape' from Aisle B, Row 3, Column 8  

  ```


## 🛠 How It Works
- Input Order – User provides a list of items to pick.
- Locate Items – System searches the dataset for aisle, row, and column.
- Optimize Path – Algorithm calculates the shortest route.
- Output Steps – Displays the sequence in which items should be picked.



  
