# Administrative Geocoding

A simple Python tool that extracts administrative regions such as province, city, district, and sub-district directly from raw address data in Excel files.  
Perfect for anyone who wants to clean and validate address data quickly without manual checking.

## 🚀 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Google Maps API](https://img.shields.io/badge/Google_Maps_API-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

## 🧩 What You Can Do

- Extract province, city, district, and sub-district from raw text addresses.  
- Process hundreds of rows in Excel automatically.  
- Use your preferred API (Google Maps or OpenAI).  
- Add clean results into new columns without changing the file structure.  
- Handle API errors safely and efficiently.

## 💡 Why It’s Useful

- You don’t have to check addresses manually.  
- Makes location data consistent and ready for analysis.  
- Saves hours in cleaning and validation work.  
- Great for operations, data analysts, and developers working with regional data.

## 📊 Example Output

**Before**

| Store Name | Address | Area | City |
|-------------|----------|------|------|
| Alfamart Tayu | Jl. Raya Tayu No.15, Jepara | Pati | Jepara |
| Indomaret Kudus | Jl. A. Yani No.8, Kudus | Kudus | Kudus |

**After**

| Store Name | Address | Area | City | Province | District | SubDistrict |
|-------------|----------|------|------|-----------|-----------|--------------|
| Alfamart Tayu | Jl. Raya Tayu No.15, Jepara | Pati | Jepara | Central Java | Jepara | Tayu |
| Indomaret Kudus | Jl. A. Yani No.8, Kudus | Kudus | Kudus | Central Java | Kudus | Jati |

## ⚙️ How It Works

1. Upload an Excel file with address data.  
2. The script reads the address column and calls the API.  
3. The API returns structured administrative information.  
4. The results are added to new columns and saved back to Excel.

## 🎯 Project Focus

Improve the accuracy of regional data from raw addresses.  
Reduce inconsistencies between area and city names in datasets.  
Make location-based analysis faster and more reliable.
