# Hürtürk İHA — Link Sayfası

Takımın QR ile açılan sitesi: https://canahmet1407.github.io/

Başvuru formu, Instagram, LinkedIn, YouTube, filo ve sponsorluk tek sayfada.

## Linkleri / yazıları değiştirmek
`index.html` içinde **`DÜZENLEME ALANI`** yazan bloğu bul — her şey orada:

- `links` → her linkin `url` alanı. Boş (`""`) bırakılan link sitede **YAKINDA** olarak görünür.
- `sponsor.email` → Sponsor Ol / E-posta butonları bu adresi kullanır.
- `sponsor.deckUrl` → (isteğe bağlı) sponsorluk dosyası linki.
- `logo` → takım logosu (üst şerit ve en altta görünür).
- `fleet` → filo kartları. Yeni uçak için fotoğrafı yükle (ör. `filo-yeni.jpg`, dikey 4:5) ve `{ name: "HT-...", photo: "filo-yeni.jpg" }` satırı ekle.

GitHub'da dosyayı açıp kalem simgesiyle düzenleyip **Commit changes** demen yeterli; 1–2 dakikada siteye yansır.
