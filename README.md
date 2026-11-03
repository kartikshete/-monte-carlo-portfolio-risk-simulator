📊 Monte Carlo Portfolio Risk Simulator

📌 Project Overview

The Monte Carlo Portfolio Risk Simulator is a Python-based project that uses Monte Carlo simulation to analyze investment portfolio risk.

It simulates 10,000 one-year investment paths for a portfolio containing four different assets and estimates portfolio volatility and 95% Value at Risk (VaR).

🎯 Objectives

* Simulate 10,000 portfolio investment paths.
* Generate daily asset returns using NumPy.
* Calculate portfolio returns using equal asset weights.
* Estimate annual portfolio volatility.
* Calculate 95% Value at Risk (VaR).
* Visualize portfolio return distributions and simulated paths.

🛠️ Technologies Used

* Python
* NumPy
* Matplotlib
* Jupyter Notebook

📈 Simulation Details

Parameter.                  Value

Number of simulations.      10,000

Investment period.         1 year

Trading days               252

Number of assets.          4

Portfolio allocation.       25% each

Confidence level.           95%

💻 Methodology

1. Asset Configuration

Four assets are configured with different expected annual returns and volatility levels.

2. Return Simulation

NumPy’s np.random.normal() generates simulated daily returns for all four assets.

3. Portfolio Calculation

Portfolio returns are calculated using matrix multiplication and equal asset weights.

4. Portfolio Paths

np.log1p() and np.exp() are used to calculate cumulative portfolio growth.

5. Risk Analysis

The project calculates:

* Annual Portfolio Volatility
* 95% Value at Risk (VaR)
* Expected Annual Return

6. Data Visualization

Matplotlib generates:

* Portfolio return distribution histogram.
* Monte Carlo simulated portfolio paths.
* 95% VaR threshold visualization.

🚀 How to Run

1. Clone this repository:
   git clone https://github.com/YOUR_USERNAME/monte-carlo-portfolio-risk-simulator.git
   

2. Navigate to the project folder:
   cd monte-carlo-portfolio-risk-simulator
   
   3. Install dependencies:
      pip install numpy matplotlib notebook
      4. Launch Jupyter Notebook:
         jupyter notebook
         5. Open the notebook and run all cells.

📊 Expected Output

The project generates:

* 10,000 simulated one-year portfolio paths.
* Portfolio return distribution histogram.
* Annual portfolio volatility.
* 95% Value at Risk estimation.

⚠️ Assumptions and Limitations

* Asset returns follow a normal distribution.
* Assets are assumed to have independent returns.
* Portfolio weights remain equally distributed.
* Historical market behavior is not incorporated.

👨‍💻 Author

Kartik Shete

B.Tech – Computer and Information Sciences

GitHub: kartikshete⁠￼

LinkedIn: Kartik Shete⁠￼

⸻

⭐ If you find this project useful, consider giving the repository a star!
      
