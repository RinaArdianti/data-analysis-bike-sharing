#  Bike Sharing Dashboard 

 
Dibuat menggunakan **Streamlit**, **Pandas**, **Plotly**, dan **Seaborn**.

---

##  Setup Environment

###  Menggunakan Anaconda
```bash
conda create --name bike-dashboard python=3.9
conda activate bike-dashboard
pip install -r requirements.txt

###  Menggunakan Shell / Terminal
mkdir bike_dashboard
cd bike_dashboard
python -m venv venv
venv\Scripts\activate    # untuk Windows
# atau
source venv/bin/activate # untuk Mac/Linux
pip install -r requirements.txt

---

##  Jalankan Streamlit App
```bash
streamlit run app.py
```

---




##  Fitur Dashboard
- **Tren Penyewaan Harian**  
  Menampilkan total penyewaan berdasarkan tanggal.
- **Penyewaan per Jam**   
  Analisis jumlah penyewaan berdasarkan jam.
- **Penyewaan Berdasarkan Cuaca**   
  Menunjukkan pengaruh kondisi cuaca terhadap penyewaan.
- **Penyewaan Berdasarkan Demand Level**  
  Mengelompokkan penyewaan berdasarkan tingkat permintaan.

---

##  Dependensi Utama
- pandas  
- matplotlib  
- seaborn  
- plotly  
- streamlit

---

##  Author
**Ni Kadek Rina Ardianti**  

