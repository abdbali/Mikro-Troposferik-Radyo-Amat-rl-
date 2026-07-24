# Mikro-Troposferik Radyo Amatörlüğü
> **Tam Güneş Tutulması Esnasında Mikro-Troposferik Kanal Oluşumunun (Tropo Ducting) VHF/UHF Frekanslarında İncelenmesi**

---

## Proje Özeti
Bu proje, tam güneş tutulması anında meydana gelen ani sıcaklık düşüşünün yarattığı **termal inversiyonun (sıcaklık terselmesi)**, VHF (144-146 MHz) ve UHF (430-440 MHz) radyo frekanslarındaki yayılım (propagation) üzerindeki etkilerini incelemeyi amaçlar. 

Tutulma anında yer seviyesindeki havanın hızla soğuması, üst katmanların ise sıcak kalmasıyla atmosferde geçici bir **radyo dalga kılavuzu (ducting)** oluşması beklenmektedir. Proje kapsamında Bursa, İstanbul ve İzmir gibi normal şartlarda doğrudan telsiz erişimi (Simplex) olmayan bölgeler arasında rölesiz telsiz iletişim testleri gerçekleştirilecektir.

---

## Amaç ve Hedefler
* **Bilimsel Analiz:** Güneş tutulmalarının yarattığı ani mikro-klimatik değişimlerin telsiz dalgaları üzerindeki bükülme (kırılma) katsayısını ölçümlemek.
* **Afet Haberleşmesi:** Olası atmosferik anomalilerde veya iyonosferik kesintilerde, VHF/UHF üzerinden alternatif uzak mesafe (DX) Simplex hatları haritalandırmak.
* **Rölesiz Erişim:** Bursa merkezli olmak üzere minimum 150 km (İstanbul) ve 250 km (İzmir) mesafelerdeki istasyonlarla doğrudan iletişim sağlamak.

---

## Teknik Donanım Altyapısı
* **Telsizler:** Minimum 25W–50W çıkış gücüne sahip VHF/UHF Mobil/Araç telsizleri (Yedek olarak 5W-8W el telsizleri).
* **Antenler:** 
  * VHF için minimum 5 elemanlı Yagi-Uda yönlü anten.
  * UHF için minimum 7 elemanlı Yagi-Uda yönlü anten.
  * İstasyonlar arası genel çağrılar için yüksek kazançlı dikey omni antenler (Diamond X-300 / X-500).
* **Konnektör ve Kablo:** Maksimum 10 metre uzunluğunda düşük kayıplı LMR-400 veya RG-213 koaksiyel kablolar.
* **Yazılım:** Dijital zayıf sinyal takibi için **WSJT-X (FT8 / FT4 modları)**.

---

## Operasyon Zaman Planı

| Faz | Zaman Dilimi | Yapılacak Faaliyet |
| :--- | :--- | :--- |
| **Faz 1: Referans** | Tutulmadan 2 saat önce | İstasyon kurulumları, azimut ayarları ve gürültü (noise) seviyesi tespiti. |
| **Faz 2: Kritik Evre** | Tam Tutulma (Totality) Anı | Sürekli modda Simplex sesli (FM) ve veri (FT8) çağrıları, RSSI kayıtları. |
| **Faz 3: Normalleşme** | Tutulmadan 1 saat sonra | Atmosferik kanalın (ducting) dağılma süresinin ve sinyal sönümlenmesinin takibi. |

---

##  Frekans Planlaması

* **VHF FM (Ses):** 145.500 MHz (Alternatif: 145.525 MHz / 145.550 MHz)
* **VHF FT8 (Dijital):** 144.174 MHz
* **UHF FM (Ses):** 433.500 MHz (Alternatif: 433.525 MHz)

---

##  Katılımcı Amatör Telsizciler ve İstasyon Listesi

Projede aktif görev alacak operatörlerin, konumlarının ve kullanacakları ana ekipmanların listesi aşağıdadır:

| Çağrı İşareti (Callsign) | Operatör Adı | İstasyon Konumu / Bölgesi | Ana Ekipman & Anten |
| :--- | :--- | :--- | :--- |
| **TB3FLY** | Abdurrahman Balı | Bursa / Uludağ Üniversitesi (KN40LG) | Yaesu FT4X + DUAL |
| **TA3ROM** | Ahmet Erginer |  Bursa / Uludağ Üniversitesi (KN40LG) | ** |
| **TA3CEP** | Mert ** |  Bursa / Uludağ Üniversitesi (KN40LG) | **|
| **TA3KAG** | Osman Kağan Tura | Bursa / Uludağ Üniversitesi (KN40LG) | ** |


---

##  Veri Kayıt Protokolü (Logbook)
Her istasyon gerçekleştirdiği başarılı veya başarısız çağrılar için aşağıdaki şablona uygun veri tutacaktır:

```text
[GG/AA/YYYY] [UTC SAAT] | [ALICI CALLSIGN] | [MOD: FM/FT8] | [SİNYAL RAPORU (R-S)] | [ANLIK SICAKLIK (°C)] | [NOTLAR]
Örnek:
24/07/2026 11:42 | TA1BBB | FM | 5 by 7 | 18.5°C | Sinyal ani yükseldi, qsb var.
```

---

##  Önemli Uyarılar
1. Testler kesinlikle **Röle (Repeater) veya Link sistemleri üzerinden yapılmamalıdır**. Tüm iletişim doğrudan (Simplex) olmalıdır.
2. Acil durum frekansları (Örn: TRAC Afet Frekansları) test amacıyla işgal edilmemelidir.
3. Dijital modlar kullanılmadan önce bilgisayar saatlerinin **GPS veya İnternet üzerinden tam senkronize** edildiğinden emin olunmalıdır.

---


