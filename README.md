# MechDock-Updates

MechDock kullanıcı EXE dosyaları ve açık derleme kimlikleri. Kaynak kod ve
özel anahtar içermez.

**Güncel test paketi: 0.2.6 ön sürüm.**
[MechDock.exe indir](https://github.com/zzsavas/MechDock-Updates/releases/download/v0.2.6/MechDock.exe)
· [Release / build kimliği ve SHA-256](https://github.com/zzsavas/MechDock-Updates/releases/tag/v0.2.6).

Bu sürümde gerçek çizim/PDF kabulünün açık engelleri vardır; imalata hazır
olarak sunulmaz. Otomatik Python/JavaScript ve CAD'e erişmeyen paket smoke
kontrolleri geçmiştir. İlk gerçek SolidWorks 2021 testinde kaynak model
korunmuş, çizim/PDF kabulü başarısız olmuştur; yeni pakette yeniden kabul gerekir.

İmzalı `latest.json` ve kararlı `/releases/latest` **0.2.5** olarak korunur.
Özgün güncelleme imzalama anahtarı bulunamadığından 0.2.6 için otomatik
imzalı bildirim üretilememiştir; imza denetimi değişmemiştir. Ön sürüm elle
indirilir. Önce aktif CAD işinin bitmesini ve uygulamanın güvenli kapanışını
bekleyin; ayar/model/çıktı dosyalarını silmeyin.

`releases/0.2.6/BUILD_INFO.json` içindeki `source_revision` paket kaynağıdır;
`exe_sha256` indirilen dosyanın SHA-256 özetidir. Kaynak/devir belgesine erişim
özel kaynak deposu için yetkili GitHub hesabı gerektirir.
