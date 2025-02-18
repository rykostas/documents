**Doğal Dil İşleme Araçları Kurulum Kılavuzu**

Bu dokümanda, doğal dil işleme çalışmaları için gerekli olan programlama araçlarının kurulum adımları anlatılmaktadır.

### 1. Python Kurulumu

Python'un en güncel sürümünü indirip kurmak için:

1. [Python Resmi Sitesi](https://www.python.org/downloads/) adresine gidin.
2. "Download" bölümünden kendi işletim sisteminize uygun Python sürümünü indirin.
3. Kurulum sihirbazını çalıştırın ve **"Add Python to PATH"** seçeneğini işaretleyerek kurulumu tamamlayın.

   **Neden "Add Python to PATH" Seçeneğini Aktifleştirmelisiniz?**
   Bu seçenek, Python'un sistemde global olarak tanınmasını sağlar. Aksi halde, Python komut satırından doğrudan çalıştırılamaz ve her seferinde Python'un yüklendiği dizini manuel olarak belirtmeniz gerekir. Bu nedenle, PATH değişkenine eklemek Python'u daha kolay kullanmanıza olanak tanır.

### 2. pip Güncelleme

Kurulumlar sırasında sistem, pip'in güncellenmesi gerektiğini belirtebilir. Pip'i güncellemek için komut satırına (cmd veya terminal) aşağıdaki komutu yazabilirsiniz:

```sh
pip install --upgrade pip
```

   **Neden pip Güncellemesi Gerekebilir?**
   - Yeni paketleri sorunsuz yükleyebilmek için güncel bir pip sürümüne sahip olmak gerekir.
   - Bazı eski pip sürümleri, yeni Python paketlerini yüklerken hata verebilir.

### 3. Jupyter Notebook Kurulumu

Jupyter Notebook'u kurmak için aşağıdaki adımları takip edebilirsiniz:

1. Komut satırını (Command Prompt / Terminal) açın.
2. Aşağıdaki komutu çalıştırın:
   ```sh
   pip install notebook
   ```
3. Kurulum tamamlandıktan sonra Jupyter Notebook'u başlatmak için:
   ```sh
   jupyter notebook
   ```
   komutunu kullanabilirsiniz.

   **Jupyter Notebook Nasıl Açılır?**
   - Windows'ta **Başlat Menüsü** → **Komut İstemi (cmd)**'yi açın ve yukarıdaki `jupyter notebook` komutunu çalıştırın.
   - macOS ve Linux'ta **Terminal** uygulamasını açıp aynı komutu girerek çalıştırabilirsiniz.
   - Jupyter Notebook başlatıldığında varsayılan internet tarayıcınızda otomatik olarak açılacaktır. Eğer açılmazsa, terminalde görünen bağlantıyı kopyalayıp tarayıcınıza yapıştırabilirsiniz.

   **Jupyter Notebook ile Çalışmaya Başlama**
   - Jupyter açıldıktan sonra tarayıcınızda bir arayüz belirecektir.
   - "New" butonuna tıklayıp **Python 3** seçeneğini seçerek yeni bir notebook oluşturabilirsiniz.
   - Açılan sayfada kod yazmaya başlayabilirsiniz. Örneğin, aşağıdaki basit Python kodunu çalıştırabilirsiniz:
     ```python
     print("Merhaba, Jupyter!")
     ```
   - Kodu çalıştırmak için **Shift + Enter** tuşlarına basabilirsiniz.

### 4. NLTK Paketinin Kurulumu

Doğal dil işleme için yaygın olarak kullanılan **nltk** paketini kurmak için:

1. Komut satırını açın ve aşağıdaki komutu çalıştırın (**Jupyter Notebook içinde değil, doğrudan komut satırında çalıştırmalısınız**):
   ```sh
   pip install nltk
   ```
2. NLTK'nin bazı ek veri setlerini indirmek için Python ortamında şu komutları çalıştırabilirsiniz (Bunları Jupyter Notebook içinde çalıştırabilirsiniz):
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   ```

### 5. **re** Kütüphanesinin Kullanımı

Python'un **re** kütüphanesi, düzenli ifadeler (regex) ile çalışmak için kullanılır. **re** kütüphanesi Python ile birlikte geldiğinden ekstra bir kurulum yapmaya gerek yoktur. Kullanmak için Python kodlarınıza şu satırı ekleyebilirsiniz:

```python
import re
```

Bu şekilde düzenli ifadeler ile metin işleme yapabilirsiniz.

Kurulum sürecinde herhangi bir sorun yaşarsanız, hata mesajını bizimle paylaşabilirsiniz.

