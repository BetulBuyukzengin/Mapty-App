# Mapty-App
<!-- Mapty-App ı, The Complate Javascript Course - 'Jonas Schmedtmann' eşliğinde  oluşturdum.-->
## Bu uygulamada *leaflet kütüphanesini* kullanarak Mapty-App uygulamasını oluşturdum.

### Bu uygulamada yapabilecekleriniz:
* Uygulamayı açtığınızda ilk olarak sizden konumunuza erişim izni isteyecektir. İzin verdiğiniz takdirde harita konumunuza göre yüklenecektir.
* O an ki konumunuz dışında istediğiniz konumu işaretleyebilirsiniz.
* Seçilen konum için ekranın solunda form oluşacaktır.
* Form için running ya da cycling seçeneklerini seçebilirsiniz.
* Running seçeneği için *distance*, *duration* ve *cadence* değerlerini girmelisiniz.
* Cycling seçeneği için *distance*, *duration* ve *elevation gain* değerlerini girmelisiniz.
<br>

![Forkify-App](img/maptyForm.png)
![Forkify-App](img/mapty.png)
![Forkify-App](img/maptyCycling.png)

## 🔴Projenin deploy edilmiş versiyonu :
 <h3><a href="https://mapty-app-betul.netlify.app/">Mapty-App</a></h3>
 
### - 🛠 Kullandığım teknolojiler :
 <img src="https://img.shields.io/badge/-JavaScript-black?style=flat&logo=javascript"/><img src="https://img.shields.io/badge/-SCSS-pink?style=flat&logo=scss"/>
 <img src="https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white"> 
 <a href="https://leafletjs.com/reference.html"><img src="https://img.shields.io/badge/Leaflet-gray"></a>

###  Oluşturduğum özellikler:
* Kodun daha iyi anlaşılabilmesi, kolayca düzenlenebilmesi ve yeni özelliklerin çok daha kolay eklenebilmesi için MVC (Model-View-Controller) tasarım desenini kullandım.
* Yemek tarifleri almak ve yeni tarifleri eklemek için **AJAX ** çağrılarını kullanarak API ile etkileşim kurdum.
* Sayfa görünümlerinin anlaşılabilirliği amacıyla birden fazla view dosyası ve ortak özelliklere sahip viewler için de ana View dosyası oluşturdum (Inheritance)
* MVC tasarıım desenini bozmamak adına  ***Subscriber - Publisher*** model yapısını kullandım.
* View dosyalarımda class yapısını kullandım.
* Daha düzenli bir yapı için SASS kullandım.
* İyi bir performans için tüm sayfayı güncellemek yerine sadece değişen ögelerin güncellenmesini sağladım.
* Daha modern bir yapı için Ajax çağrılarını uygularken Async-Await yöntemini kullandım. 

#### Projenin bağımlılıkları :
* "fracty": "^1.0.0"
* "parcel": "^2.10.1"

