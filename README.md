## Universal Bank and Ebay Auction Dataset Analysis

## Overview

This Python code includes Exploratory Data Analysis (EDA) for both the Universal Bank and Ebay Auction datasets, followed by the implementation of K-NN and classification models on the Universal Bank dataset. The summary of findings is provided below.

### Universal Bank Dataset

1. **K-NN and Classification Models:**
   - K-NN Model: Achieved a high accuracy of 97% for k=3.
   - Decision Tree Model: Demonstrated poor accuracy for true positives.

2. **Decision Between K-NN and Classification Tree:**
   - Decision Tree: Poor accuracy for true positives.
   - K-NN: High accuracy (97% for k=3).
   - Recommendation: K-NN is preferred due to its superior accuracy, even though it can be computationally expensive for new data.

### Ebay Auction Dataset

1. **Classification Tree Analysis:**
   - Recommendations based on opening and closing price:
     - If openPrice is between 0.94 and 3.615 and closingPrice is less than 3.645, it will yield a competitive bid.
   - Recommendations for a 2-day auction:
     - If the opening price is less than 0.88, all categories from 1 to 12 will yield in a competitive auction.
