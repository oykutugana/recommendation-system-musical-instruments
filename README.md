# YZM2022 Data Mining Homework — Recommendation System

Amazon Musical Instruments dataset üzerinde recommendation system tasarımı.

**Dataset:** https://huggingface.co/datasets/oyku-tugana/amazon-musical-instruments-2014-2023-5core

**Project Link:** https://github.com/oykutugana/recommendation-system-musical-instruments

## Klasör Yapısı

- `colab_notebooks/` — embeddings oluştururken ve proje tasarlanırken kullanıldı. Artık sadece arşivde, çalıştırılmamalı.
- `colab_notebooks/01_COLAB_eda_exploration.ipynb`      -COLAB
- `colab_notebooks/02_COLAB_sampling_and_upload.ipynb`  -COLAB
- `colab_notebooks/03_COLAB_embeddings.ipynb`          -COLAB



- `results/` — embeddings hariç diğer klasörler `TuganaOyku_Yildiz_24018020.ipynb` ile oluşturuldu.
- `results/embeddings/` — 03_COLAB_embeddings.ipynb ile oluşturuldu
- `results/figures/` — grafikler
- `results/tables/` — Excel/CSV sonuçları



- `report_24018020.docx`
- `README.md`
- `requirements.txt` 
- `TuganaOyku_Yildiz_24018020.ipynb` 


## ÇALIŞTIRMA TALİMATI

Gereksinimler:
- Python 3.11
- pip install -r requirements.txt

İlk çalıştırma:
1. requirements.txt'deki paketleri kur
2. TuganaOyku_Yildiz_24018020.ipynb dosyasını aç
3. Kernel → Restart → Run All
4. İlk hücrede HF'den dataset indirilir (~50 MB, internet gerek)

Veri kaynağı:
- HF dataset: oyku-tugana/amazon-musical-instruments-2018-2023-5core
- Notebook otomatik indirir.

Önceden hesaplanmış dosyalar:
- results/embeddings/ — SBERT ve CLIP embedding'leri
  (Colab GPU üzerinde üretildi, kod 03_embeddings_colab.ipynb'de
   referans gösterilmiştir. Bu projede 13,575 ürün için image embedding
   gerektiği için GPU şarttır.)
