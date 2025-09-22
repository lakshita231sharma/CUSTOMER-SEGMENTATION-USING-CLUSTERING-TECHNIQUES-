# Inventory Optimization Project

This project demonstrates how to generate an inventory dataset and apply **optimization techniques** to determine the optimal order quantities for multiple products.

## 📌 Project Overview
The project includes:
1. **Dataset Generation**  
   - Randomly generates weekly demand, current inventory, max capacity, holding cost, order cost, and budget for 20 products.  
   - Saves the dataset as `inventory_dataset.csv`.

2. **Optimization Model**  
   - Uses `scipy.optimize.least_squares` to solve for order quantities.  
   - Ensures constraints:
     - Demand balance
     - Storage capacity
     - Budget/cost limits

3. **Results**  
   - Prints optimal order quantities for each product.

---

## 🛠️ Technologies Used
- Python 3  
- NumPy  
- Pandas  
- SciPy  

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/inventory-optimization.git
   cd inventory-optimization
