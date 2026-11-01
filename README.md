# 📊 Regional Sales Analysis
### Mengubah Data Penjualan Menjadi Wawasan Bisnis yang Dapat Ditindaklanjuti

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Manipulation-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/EDA-Exploratory%20Analysis-orange?style=for-the-badge" />
</p>

<p align="center">
  <b>End-to-End Data Analytics Project</b><br>
  Python • Pandas • NumPy • Matplotlib • Seaborn • Power BI
</p>

---

## 📌 Project Overview

**Regional Sales Analysis** merupakan proyek Data Analytics yang bertujuan untuk mengevaluasi kinerja penjualan dan profitabilitas bisnis berdasarkan data historis selama lima tahun.

Analisis dilakukan dengan mengeksplorasi beberapa aspek utama, yaitu performa penjualan secara keseluruhan, produk, saluran penjualan, wilayah geografis, dan pelanggan.

Proyek ini mencakup proses pengolahan data, Exploratory Data Analysis (EDA), hingga pengembangan dashboard interaktif menggunakan Power BI untuk menghasilkan insight dan rekomendasi bisnis berbasis data.

**Project Objective:**
Mengidentifikasi faktor-faktor yang berkontribusi terhadap pendapatan dan profitabilitas, menemukan peluang pertumbuhan, serta mendukung pengambilan keputusan bisnis melalui analisis data.

## 🎯 Project Background

Dalam persaingan bisnis, perusahaan perlu memahami faktor-faktor yang mendorong pendapatan dan profitabilitas untuk mempertahankan pertumbuhan bisnis. Perbedaan kontribusi produk, saluran penjualan, wilayah, dan pelanggan dapat memengaruhi efektivitas strategi penjualan.

Melalui proyek ini, dilakukan analisis terhadap data penjualan untuk mengidentifikasi tren pendapatan, mengevaluasi profitabilitas, serta mengetahui kontribusi produk, saluran penjualan, wilayah, dan pelanggan. Hasil analisis divisualisasikan melalui Power BI untuk menghasilkan *actionable insights* dan rekomendasi guna mengoptimalkan strategi penjualan serta mendukung pengambilan keputusan bisnis.

## 🚨 Business Problem

Perusahaan membutuhkan pemahaman yang lebih menyeluruh mengenai kinerja penjualan untuk menentukan strategi bisnis yang tepat. Namun, tanpa analisis berdasarkan produk, channel, wilayah, dan pelanggan, perusahaan dapat mengalami kesulitan dalam:

- Mengidentifikasi tren dan perubahan pendapatan dari waktu ke waktu.
- Mengetahui produk yang memberikan kontribusi revenue dan profitabilitas terbaik.
- Mengevaluasi efektivitas masing-masing sales channel.
- Menentukan wilayah dengan kontribusi penjualan tertinggi maupun terendah.
- Mengidentifikasi pelanggan dengan kontribusi revenue dan profit margin yang menarik.
- Menemukan peluang untuk meningkatkan pendapatan dan profitabilitas.

**Business Objective:**

Bagaimana perusahaan dapat mengoptimalkan strategi penjualan dengan memahami kontribusi produk, channel, wilayah, dan pelanggan agar pertumbuhan revenue serta profitabilitas dapat ditingkatkan?

## 🔍 Key Business Questions

Analisis ini dirancang untuk menjawab beberapa pertanyaan bisnis berikut:

| No. | Key Business Questions |
|---|---|
| 01 | Bagaimana kinerja penjualan perusahaan berdasarkan total Revenue, Profit, Profit Margin, dan Orders? |
| 02 | Bagaimana tren pendapatan berubah dari waktu ke waktu dan apakah terdapat pola musiman? |
| 03 | Produk mana yang memberikan kontribusi Revenue terbesar dan produk mana yang memiliki Profit Margin tertinggi? |
| 04 | Sales channel mana yang memberikan kontribusi Revenue dan Profit terbesar? |
| 05 | Wilayah dan negara bagian mana yang memiliki kontribusi penjualan tertinggi? |
| 06 | Bagaimana perbedaan kinerja penjualan dan profitabilitas antarwilayah? |
| 07 | Siapa pelanggan dengan kontribusi Revenue terbesar dan bagaimana perbandingan profitabilitas antar pelanggan? |
| 08 | Strategi apa yang dapat diterapkan untuk mengoptimalkan penjualan dan meningkatkan profitabilitas? |

## 🛠️ Technology & Tools

### Programming & Data Analysis

| Technology | Usage |
|---|---|
| Python | Data analysis dan preprocessing |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |

### Business Intelligence

| Technology | Usage |
|---|---|
| Power BI | Interactive dashboard development |
| Power Query | Data transformation |
| Power BI Visuals | Reporting dan data storytelling |

### Supporting Tools

- Google Colab
- Microsoft Excel
- PowerPoint
- GitHub

## 📂 Dataset Overview

Dataset terdiri dari beberapa tabel yang digunakan untuk mendukung analisis penjualan.

```text
Sales
├── Orders
├── Customers
├── Products
├── States
├── Regions
├── Channels
└── Budget
```

Informasi yang digunakan dalam analisis meliputi:

**1. Order & Customer Information**
- Order Number
- Order Date
- Customer Name
- Channel
- Product Name

**2. Financial Information**
- Quantity
- Unit Price
- Revenue
- Cost
- Profit
- Profit Margin %

**3. Time Information**
- Order Month
- Order Month Number
- Order Month Name

**4. Geographic Information**
- State
- State Name
- US Region
- Latitude
- Longitude

**5. Planning Information**
- Budget 2017

## ⚙️ Data Preparation & Cleaning

Tahap Data Preparation dilakukan untuk memastikan data memiliki struktur yang konsisten dan siap digunakan dalam proses analisis.

Proses yang dilakukan meliputi:

- Restrukturisasi header.
- Konsolidasi dan penggabungan tabel.
- Menghapus kolom redundan.
- Standardisasi nama kolom.
- Penyesuaian tipe data.
- Pemilihan kolom kunci.
- Validasi data.

**Feature Engineering**

Membuat metrik bisnis yang diperlukan untuk analisis, antara lain:

```text
Profit
Profit Margin %
```

Selain itu, dilakukan pembuatan fitur kalender untuk mendukung analisis tren penjualan berdasarkan waktu.

Berdasarkan dokumentasi preprocessing proyek, tidak ditemukan missing values maupun baris duplikat setelah proses pembersihan data.

## 📊 Exploratory Data Analysis (EDA)

Exploratory Data Analysis dilakukan untuk memahami karakteristik data dan menemukan pola yang relevan dengan permasalahan bisnis.

Analisis mencakup:

- Sales Trend Analysis
- Product Performance Analysis
- Channel Performance Analysis
- Regional Performance Analysis
- Customer Analysis
- Profitability Analysis
- Seasonal Analysis
- Correlation Analysis

Tahap ini berfokus pada pemahaman terhadap apa yang terjadi dalam data, di mana performa tersebut terbentuk, serta faktor-faktor yang berpotensi memengaruhi hasil bisnis.

## 🧠 Key Insights & Business Implications

Berdasarkan hasil analisis dan visualisasi pada ketiga dashboard, diperoleh beberapa temuan utama berikut.

### 01. Overall Sales Performance

<text>**Key Insight:**</text>

Kinerja penjualan secara keseluruhan menunjukkan:

| KPI | Performance |
|---|---:|
| Total Revenue | $1.2 Billion |
| Total Profit | $461.8 Million |
| Profit Margin | 37.36% |
| Total Orders | 64K |

Tren pendapatan menunjukkan performa yang lebih tinggi pada bulan Mei dan Agustus, sedangkan Februari menjadi salah satu periode dengan pendapatan yang lebih rendah.

**Business Implication:**

Perusahaan perlu memperhatikan perubahan performa penjualan berdasarkan waktu untuk mengidentifikasi periode potensial dan periode yang membutuhkan strategi peningkatan penjualan.

### 02. Product Performance

**Key Insight:**

- Product 26 menghasilkan Revenue tertinggi sekitar $117M.
- Product 25 berada di posisi berikutnya dengan Revenue sekitar $109M.
- Product 13 menghasilkan Revenue sekitar $78M.
- Product 9 memiliki Profit Margin tertinggi sebesar 40.0%.

**Business Implication:**

Produk dengan Revenue tinggi berperan penting dalam menghasilkan pendapatan, sedangkan produk dengan Profit Margin tinggi menunjukkan potensi profitabilitas yang menarik. Keduanya perlu dievaluasi menggunakan strategi yang berbeda.

### 03. Sales Channel Performance

**Key Insight:**

Kontribusi Revenue berdasarkan sales channel:

| Sales Channel | Revenue | Contribution |
|---|---:|---:|
| Wholesale | $668.2M | 54.06% |
| Distributor | $387.14M | 31.32% |
| Export | $180.63M | 14.61% |

Export memiliki Profit Margin tertinggi sebesar 38.01%, sementara Wholesale menjadi kontributor Revenue terbesar.

**Business Implication:**

Wholesale merupakan channel utama dalam menghasilkan pendapatan. Di sisi lain, Export memiliki potensi untuk dikembangkan karena menunjukkan margin yang lebih tinggi.

### 04. Geographic Performance

**Key Insight:**

Kontribusi Revenue berdasarkan wilayah:

| Region | Revenue | Contribution |
|---|---:|---:|
| West | $372.1M | 30.1% |
| South | $335.1M | 27.1% |
| Midwest | $320.3M | 25.9% |
| Northeast | $208.4M | 16.9% |

West menjadi wilayah dengan kontribusi Revenue tertinggi. Pada tingkat negara bagian, California menghasilkan Revenue terbesar sekitar $228.79M.

**Business Implication:**

Wilayah West dan California merupakan pasar dengan kontribusi penjualan yang kuat. Sementara itu, Northeast dapat menjadi fokus evaluasi untuk menemukan peluang peningkatan performa regional.

### 05. Customer Performance

**Key Insight:**

- Aibox Company menjadi salah satu pelanggan dengan kontribusi Revenue tertinggi, sekitar $13M.
- State Ltd menghasilkan Revenue sekitar $12M.
- Neutrogena Ltd memiliki Profit Margin tertinggi sebesar 44.78%.
- Avamba Company memiliki Profit Margin sebesar 44.20%.

Temuan ini menunjukkan bahwa pelanggan dengan Revenue tertinggi tidak selalu memiliki Profit Margin tertinggi.

**Business Implication:**

Evaluasi pelanggan tidak cukup hanya berdasarkan besarnya Revenue. Perusahaan juga perlu mempertimbangkan Profit Margin untuk mengetahui pelanggan yang memberikan kontribusi keuntungan lebih baik.

## 💡 Business Recommendations

Berdasarkan Key Insights dan Business Implications, berikut rekomendasi yang dapat dipertimbangkan perusahaan.

### 01. Optimize Product Performance

Mempertahankan dan mengoptimalkan produk dengan kontribusi Revenue tinggi seperti Product 26 dan Product 25. Selain itu, mengevaluasi produk dengan Profit Margin tinggi untuk mengidentifikasi peluang peningkatan keuntungan.

### 02. Improve Sales Channel Strategy

Mempertahankan Wholesale sebagai channel utama penghasil Revenue serta mengeksplorasi peluang pengembangan Export karena memiliki Profit Margin tertinggi.

### 03. Strengthen Regional Market Strategy

Mempertahankan performa pasar di wilayah West dan menjadikan California sebagai salah satu benchmark. Perusahaan juga dapat mengevaluasi wilayah dengan kontribusi lebih rendah untuk menemukan peluang pertumbuhan.

### 04. Develop Customer Value Strategy

Melakukan evaluasi pelanggan berdasarkan Revenue dan Profit Margin, kemudian memprioritaskan:

- Customer Retention
- Customer Relationship Management
- Upselling
- Cross-selling

### 05. Improve Sales Planning

Menggunakan tren pendapatan bulanan sebagai dasar perencanaan penjualan, persediaan, dan campaign. Perusahaan dapat memperkuat strategi pada periode dengan performa lebih rendah serta mempersiapkan kebutuhan sebelum periode puncak.

### 06. Monitor Profitability

Melakukan pemantauan Revenue, Profit, dan Profit Margin secara berkala untuk mengevaluasi kinerja produk, channel, wilayah, dan pelanggan. Hal ini membantu perusahaan menjaga keseimbangan antara pertumbuhan pendapatan dan keuntungan.

## 📈 Power BI Dashboard

Hasil analisis divisualisasikan ke dalam tiga dashboard interaktif menggunakan Power BI. Setiap dashboard memiliki fokus analisis yang berbeda, tetapi saling melengkapi untuk memberikan gambaran menyeluruh mengenai kinerja penjualan.

### 01. Overall Sales Performance

Dashboard ini memberikan gambaran umum mengenai kinerja penjualan perusahaan.

Informasi yang ditampilkan:
- Total Revenue
- Total Profit
- Profit Margin
- Total Orders
- Monthly Sales Trend

### 02. Product & Sales Channel Performance

Dashboard ini berfokus pada evaluasi performa produk dan sales channel.

Informasi yang ditampilkan:
- Product Revenue
- Product Profitability
- Product Profit Margin
- Revenue by Sales Channel
- Profit by Sales Channel
- Channel Profit Margin

### 03. Geographic & Customer Performance

Dashboard ini memberikan informasi mengenai kontribusi penjualan berdasarkan wilayah dan pelanggan.

Informasi yang ditampilkan:
- Revenue by Region
- Revenue by State
- Regional Profit Margin
- Customer Revenue
- Customer Profit Margin
- Customer Performance Comparison

## 🖼️ Dashboard Preview

### 01. Overall Sales Performance

<p align="center">
  <img src="screenshots/dashboard-overview.png" width="95%">
</p>

### 02. Product & Sales Channel Performance

<p align="center">
  <img src="screenshots/product-channel-performance.png" width="95%">
</p>

### 03. Geographic & Customer Performance

<p align="center">
  <img src="screenshots/geographic-customer-performance.png" width="95%">
</p>

> Sesuaikan nama file gambar dengan nama screenshot yang digunakan di repository GitHub Anda.

## 📁 Repository Structure

```text
Regional-Sales-Analysis/
│
├── README.md
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── Regional_Sales_Analysis.ipynb
│
├── powerbi/
│   └── Regional_Sales_Analysis.pbix
│
├── screenshots/
│   ├── dashboard-overview.png
│   ├── product-channel-performance.png
│   └── geographic-customer-performance.png
│
└── presentation/
    └── Regional_Sales_Analysis.pptx
```

## 🎯 Skills & Competencies

**Data Analytics**
- Exploratory Data Analysis (EDA)
- Trend Analysis
- Product Analysis
- Sales Channel Analysis
- Regional Analysis
- Customer Analysis
- Profitability Analysis
- Correlation Analysis

**Data Preparation**
- Data Cleaning
- Data Transformation
- Data Integration
- Feature Engineering
- Data Validation

**Business Intelligence**
- Power BI Dashboard Development
- KPI Monitoring
- Interactive Data Visualization
- Business Storytelling
- Dashboard Design

**Business & Analytical Thinking**
- Problem Solving
- Business Question Formulation
- Insight Generation
- Business Recommendations
- Data-Driven Decision Making

## 🏆 Project Value

Proyek ini menunjukkan proses analisis data secara end-to-end, mulai dari pengolahan data mentah hingga menghasilkan rekomendasi bisnis yang dapat digunakan sebagai bahan pertimbangan pengambilan keputusan.

Melalui tiga dashboard Power BI, stakeholder dapat mengevaluasi kinerja penjualan dari berbagai perspektif, mengidentifikasi area dengan kontribusi terbaik, serta menemukan peluang untuk mengoptimalkan strategi penjualan dan profitabilitas.

**End-to-End Workflow:**

```text
Raw Data
   ↓
Data Cleaning & Preparation
   ↓
Exploratory Data Analysis
   ↓
Key Business Insights
   ↓
Power BI Dashboard
   ↓
Business Recommendations
```

## 👨‍💻 About Me

### Faris Fatur Rohman
**Mathematics Graduate | Aspiring Data Analyst**

Saya merupakan lulusan Matematika dengan ketertarikan pada Data Analytics dan Data Science, khususnya dalam mengolah data menjadi insight yang dapat mendukung pengambilan keputusan bisnis.

**Core Skills**

```text
Python
SQL
Microsoft Excel
Power BI
Pandas
NumPy
Data Cleaning
Exploratory Data Analysis
Data Visualization
Business Intelligence
```

Saya tertarik untuk mengembangkan kemampuan analytical thinking dan business understanding melalui penyelesaian permasalahan nyata menggunakan data.

## 💼 Career Interests

Saya terbuka terhadap peluang karier di bidang:

- Data Analyst
- Junior Data Analyst
- Business Intelligence Analyst
- BI Developer
- Data Science
- Analytics Internship

## ⭐ Let's Connect

Saya terbuka untuk berdiskusi, belajar, dan berkolaborasi dengan recruiter, hiring manager, maupun profesional di bidang Data Analytics.

## 📌 Disclaimer

Proyek ini dibuat untuk keperluan portfolio dan edukasi dengan tujuan menunjukkan penerapan proses Data Analytics end-to-end, mulai dari data preparation, Exploratory Data Analysis, dashboard development, hingga penyusunan business insights dan recommendations.
