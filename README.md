# music-genre-classification

# Dataset Download Instructions

This guide explains how to download the dataset using the Kaggle API.

## Steps to Download the Dataset

1. **Create an API Key and Download `kaggle.json`:**  
   - Log in to your Kaggle account.
   - Go to your [Account Settings](https://www.kaggle.com/account).
   - Scroll to the **API** section and click **"Create New API Token"**.  
     This will download a file named `kaggle.json`.

2. **Configure Your Environment:**  
   Open your terminal and run the following commands:
   ```bash
   mkdir -p ~/.kaggle
   mv /path/to/downloaded/kaggle.json ~/.kaggle/
   chmod 600 ~/.kaggle/kaggle.json
   ```

3. **Download Dataset:**  
   ```bash
    bash dataset_downloader.sh
   ```

