## API NEDİR ?

**API**, İngilizce _'Application Programming Interface'_ kelimelerinin baş harflerinden oluşan bir kısaltmadır.

Türkçesi **'Uygulama Proglamlama Arayüzü'** olarak çevrilebilir.

Bir uygulamanın başka bir uygulamadan veri almasını, işlem yaptırmasını veya hizmet kullanmasını mümkün kılar.

API'ler sayesinde geliştiriciler, sıfırdan sistem yazmak yerine mevcur servisleri kullanarak hızlı, güvenli ve ölçeklenebilir uyygulamalar geliştirebilir.

---

## API Nasıl Çalışır?

API'ler **istemci** (client) ve **sunucu** (server) mantığı ile çalışır.

- İstemci API'ye bir istek gönderir  
- Sunucu isteği işler  
- Sonuç istemciye yanıt olarak döner  

Bu iletişim genellikle **HTTP** üzerinden ve **JSON** ya da **XML** formatında gerçekleşir.

---

## API Türleri

### Kullanım alanına göre

- **Özel (Private / DAhili) API**  
  Sadece kurum içi sistemlerde kullanılır.

- **Açık (Public / Open) API**  
  Herkesin kullanımına açıktır.

- **Parner API**  
  Sadece iç ortaklarına açıktır.

- **Birleşik (Composite) API**  
  Birden fazla API'yi tek uç noktada birleştirir.

---

### Mimariye göre

- **REST API**  
  En yaygın kullanılan API türüdür.  
  **HTTP** metodlarını **(GET, POST, PUT, DELETE)** kullanır ve genellikle **JSON** döner.  
  Durumsuzdur , hızlı ve esnektir.

- **SOAP API**  
  **XML** tabanlıdır, yüksek güvenlik sunar.  
  kurumsal vefinansal sistemlerde tercih edilir.

- **RPC API**  
  Sunucudaki bir fonksiyonu uzaktan çağırmaya dayanır.  
  **JSON-RPC** ve **XML-RPC** yaygındır.

- **WebSocket API**  
  Çift yönlü ve gerçek zamanlı iletişim sağlar.  
  Canlı sohbet,, oyun ve anlık veri uygulamarında kullanılır.

---

## API KUllanım Alanları

- Sosyal medya entegrasynları  
- Ödeme ve bankalıcık servisleri  
- Hava durumu ve konum servisleri  
- E-ticaret sistemleri  
- canlı sohbet ve bildirim sistemleri  
- Borsa ve finans uygulamaları  
- Yapay zeka ve veri analizi serviserli  

---

## API Kullanmanın Avantajları

- Geliştirme süresini kısaltır  
- Tekrar kod yazma ihtiyacını azaltır  
- Güvenli veri paylaşımı sağlar  
- Bakımı ve ölçeklendirmesi kolaydı  
- Platformlar arası entegrasyonu mümkün kılar  

---

## API Güvenliği

### API'ler genellikle işu yöntemler ile korunur:

- API key  
- Token **(JWT, OAuth)**  
- Yetk,ilendirme ve erişim kontrolleri  

API uç noktalarının güvenliği ve performansı, istemin esağlığı açısından kritiktir.

---

## Sonuç

API'ler, modern yazılım geliştirmenin temel yapı taşlarından biridir.  
Farklı sistemlerin sorunsuz şekilde haberleşmesini sağlar projeleri daha hızlı ve veirimli hale getirir.

**REST** başta olmak üszere **SOAP**, **RPC** ve **WebSocket** gibi mimariler sayesinde API'ler, web, mobil, masaüstü ve yapay zeka uygulamalarında yaygın olarak kullanılmaktadır.

## Kaynaklar

- Patika.dev – API Nedir, Ne İşe Yarar  
  https://www.patika.dev/blog/api-nedir-api-ne-ise-yarar

- CoderSpace – API Sözlük  
  https://coderspace.io/sozluk/api/

- AWS – API Nedir?  
  https://aws.amazon.com/tr/what-is/api/
