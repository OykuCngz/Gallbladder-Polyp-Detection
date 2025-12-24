# Gallbladder Polyp Detection

Proje, safra kesesi görüntü verileri kullanarak 3 sınıflı (Benign, Polyp, Karsinom) sınıflandırma yapan bir yapay sinir ağı örneğidir.

Dosyalar
- `Proje.ipynb` — Veri yükleme, ön işleme, model eğitimi ve değerlendirme adımları.
- `gallbladder_features.csv` — Kullanılan özellik seti (veri kümesi).

Çalıştırma
1. Sanal ortam oluşturun ve etkinleştirin (önerilir):
   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate
   ```
2. Gerekli paketleri kurun (örnek):
   ```powershell
   pip install -r requirements.txt
   ```
3. `Proje.ipynb` dosyasını VS Code veya Jupyter Notebook ile açıp hücreleri çalıştırın.

Notlar
- Bu repo eğitim amaçlıdır. Gerçek klinik kararlar için uzman değerlendirmesi gerekir.
