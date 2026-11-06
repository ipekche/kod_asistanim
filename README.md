# Kod-Asistan v0.1

**Proje Yazarı:** İpek YILMAZ

## Projenin Amacı
Kullanıcılara günlük işlerinde (hesaplama, selamlama vb.) yardımcı olacak bir dijital asistan tasarlamak.

## Projenin Hedefleri
* v1.0 Akıllı Menü entegrasyonunun sağlanması
* v2.0 Veri Saklama ve veri tabanı modülünün geliştirilmesi


## Proje Kapsamı ve Kritik Eşik Sözde Kodu
Projenin temel çalışma algoritması, belirlenen bir kritik sınır değerine (örneğin sıcaklık, kota veya giriş limiti) göre sistemin tepki vermesini temel alır. Tasarlanan sözde kod mantığı aşağıda belirtilmiştir:
1. BAŞLA
2. saat = 1 değerini ata 
3. DÖNGÜYÜ BAŞLAT 
4. Sensörden gelen su_seviyesi değerini oku.
5. EĞER su_seviyesi > 50 İSE
6. YAZ "Kritik seviye aşıldı! Tahliye saati: ", saat, " | Su Seviyesi: ", su_seviyesi
7. DÖNGÜDEN ÇIK
8. DEĞİLSE (Su seviyesi 50 veya altındaysa)
9. YAZ saat, ". saatte kapaklar kapalı tutuluyor."
10. saat = saat + 1 (Saat sayacını 1 artır)
11. DÖNGÜYÜ SONLANDIR
12. DUR

## Kaynakça
Bu proje belgelendirilirken ve geliştirilirken aşağıdaki kurumsal kaynaklardan atıf yapılarak yararlanılmıştır:
* Millî Eğitim Bakanlığı, *Programlama Temelleri Ders Kitabı*, Ankara.
