# Bank Marketing: Find Good Customers with Data Mining 🎯

**Project Goal:** I want to make a computer program (a model) to find bank customers who will say 'yes' to a term deposit. This helps the bank call fewer people and save money.

## 📈 Key Results (Important Numbers)

| What I Looked At | Result (WEKA / Python) | What This Means for Business |
| :--- | :--- | :--- |
| **Best Success Rate** | **[Your Success Rate or Accuracy]** (e.g., 90.7%) | The program can make **[Your Best Model]** better. |
| **Main Group (Cluster)** | **[Group Details]** (e.g., Age 40-55, Worker, Never called) | The bank must call these people in the next campaign. |
| **Important Rule** | `{euribor3m > 4.5, cons.price.idx > 93.9} -> y=no` | The economy is important. Bad economy means people say 'no'. |

*

[Image of Important Graph]
*

## 🛠️ Tools I Used

I did this project in two steps:

1.  **First Look (WEKA + OpenRefine):** I used this for fast cleaning and simple models (like trees and groups).
2.  **Code that Works Always (Python/Jupyter):** I made the models again in Python so other people can use the code.

| What I Did | Tools I Used |
| :--- | :--- |
| **Cleaning Data** | OpenRefine, Pandas |
| **Prediction** | WEKA (J48), `scikit-learn` (Decision Tree, Random Forest) |
| **Making Groups** | WEKA (K-Means), `scikit-learn` (KMeans) |

## ⚙️ How to Use This Project

1.  **Get the Code:**
    ```bash
    git clone [your_repo_link]
    cd bank-marketing-data-mining
    ```
2.  **Get the Data:**
    Put the original CSV file (`bank-additional-full.csv`) in the `data/` folder.
3.  **Install Tools (Dependencies):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # Mac/Linux
    venv\Scripts\activate     # Windows
    pip install -r requirements.txt
    ```
4.  **Start Working:**
    Open the files in `notebooks/` (start with `01`).
