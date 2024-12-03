<h1> [AWS SaaS Company Sales Transaction] </h1>

## 1. Project Overview
This project analyzes business data to extract insights, improve decision-making, and identify key trends. The primary focus is to optimizing profit transaction in Finance Industry. 

Key Objectives:
- Objective 1: Mengetahui faktor-faktor yang mempengaruhi keuntungan penjualan lisensi platform Amazon Website Services pada industri keuangan.


## 2. Data Sources
- [Dataset 1](https://ee-assets-prod-us-east-1.s3.amazonaws.com/modules/337d5d05acc64a6fa37bcba6b921071c/v1/SaaS-Sales.csv) - Data terdiri dari 9994 transaksi pembelian lisensi produk dari tahun 2020 sampai 2023. Region yang menggunakan lisensi dari AWS dari EMEA, AMER, APJ.

## 3. Technologies Used
- Programming Language: Python (e.g., Pandas, NumPy)
- Visualization: Matplotlib, Seaborn.
- Interactive Dashboard: Tableau
- Version Control: Git
- Others: Jupyter Notebook

## 4. Project Structure

```
├── README.md          <- The top-level README for developers using this project.
|
├── data
│   ├── raw            <- Data from third party sources.
│   └── cleaned        <- The data that has been cleaned.
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── reports            <- Generated analysis as PDF
|   ├── slide          <- Generated PDF
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── src                <- Source code for use in this project.

```

## 5. Summary of Finding
### 5.1 Business Insight
Di Industri Finance, faktor yang memiliki hubungan positif dengan profit adalah jumlah penjualan. Region customer juga mempengaruhi profit dalam hal ini. Tetapi, terjadi hal sebaliknya pada diskon. Diskon memiliki hubungan negatif dengan profit. Semakin jumlah penjualan meningkat, maka profit juga meningkat. Namun, diskon penjualan meningkat, maka profit akan menurun. 
### 5.2 Actionable Recommendation
Rekomendasi yang dapat diberikan : <br> 
Jika penyedia platform atau AWS ingin penjualannya untuk setiap segment meningkat dan setiap industri seimbang (atau lebih naik) labanya, disarankan untuk memberikan diskon penjualan kepada customer atau pembeli di bawah sama dengan dari 20 persen. Sebab, dengan diskon yang rendah, laba yang diperoleh semakin tinggi. Diikuti dengan harga jual yang ditawarkan oleh penyedia platform atau AWS. 

## 6. Contact
- Name: Ratih Budi Setyorini
- Email: ratih.budi97@gmail.com
- LinkedIn: https://linkedin.com/in/ratih-budi-setyorini
- Tableu public : 