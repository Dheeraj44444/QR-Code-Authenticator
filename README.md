# QR Code Authenticator

## 📌 Overview
This project focuses on detecting counterfeit QR codes by distinguishing between:

- **First Prints** (Original QR Codes)
- **Second Prints** (Counterfeit QR Codes)

Using **Machine Learning (Random Forest)** and **Deep Learning (CNN)**, the system accurately classifies QR codes based on copy detection patterns (CDPs). The dataset consists of images of first prints (originals) and second prints (scanned & reprinted copies).

## 📂 Dataset
The dataset contains:

- **First Print**: Original QR codes with embedded copy detection patterns.
- **Second Print**: Counterfeit versions created by scanning and reprinting the original QR codes.

🔗 **[Download Dataset Here](#)** *((https://drive.google.com/drive/folders/1pPeWT1zntlKXnuY_yHmpI-ZzKl4nLgQS))*

💡 *Note: Ensure that the dataset is correctly placed in the project directory.*

## 🔧 Installation
To set up the environment, install the required dependencies:

```bash
pip install opencv-python numpy pandas scikit-learn tensorflow matplotlib seaborn joblib
```

## 🚀 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/qr-code-authentication.git
   cd qr-code-authentication
   ```
2. Place the dataset in the correct directory.
3. Run the model training and evaluation scripts.
4. Analyze the results to detect counterfeit QR codes.

