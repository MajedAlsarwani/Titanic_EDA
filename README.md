
# 🚢 Titanic EDA 

This project is a data exploration dashboard built with **Streamlit** and **Plotly** to visualize insights from the Titanic dataset. The dashboard allows interactive filtering, dynamic visualizations, and maps the Titanic's historical route.

---

## Cleanning

- **Key findings**
  - Missing Values Identified:

      Age: 263 missing values (20% of data)

      Survived: 22 missing values

      Fare: 1 missing value

      Embarked: 2 missing values

  - Data cleanning
      Droping unnecessary columns (Unnamed 0, ticket number, cabin)
      
      Filling NA values in Age in range 18 to 40 becaues of age distribution was high in between

      droping rows in (Survived, Fare, Embarked)

---

---

## 📌 Features

- **Interactive Filters**  
  Filter passengers by gender, survival status, ticket class, and age range from the sidebar.

- **Passenger Summary Metrics**  
  Displays total passengers, average age, and average fare for selected filters.

- **📍 Route Map**  
  Shows the Titanic's journey using Plotly map visualization:
  - Belfast (Construction)
  - Southampton (Start)
  - Cherbourg
  - Queenstown
  - Iceberg Warning Zone
  - Wreck Site
  - New York City (Destination)

- **📊 Visual Insights**  
  - Gender Distribution (Pink for Female, Blue for Male)
  - Survival Rates (Green = Survived, Red = Died)
  - Passenger Class Distribution
  - Fare by Class and Gender
  - Age Distribution by Gender
  - Survival by Class and Gender
  - Survival by Family Size
  - Passenger Count by Embarkation Port
  - Correlation Heatmap of Numeric Features

- **ScreenShots**
  <img width="1728" alt="Screenshot 1446-11-11 at 7 06 25 PM" src="https://github.com/user-attachments/assets/a0716fb4-7abf-49c1-8526-208b8c2864bb" />
<img width="1728" alt="Screenshot 1446-11-11 at 7 06 46 PM" src="https://github.com/user-attachments/assets/0988160b-c436-4aee-b9d8-cd6114f27df1" />
<img width="1728" alt="Screenshot 1446-11-11 at 7 07 08 PM" src="https://github.com/user-attachments/assets/b8447c18-ae45-48eb-b7e4-8e5d96412048" />
<img width="1728" alt="Screenshot 1446-11-11 at 7 07 27 PM" src="https://github.com/user-attachments/assets/c06a9846-1539-45fa-8388-69163b5bcacb" />
<img width="1728" alt="Screenshot 1446-11-11 at 7 07 44 PM" src="https://github.com/user-attachments/assets/6d6bf846-76b1-42c9-aa4d-ac8eb04b540d" />


---

## 🧰 Tech Stack

- Python
- Streamlit
- Pandas
- Numpy
- Plotly

---

## 🚀 Getting Started

1. **Clone this repository:**
   ```bash
   git clone 
   cd titanic-eda
   ```

2. **Install the required libraries:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app:**
   ```bash
   streamlit run app.py
   ```

---

## 📁 Project Structure

```
📦 titanic-eda
├── app.py                # Main Streamlit app
├── titanic_cleanning     # File for cleanning
├── Data                  # Dataset folder
├── README.md             # Project documentation
└── requirements.txt      # Dependencies list
```

---

## 🧠 Key Insights

- Majority of passengers were in 3rd class.
- Women had a significantly higher survival rate than men.
- 1st class women and children had the highest survival rates.
- Most passengers boarded from Southampton.
- Fare prices increase with ticket class.
- Survival rate is correlated with gender, class, and age.
- If you were alone you had highest survival rate


