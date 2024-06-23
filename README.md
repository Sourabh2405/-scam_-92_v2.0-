
# scam'92_v2.0 SoC 2024 Project ID 24

This readme is for assignment 1, where I implemeted a LSTM model combined with other layers to train a stock data of Amazon from date 16-05-1997
till 21-06-2024 (total of 6818 entries)

## Author: Sourabh Chouhan
## Roll. No: 210010062



## Model Architecture
**Conv1D Layer**:
Extracts local features from the input time series.

Parameters: 64 filters, kernel size of 3, causal padding, ReLU activation.

**LSTM Layers:**
Captures temporal dependencies.

Layer 1: 64 units, returns full sequences.

Layer 2: 64 units, returns the final output.


**Dense Layers:**
Transforms the output to the desired shape.

*Dense 1:* 30 units, ReLU activation.

*Dense 2:* 10 units, ReLU activation.

*Output Layer:* 1 unit.

**Lambda Layer:**
Scales the output by 400.

## Libraries used
Numpy, Matplotlib, pandas

## Datasource
[![portfolio](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAA8FBMVEVeAc1dActaAcVYAcFXAb5WAbxUAbhTAbVRALFPAK1NAKlLAKRIAKyKyVFJAKFVN6Oe8wqIxFJIAJ1OALtXK7BGALFiZJKl/wB7pWo6AKmOz01fU6BzkXpoeIStotBUGbSZ6CiQ1EVxh4aEulxWSZXa1un///8zAJhGAJldR6cwALBgXpaT3DhOFKjz8vdpb5Xm5e1PLaBsT7JDAJPIweJeNLB1mHOPf8Lc3Op7ZLkgAJq0rNQaAIsyAIhBAI9AAIw+AIg8AINXO5S8udBIIp19b66Cdqqgl74hAHo5AH2rpMdxXqGAbrOfksNCIoVmTKYUy/OsAAABhklEQVR4AW3RBXYDMQwEUIeZs2EGhbehtmFmvP9tOvI+l+exv0mS4JhMJrPZbLFYrTabzW53OJxOp8vlcjNBlCmSBvz/GMjtEf8f84I8wH+P+bwwv/h2zK6OBYIhr8fvDwtJ0iJR45wWiyeSbGEB4xthqXhac8Ey8WwyBwOqK/OFYime1VxaOV5JVqkGqwtJjkgjXm5qrXhCaxfCHZ30WrherwvDXuKZZq7r7QXjqWSfCAgbCDZ7Jh5rDrH06n9LvpOBg8FAoDZHpNDQRsQZT6YkcTZglHV78zoZGZGB88FgsRBOtj59j0TYUnDZSfqLMKALWB39SnW+XC5XwhiOv6YymHOkAdk8spVcN1eAG5lWa/GNAg2QtFVlAwOy1cK4cDbdzha4EJeuKL1GBB+r0Y62REOiPVFap8Oxe4KdBcxfm3ar+q47vIy6x0t3dB1t06DzWcjXenS7k769VO+6vunSgR4gYJjxSXhN5nRanU7n01kh/3/+rQDkrBCEKIMoA/6qW5LKB+nIZaQqRO4KAAAAAElFTkSuQmCC)](https://finance.yahoo.com/quote/AMZN/history/)YahooFinance Amazon stock data

**train data size:** 6500

**test data size:** 318

**Numner of Epochs:** 100

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/Sourabh2405/-scam_-92_v2.0-.git)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sourabh-chouhan-252510241/)



