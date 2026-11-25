# 🏐 Voleybol Isınma Koçu

Maç öncesi ısınma hareketlerini kamerayla takip eden, hareketleri animasyonla gösteren ve doğru yapılıp yapılmadığını kontrol ederek sesli yönlendiren web uygulaması.

**Uygulamayı aç:** https://cemyurtlak.github.io/voleybol-isinma-kocu/

## Özellikler
- Kamera ile gerçek zamanlı vücut takibi (33 eklem noktası)
- Her hareket öncesi animasyonlu gösterim
- Tekrar sayma ve hatalı harekette uyarı (ör. "Dirseklerini bükme", "Dizlerini içe kapatma")
- Türkçe sesli koç
- Baştan ayağa sıralı 10 hareket: boyun yana eğme, omuz kaldırma, kol çevirme, kolları açıp yukarıda birleştirme, gövde yana eğilme, öne eğilme, squat, yerinde diz çekme, parmak ucunda yükselme, kriko

## Kullanılan teknoloji
- Google MediaPipe Pose Landmarker (açık kaynak, Apache 2.0) — tarayıcıda yerel çalışır, görüntü hiçbir sunucuya gönderilmez
- Hareket doğruluğu: eklem noktaları arasındaki açı ve mesafelerle kural tabanlı değerlendirme

## Kullanım
Linki Chrome veya Edge'de açın, kamera izni verin, kameradan 2–3 metre uzakta tüm vücudunuz görünecek şekilde durun.

Proje: Elif — Özel Muratpaşa Yükseliş Koleji
