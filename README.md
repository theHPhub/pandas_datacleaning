**Hotel Bookings Data Cleaning – Jupyter Notebook**
**📄 Project Overview**

This project focuses on cleaning and organizing a sample hotel bookings dataset. The dataset was sourced online and contains basic booking information such as booking date, company, guest name, and room number.
The goal was to prepare the data for further analysis by removing inconsistencies, handling missing values, and clearly labeling each record.

**🧹 Data Cleaning Steps**

Removed Null Values
Used Pandas and NumPy to drop rows containing missing or incomplete information.

Created an “Actual Category” Column
Added a new text column to clearly indicate the booking category (e.g., room type) or other relevant classification.

Filtered Unwanted Rows
Eliminated irrelevant or noisy data entries to ensure the dataset reflects valid hotel booking records.

**📊 Dataset Columns**

After cleaning, the dataset includes:

Date – Booking or check-in date

Company – Travel agency or corporate client name

Person Name – Guest’s name

Room Number – Allocated or requested room

Actual Category (New) – Custom label describing the booking category or room type

**🛠️ Tools & Libraries**

**Python 3**

**Pandas**

**NumPy**

**Jupyter Notebook (.ipynb) – Edited and executed in Visual Studio Code**

**🚀 How to Run**

Clone or download this repository.

Install dependencies:

pip install pandas numpy jupyter


Open the .ipynb file in VS Code (with the Jupyter extension) or in a browser-based Jupyter environment.

Run the cells sequentially to reproduce the cleaning steps or adapt them for your dataset.

**📈 Possible Next Steps**

Add visualizations (e.g., booking trends over time)

Automate anomaly or outlier detection

Integrate additional attributes (e.g., price, stay duration, customer type)
