# Devnot 2025 N8N Workflows

Bu repository, Devnot 2025 etkinliğinde gösterilen N8N workflow'larını içermektedir.

## Workflow'lar

### 1. PDF RAG (Pdf_RAG.json)
Bu workflow, PDF dosyalarından bilgi çıkarma ve sorgulama yapabilmenizi sağlar. Workflow şu adımları içerir:
- PDF dosyasını okuma
- Metin bölümleme
- OpenAI entegrasyonu
- Vektör veritabanı depolama
- Sohbet arayüzü ile etkileşim

### 2. Save Receipt (Save_Receipt.json)
Bu workflow, makbuz kaydetme işlemlerini otomatize eder. İçerdiği adımlar:
- HTTP isteği ile veri alma
- Dosya yazma işlemi

### 3. Trip Planner (Trip_Planner.json)
Seyahat planlama asistanı workflow'u. Şu özellikleri içerir:
- OpenAI ile seyahat önerileri oluşturma
- HTTP istekleri ile harici servislerle entegrasyon

## Kurulum

1. Bu workflow'ları kullanmak için öncelikle [n8n](https://n8n.io/) platformunun kurulu olması gerekmektedir.
2. JSON dosyalarını n8n'e import edin:
   - N8N arayüzünde "Workflows" sekmesine gidin
   - "Import from File" seçeneğini kullanın
   - İlgili JSON dosyasını seçin

## Gereksinimler

- N8N platformu
- OpenAI API anahtarı (PDF RAG ve Trip Planner workflow'ları için)
- İnternet bağlantısı

## Not

Workflow'ları kullanmadan önce:
- Gerekli API anahtarlarını ayarladığınızdan
- Bağlantı noktalarının doğru yapılandırıldığından
- Dosya yollarının kendi sisteminize göre güncellendiğinden

emin olun.

## Lisans

MIT 

## Faydalı Kaynaklar

### [n8n](https://n8n.io/)
Açık kaynak kodlu bir workflow otomasyon platformu olan n8n, 200'den fazla servis ile entegrasyon imkanı sunar. Node tabanlı görsel arayüzü ile kod yazmadan iş akışları oluşturabilir, kendi sunucunuzda host edebilir veya cloud versiyonunu kullanabilirsiniz. Özellikle teknik kullanıcılar için güçlü özelleştirme imkanları sunar.

### [Microsoft Power Automate](https://www.microsoft.com/en-us/power-platform/products/power-automate)
Microsoft'un kurumsal düzeyde otomasyon çözümü olan Power Automate, düşük kodlu ve AI destekli bir platformdur. Microsoft 365 uygulamalarıyla derin entegrasyonu, RPA (Robotik Süreç Otomasyonu) yetenekleri ve 1000'den fazla hazır bağlayıcısı ile iş süreçlerini otomatikleştirmek için kapsamlı bir çözüm sunar.

### [Smythos](https://smythos.com/)
Smythos, yapay zeka destekli iş akışı otomasyonu platformudur. Doğal dil işleme yetenekleri sayesinde, kullanıcılar metin tabanlı komutlarla karmaşık iş akışları oluşturabilir. Özellikle AI modelleri ve veri işleme süreçlerinin otomasyonunda öne çıkar.

### [MindStudio](https://www.mindstudio.ai/)
MindStudio, AI ajanları ve otomasyonları oluşturmak için tasarlanmış modern bir platformdur. Görsel arayüzü ve AI destekli araçlarıyla, kullanıcılar karmaşık AI uygulamalarını kolayca oluşturabilir ve yönetebilir. Özellikle LLM (Large Language Model) tabanlı uygulamalar için optimize edilmiştir.

### [Zapier](https://zapier.com/)
Web uygulamaları arasında otomasyon oluşturmayı sağlayan popüler bir platform olan Zapier, 5000'den fazla uygulama ile entegrasyon sunar. Kod yazmadan "Zap" adı verilen otomasyonlar oluşturarak farklı servisleri birbirine bağlayabilirsiniz. Özellikle küçük işletmeler ve bireysel kullanıcılar için kullanıcı dostu bir çözümdür.

### [Make (Formerly Integromat)](https://www.make.com/)
Make (eski adıyla Integromat), görsel bir arayüz üzerinden karmaşık otomasyonlar oluşturmanıza olanak sağlar. Detaylı hata ayıklama araçları, gelişmiş veri dönüşüm özellikleri ve esnek tetikleyici seçenekleriyle öne çıkar. İş süreçlerini otomatikleştirmek için güçlü ve ölçeklenebilir bir platformdur. 