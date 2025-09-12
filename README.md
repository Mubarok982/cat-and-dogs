# Cat vs Dog Classification

Proyek ini merupakan implementasi deep learning untuk klasifikasi gambar kucing dan anjing.  
Model dilatih menggunakan TensorFlow/Keras, kemudian diekspor ke tiga format berbeda:

- **Keras (.keras)** → untuk pelatihan/pengecekan ulang
- **TensorFlow.js** → untuk deployment di aplikasi web
- **TensorFlow Lite (.tflite)** → untuk deployment di perangkat mobile/embedded

## Struktur Folder
- `Saved_Model/` → berisi model dalam format `.keras`
- `TFjs_Model/` → berisi model dalam format TensorFlow.js (`model.json` + `.bin`)
- `TFLite/` → berisi model dalam format `.tflite`
- `cat_and_dog_submission.ipynb` → notebook pelatihan & konversi
- `requirements.txt` → daftar dependensi
- `README.md` → dokumentasi proyek

## 📦 Installation
pip install -r `requirements.txt` di direktory tempat folder berada


