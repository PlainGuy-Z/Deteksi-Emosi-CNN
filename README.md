# CNN Test - Emotion Detection
Repository ini berisi eksperimen pribadi untuk menguji implementasi sederhana Convolutional Neural Network (CNN) dalam tugas **face emotion detection**.  
Tujuan utamanya bukan untuk produksi, tapi sebagai *playground* untuk ngoprek model, tuning hyperparameter, dan nguji performa dataset secara cepat.

## 🎯 Tujuan Proyek
- Mengetes arsitektur CNN dasar untuk klasifikasi emosi wajah.  
- Mencoba berbagai konfigurasi layer, dropout, augmentation, dan optimizer.  
- Mengetes apakah target akurasi tertentu (≥ 75% atau lebih tinggi) bisa dicapai.  
- Menyimpan hasil eksperimen sebelum dipindah ke repository project tim.

## 📂 Struktur Project
```
CNN_Test_Emotion_Detection/
│
├── dataset/
│   └── test/
│       └── angry/
│       └── disgust/
│       └── fear/
│       └── happy/
│       └── neutral/
│       └── sad/
│       └── surprise/
│   └── train/
│       └── angry/
│       └── disgust/
│       └── fear/
│       └── happy/
│       └── neutral/
│       └── sad/
│       └── surprise/
├── .gitignore
├── main.ipynb
└── README.MD
```
