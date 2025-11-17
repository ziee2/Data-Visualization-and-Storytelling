# 📊 Data Storytelling - Materi Praktikum

## 📋 Deskripsi

Repository ini berisi materi praktikum lengkap untuk mata kuliah **Data Visualization - Data Storytelling**. Materi dirancang untuk membantu mahasiswa memahami dan menerapkan teknik data storytelling menggunakan Python.

---

## 🎯 Tujuan Pembelajaran

Setelah menyelesaikan modul praktikum ini, mahasiswa akan mampu:

1. ✅ Memahami konsep fundamental data storytelling
2. ✅ Membedakan visualisasi data biasa dengan storytelling yang efektif
3. ✅ Menggunakan library Python (Pandas, Matplotlib, Seaborn, Plotly) untuk visualisasi
4. ✅ Menerapkan prinsip desain visual dan color theory
5. ✅ Membuat narasi yang compelling dengan data
6. ✅ Mengembangkan dashboard interaktif
7. ✅ Menyampaikan insight dengan clear call-to-action

---

## 📚 Struktur Materi

### **Modul 1: Pengenalan Data Storytelling**

📓 File: `notebooks/01_intro.ipynb`

**Topik Bahasan:**

- Apa itu Data Storytelling?
- 4 Elemen Penting: Context, Data, Narrative, Visualization
- Mengapa Data Storytelling Penting?
- Framework Storytelling (Setup, Rising Action, Climax, Resolution)
- Perbandingan Visualisasi Buruk vs Baik
- Best Practices & Tips

**Implementasi Kode:**

```python
# Contoh: Membuat data story sederhana
- Setup environment (pandas, matplotlib, seaborn)
- Generate sample sales data
- Visualisasi tanpa story (buruk)
- Visualisasi dengan story (baik) + annotations
- Narasi lengkap dengan context & insights
- Rekomendasi actionable
```

**Latihan:**

- Analisis kepuasan pelanggan 4 kategori service
- Identifikasi area improvement
- Buat visualisasi + narasi efektif

---

### **Modul 2: Visualisasi Data untuk Storytelling**

📓 File: `notebooks/02_visualization_basics.ipynb`

**Topik Bahasan:**

- Memilih Chart yang Tepat (Bar, Line, Scatter, Heatmap, dll)
- Bar Charts untuk Perbandingan
- Line Charts untuk Tren Waktu
- Scatter Plots untuk Korelasi
- Heatmaps untuk Pola
- Distribution Plots (Box Plot, Violin Plot)
- Small Multiples Technique
- Color Psychology & Palettes
- Annotations dan Text yang Efektif

**Implementasi Kode:**

```python
# Contoh berbagai jenis visualisasi:
1. Bar Chart Enhancement
   - Horizontal bars dengan color coding
   - Value labels dan reference lines
   - Highlighting above/below average

2. Line Chart dengan Storytelling
   - Trend lines dan moving averages
   - Peak annotations
   - Highlighting key periods

3. Scatter Plot dengan Narasi
   - Correlation visualization
   - Regression lines
   - Category coloring

4. Heatmap untuk Pattern Discovery
   - Pivot tables visualization
   - Color gradients
   - Insight extraction

5. Color Palettes Demo
   - Sequential (kuantitatif)
   - Diverging (with midpoint)
   - Categorical (distinct categories)
   - Colorblind-friendly options
```

**Latihan:**

1. Story-driven visualization dengan demographics data
2. Multi-plot dashboard (4 subplots)

---

### **Modul 3: Advanced Data Storytelling**

📓 File: `notebooks/03_data_storytelling.ipynb`

**Topik Bahasan:**

- Narrative Structures (Linear, Non-linear, Interactive)
- Context Building Techniques
- Audience Analysis
- Data-Driven Decision Making
- Storyboarding
- Call-to-Action Design
- Real-World Case Studies

**Implementasi Kode:**

```python
# Studi Kasus Komprehensif:
1. E-Commerce Sales Analysis
   - Multi-dimensional data exploration
   - Cohort analysis
   - Customer segmentation story

2. Marketing Campaign Performance
   - Before/after comparison
   - ROI storytelling
   - Channel effectiveness

3. Business Intelligence Dashboard
   - KPI visualization
   - Executive summary
   - Drill-down capabilities
```

**Latihan:**

- Analisis lengkap dataset real-world
- Presentasi story dengan multiple insights
- Rekomendasi strategis

---

### **Modul 4: Interactive Dashboards**

📓 File: `notebooks/04_interactive_dashboards.ipynb`

**Topik Bahasan:**

- Plotly untuk Visualisasi Interaktif
- Dash/Streamlit untuk Web Apps
- Dashboard Design Principles
- User Interaction Patterns
- Deployment Basics

**Implementasi Kode:**

```python
# Interactive Components:
1. Plotly Express & Graph Objects
   - Interactive line charts
   - Animated visualizations
   - 3D plots
   - Choropleth maps

2. Streamlit Dashboard
   - Multi-page apps
   - Filters dan dropdowns
   - Real-time updates
   - Data download features

3. Deployment
   - Streamlit Cloud
   - Heroku basics
   - GitHub Pages
```

**Project:**

- Build complete interactive dashboard
- Deploy to cloud platform

---

## 🛠️ Setup & Installation

### Prerequisites

- Python 3.8+
- Jupyter Notebook / JupyterLab
- VS Code (recommended)

### Installation Steps

```bash
# 1. Clone repository
git clone [repository-url]
cd data-viz-storytelling

# 2. Create virtual environment
python -m venv venv

# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter
jupyter notebook
```

---

## 📦 Dependencies

```txt
# Core Libraries
pandas>=2.0.0
numpy>=1.24.0
matplotlib>=3.7.0
seaborn>=0.12.0

# Interactive Visualization
plotly>=5.14.0
dash>=2.9.0
streamlit>=1.22.0

# Data Processing
scipy>=1.10.0
scikit-learn>=1.2.0

# Utilities
jupyter>=1.0.0
ipywidgets>=8.0.0
```

---

## 🎨 Best Practices yang Diajarkan

### 1. **Visualisasi Design**

- ✅ Less is More - Simplicity over complexity
- ✅ Signal > Noise - Remove chart junk
- ✅ Consistent styling across charts
- ✅ Accessibility (colorblind-friendly)

### 2. **Color Usage**

- ✅ Sequential: Light → Dark untuk Low → High
- ✅ Diverging: Red ← White → Blue untuk positive/negative
- ✅ Categorical: Distinct colors untuk kategori berbeda
- ✅ Semantic: Red=danger, Green=success, Blue=neutral

### 3. **Storytelling Framework**

```
1. SETUP: Perkenalkan konteks
2. RISING ACTION: Tunjukkan data & pola
3. CLIMAX: Highlight insight utama
4. RESOLUTION: Kesimpulan & rekomendasi
```

### 4. **Annotation Tips**

- ✅ Highlight key moments
- ✅ Use arrows untuk direct attention
- ✅ Boxes untuk emphasis
- ✅ Concise & actionable text

---

## 📖 Referensi & Resources

### Buku

1. **"Storytelling with Data"** - Cole Nussbaumer Knaflic

   - Bible of data storytelling
   - Practical examples dan exercises

2. **"The Truthful Art"** - Alberto Cairo

   - Data visualization principles
   - Ethics dalam data viz

3. **"Data Visualization Handbook"** - Andy Kirk
   - Comprehensive guide
   - Design thinking approach

### Online Resources

- [Matplotlib Documentation](https://matplotlib.org/)
- [Seaborn Gallery](https://seaborn.pydata.org/examples/index.html)
- [Plotly Examples](https://plotly.com/python/)
- [ColorBrewer](https://colorbrewer2.org/) - Color palettes
- [Data Viz Project](https://datavizproject.com/) - Chart selection

### Inspirasi

- [Information is Beautiful](https://informationisbeautiful.net/)
- [FlowingData](https://flowingdata.com/)
- [The Pudding](https://pudding.cool/)

---

## 💡 Contoh Output yang Diharapkan

### Good Data Story Example:

```
📊 Title: "Q4 Sales Surge: Product A Leads 67% Growth"

🎯 Context:
"Kami meluncurkan 3 produk di awal 2024 untuk menargetkan
segmen pasar baru..."

📈 Visualization:
- Line chart menunjukkan tren 12 bulan
- Product A: hijau (trending up)
- Product B: merah (declining)
- Product C: biru (rising star)
- Annotations di peak periods
- Highlight Q4 performance

💡 Insights:
"Product A dan C tumbuh 140%+ dengan akselerasi kuat di Q4.
Product B menurun 33% - perlu evaluasi segera."

🎯 Recommendations:
1. Scale up production untuk A & C
2. Customer research untuk B
3. Optimize Q4 inventory planning
```

---

## 🏆 Assessment Criteria

### Penilaian Praktikum:

**1. Kualitas Visualisasi (30%)**

- Pemilihan chart yang tepat
- Design yang clean dan professional
- Appropriate use of color
- Effective annotations

**2. Storytelling (40%)**

- Clear narrative structure
- Context building
- Insight clarity
- Actionable recommendations

**3. Implementasi Teknis (20%)**

- Code quality dan organization
- Proper use of libraries
- Error handling
- Documentation

**4. Kreativitas (10%)**

- Original approach
- Engaging presentation
- Unique insights

---

## 🚀 Project Ideas

### Mini Projects untuk Praktik:

1. **Sales Dashboard**

   - Multi-regional performance
   - Product comparison
   - Trend analysis
   - Forecasting

2. **Social Media Analytics**

   - Engagement metrics
   - Growth stories
   - Content performance
   - Audience insights

3. **Financial Storytelling**

   - Revenue trends
   - Expense breakdown
   - Profitability analysis
   - Investment decisions

4. **Customer Analytics**

   - Segmentation
   - Churn analysis
   - Lifetime value
   - Satisfaction scores

5. **Marketing Campaign**
   - ROI visualization
   - Channel effectiveness
   - Conversion funnels
   - A/B testing results

---

## 🤝 Contributing

Untuk asisten praktikum yang ingin menambah/memperbaiki materi:

1. Fork repository
2. Create feature branch (`git checkout -b feature/NewModule`)
3. Commit changes (`git commit -m 'Add new storytelling technique'`)
4. Push to branch (`git push origin feature/NewModule`)
5. Create Pull Request

---

## 📞 Support & Contact

**Instruktur:** [Nama Instruktur]  
**Email:** [email]  
**Office Hours:** [jadwal]  
**Lab:** [lokasi]

### FAQ & Troubleshooting

- **Q: Jupyter tidak bisa dibuka?**

  - A: Cek instalasi: `jupyter --version`, reinstall jika perlu

- **Q: Module not found error?**

  - A: Install dependencies: `pip install -r requirements.txt`

- **Q: Plot tidak muncul?**
  - A: Tambahkan `%matplotlib inline` di cell pertama

---

## 📝 Lisensi

Materi ini dibuat untuk keperluan edukasi. Silakan gunakan dan modifikasi sesuai kebutuhan pembelajaran.

---

## 🎓 Kata Penutup

> "The goal is to turn data into information, and information into insight."  
> — Carly Fiorina

Data storytelling adalah skill yang sangat valuable di era data-driven decision making. Dengan menguasai teknik-teknik dalam praktikum ini, Anda akan mampu:

- 📊 Transform raw data menjadi compelling narratives
- 🎨 Create visualizations yang meaningful
- 💡 Drive decisions dengan data-backed insights
- 🚀 Stand out sebagai data communicator

**Selamat belajar dan happy storytelling!** 🎉

---

_Last Updated: November 2024_  
_Version: 1.0_
