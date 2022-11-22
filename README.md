# KrissChatbot
  Kriss chatbot adalah bot pintar yang akan membantumu belajar mengenai wawasan berbangsa dan bernegara.
  
# Installasi
Install python 3.9 di windows, download paket menggunakan link berikut:
https://www.python.org/downloads/release/python-3913/

Modul python yang diperlukan antara lain:
```text
tensorflow==2.11.0
nltk==3.7
numpy==1.20.3
keras==2.11.0
tk==0.1.0
```
Install module dengan pip3
```shell
python3.9 -m pip install -r requirements.txt
```

# Dataset
 Dataset yang digunakan terdapat pada file datasets/intents.json. Terdiri atas pola kata dari user dan respon
 
# Training & Modelling
 Mulai training dengan perintah
```shell
python3.9 train_chatbot.py
```

Hasil training yaitu berupa model akan tersimpan menjadi 2 file, yaitu kelas.pkl untuk model klasifikasi dan kosakata.pkl untuk kalsifikasi tiap kata terhadap kelas. dan pemodelan tersimpan di models/chatbot_model.h5

# Interaksi & GUI
 Jalankan perintah berikut untuk membuka jendela chat atau GUI dan mulai berinteraksi dengan bot
```shell
python3.9 gui_chatbot.py
```

#Presentasi

 https://www.youtube.com/watch?v=tJs3VhZ9Xc4&t=7s


