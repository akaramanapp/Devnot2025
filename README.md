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