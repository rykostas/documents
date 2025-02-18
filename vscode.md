# VS Code Üzerinde Jupyter Kurulumu

## 1. VS Code'u Yükleyin
Eğer VS Code yüklenmemişse, [resmi web sitesinden](https://code.visualstudio.com/) indirin ve kurulum adımlarını takip edin.

## 2. Python ve Jupyter Paketlerini Yükleyin
Jupyter'i çalıştırabilmek için Python'un sisteminizde kurulu olması gereklidir.

### a) Python'un Kurulu Olduğunu Kontrol Edin
Terminal (Komut Satırı) üzerinde şu komutu çalıştırın:
```
python --version
```
Eğer Python yüklenmemişse, [Python'un resmi web sitesinden](https://www.python.org/downloads/) uygun sürümü indirip kurabilirsiniz.

### b) Gerekli Paketleri Yükleyin
Python yüklendikten sonra terminalde şu komutları çalıştırın:
```
pip install jupyter
pip install notebook
```

## 3. VS Code Üzerinde Jupyter Eklentisini Kurun
VS Code'u açın ve şu adımları takip edin:
1. **Uzantılar (Extensions) Sekmesini Açın** (Ctrl + Shift + X)
2. **"Jupyter" Uzantısını Aratın** ve **Yükleyin**

## 4. Jupyter Notebook'u VS Code Üzerinde Çalıştırma
Jupyter Notebook dosyası oluşturup çalıştırmak için şu adımları izleyin:
1. **VS Code'da yeni bir dosya oluşturun** ve ".ipynb" uzantısıyla kaydedin (örneğin, `notebook.ipynb`).
2. **Dosyayı açın** ve bir Python kodu yazın.
3. **Üst kısımdaki "Run" Butonuna Basın** veya **Shift + Enter** tuşlarına basarak kodu çalıştırın.

## 5. Alternatif: Terminal Üzerinden Jupyter Notebook Çalıştırma
Jupyter Notebook'u terminalden de başlatabilirsiniz:
```
jupyter notebook
```
Bu komut, tarayıcıda Jupyter Notebook arayüzünü açar.



