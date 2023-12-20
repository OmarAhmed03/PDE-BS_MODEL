# Option Pricing Modeling and Analysis with Black-Scholes Equation and ANN 

**Exploring option pricing methodologies through a deep learning approach and comparing it with the classic Black-Scholes model.**

## Overview

[Insert a visually engaging image or animation showcasing option pricing concepts or models]

This project delves into the realm of option pricing by combining the traditional Black-Scholes model with the power of artificial neural networks (ANNs). It aims to:

* Develop an ANN model for option price prediction.
* Conduct a comparative analysis between the ANN model and the Black-Scholes model.
* Construct a web application for practical price prediction.

## Key Components

**1. Data Collection and Analysis**

* **Dataset:**
    * Source: Yahoo Finance API
    * Number of records: 35,727
    * Features:
        * `contractSymbol` (object)
        * `lastTradeDate` (datetime64[ns])
        * `strike` (float64)
        * `lastPrice` (float64)
        * `impliedVolatility` (float64)
        * `expiry_date` (datetime64[ns])
        * `symbol` (object)
        * `dates diff` (int64)
        * `Stock price` (float64)
    * Memory usage: 2.5+ MB
    * Location: `Dataset` folder
    * Preprocessing and analysis details: `Data_collection_analysis` file
    * **Data description:**

| Feature       | Count | Mean       | Std Dev    | Min        | 25%       | 50%       | 75%       | Max        |
|----------------|-------|------------|------------|------------|-----------|-----------|-----------|------------|
| strike         | 35727  | 163.558230 | 380.722103 | 0.350000   | 20.000000 | 50.000000 | 155.000000 | 5400.000000 |
| lastPrice      | 35727  | 33.963996  | 100.049276 | 0.010000   | 0.440000   | 4.400000  | 20.150000  | 1499.750000 |
| impliedVolatility | 35727  | 0.165873  | 0.697095  | 0.000000   | 0.000010   | 0.000010  | 0.125009  | 39.875004  |
| dates diff     | 35727  | 187.674280 | 234.796544 | 2.000000   | 23.000000  | 65.000000  | 262.000000 | 967.000000 |
| Stock price    | 35727  | 115.886382 | 135.571782 | 0.860300   | 19.219999 | 49.340000  | 148.839996 | 504.045685 |

   ![Histogram of Option Prices](images/option_price_hist.png)

* **Explanation:** This histogram visualizes the distribution of option prices in the dataset

    

**2. ANN Model Development**

* **Architecture and training:** (Provide details, potentially with a visual representation of the model architecture)
* **Performance evaluation:** (Include key metrics, presented visually using charts or graphs)

**3. Comparative Analysis**

* **ANN model vs. Black-Scholes model:** (Highlight insights and findings, potentially using a table or graph to compare results)

**4. Web Application**

* **Functionality:** Option price prediction
* **Code:** `web_app` folder
* **Instructions:** (Guide users on how to run the app, including visual examples if applicable)

## Getting Started

1. Clone this repository.
2. Install required libraries: (List dependencies)
3. Explore the code and data.
4. Run the web application: (Provide instructions)

## Contributing

We welcome contributions! Please refer to the `CONTRIBUTING.md` file for guidelines.

**Additional Information**

* (Insert any relevant links, citations, or further details)

## Visuals

* (Consider incorporating additional images or diagrams to illustrate key concepts or results)
