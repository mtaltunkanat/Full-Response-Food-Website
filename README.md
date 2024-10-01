https://www.youtube.com/watch?v=3zbtWSpsFV4&list=PLdz-gps4GThx5Ny6v9qhXIDzaMYydqXrQ&index=2
53.00
imagesler orada
ilk hali
![Ekran görüntüsü 2024-09-21 134542](https://github.com/user-attachments/assets/1998a6d2-b18e-45f0-8f53-0888111413c8)

son hali
![Ekran görüntüsü 2024-10-01 232950](https://github.com/user-attachments/assets/599e6128-a233-4032-b34d-474dfc5d3bb9)

Ortadaki yazı ve butonları sola çekmek için CSS kodunda düzenlemeler yapmanız gerekiyor. Şu adımları takip edebilirsiniz:

Metin ve Butonlar için Konteyneri Sola Hizalayın: text-align ve justify-content gibi özellikler ile hizalamayı değiştirebilirsiniz.
CSS kodunuzda aşağıdaki düzenlemeleri yapabilirsiniz:

css
Kodu kopyala
.header-content {
    position: absolute;
    top: 50%;
    left: 0; /* Sola hizalama */
    transform: translateY(-50%);
    text-align: left; /* Metinleri sola hizalar */
    padding-left: 20px; /* İsteğe bağlı: Soldan boşluk bırakmak için */
}

.header-content h1 {
    font-size: 48px;
    color: white;
}

.header-content p {
    font-size: 16px;
    color: white;
    max-width: 500px; /* Metin genişliğini sınırlamak için */
}

.header-content .buttons {
    margin-top: 20px;
}

.header-content .buttons a {
    display: inline-block;
    background-color: #6c63ff;
    color: white;
    padding: 10px 20px;
    margin-right: 10px;
    border-radius: 5px;
    text-decoration: none;
}
HTML Kodundaki Düzenleme: Eğer mevcut kodunuzda bir header-content sınıfı yoksa, aşağıdaki gibi yapıyı oluşturabilirsiniz:
html
Kodu kopyala
<div class="header-content">
    <h1>EN KALİTELİ WEB SİTELERİNİN TEK ADRESİ</h1>
    <p>Lorem Ipsum, Dolor Sit Amet Consectetur Adipisicing Elit...</p>
    <div class="buttons">
        <a href="#">Bizi Arayın</a>
        <a href="#">Bize Yazın</a>
    </div>
</div>
Açıklamalar:
position: absolute; ile içerikleri tam olarak istediğiniz yere yerleştirebilirsiniz.
left: 0; ile içerikleri tamamen sol tarafa hizalıyoruz.
padding-left ile sola biraz boşluk ekleyebilirsiniz (isteğe bağlı).
text-align: left; ile metin ve butonları sola hizalıyoruz.
Bu değişikliklerle birlikte yazı ve butonlar, tam olarak istediğiniz gibi sola çekilecektir.
chatgpt cevabı budur
