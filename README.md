 ### **Komutlara giriş 2:**

  # WİLCARD KAVRAMI
  
- Komutları yazarken kriter oluşturmamızı sağlayan özel karakterlerdir.
- Filtreleme işlevi görür.
- Zaman kazandırır.

Bu wilcard terimleri 3 tanedir. Bunlar:

1)  *(yıldız)--> Bir veya birden fazla karakterin yerine geçebilecek bir joker karakterdir.
2) [] (köşeli parantez)-->  Yerine geçeceği karakterleri küme şeklinde belirten bir wilcard operatörüdür.
3) ? (soru işareti)--> Yalnızca bir karakterin yerine geçebilecek bir joker karakteridir.
- ---

Örnek 1:
 
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/9e37b137-57c8-42e6-b28b-b03a828b1cee"/>
<div>




- ---

Örnek 2:

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/791eeb01-e37a-4b07-9c0b-832430fef786"/> 
<div>



- ---

Örnek 3:    

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/1851eb97-5c0e-4e05-9bb7-2d86bebc09fa"/>
<div>
   


---

Örnek 4:
  
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/269ca173-514d-4c9a-b181-864716d410c5"/>

<div>
   

---
Örnek 5:

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/add49fe2-578e-495f-84a2-dfca30423a55"/>
<div>

 

---
  
Örnek 6:

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/bdd5d94b-fc35-4228-8267-a109dea532b1"/>
<div>

 
---
Yönlendirme Operatörleri:

- Komutların girdi ve çıktılarını yönlendirmemizi sağlar.
  
1) bir tane büyüktürişareti : Bir programın veya bir komutun çıktısını bir başka dosyaya tamamen yazmamızı sağlar.
  
2) iki tane büyüktür işareti : Bir programın veya bir komutun çıktısını bir başka dosyanın sonuna eklememizi sağlar.
  
Örnek 1: yazi.txt dosyasının içindeki bilgileri mayis dosyasının içine aktarna işlemi yapılıyor.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/b2041098-5b3f-42f0-9426-08c702d0c099"/>
<div>
  
---

Örnek 2: yazi.txt dosyasının içindeki bilgileri mayis dosyasının sonuna aktarna işlemi yapılıyor.

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/020d1b6a-a8f2-4b93-8902-51a39993376b"/>
<div>
 

---
  
Pipe Kullanımı:
  
- Komutlarımız çıktılarını bir başka komuta girdi olarak veren operatördür.
- Pipe işaretini klavyeden alt gr + -

Örnek 1: 

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/00e1f902-f2ce-4a7e-9d98-08f292530050"/>
<div>
  
---

Örnek 2: 
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/22d57a23-a116-4ed1-85a9-da92f347b3a7"/>
<div>


---

Kullanıcı Nedir?
  
- Linux, çok kullanıcılı bir sistemdir.
  
- Birçok program, sunucu yazılımı, komut; çok kullanıcılı sistem üzerinde çalışır.
  
- Kullanıcılar 2'ye ayrılır: Bunlar:
  
1) Genel amaçlı Kullanıcılar:

- Kendilerine veya gruplarına tanımlı yetkileri kullanırlar.
  
- Ev dizinleri /home dizini altında bulunur.
  
2)Root Kullanıcısı:
  
- Tüm yetkilere ve erişimlere sahiptir.
  
- Sistem seviyesinde yetkiler için kullanılır.
  
- Ev dizinleri /root dizinidir.

---

Grup Nedir?
  
- Birden fazla kullanıcının bir arada bulunduğu erişim gruplarıdır.
  
- GID = Grup ID
  
- Bir kullanıcı birden fazla gruba üye olabilir.
  
- Grup üyelikleri /etc/group altına tanımlanır.
  
- Örnek olarak çizimler grubuna mimarlar mimarlar yetkilendirilebilir. Veya kodlar grubuna mühendisle yetkilendirilebilir.
  

---

- Kullanıcı parolalarının olduğu yerdir. Önceden bu parolalar passwd içinde bulunurmuş.


 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/108a3718-b110-4e5e-8970-68f42584b923"/>
<div>


---

 - /etc/shadow içinde bulunan bilgilerin içinde 2. sütunda ünlem işareti vasra oraya parola dahil olmaz üzere girilemeyeceğini  belitir.

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/186554d3-601c-4cef-a629-5d7f8adbefd2"/>
<div>

--- 

- etc/shadow
	
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/5e96b340-e0f8-48e5-bc96-e799d4fb3af0"/>

<div>



---

- `ismail@kaya:~$file DosyaAdi `---> Dosyanın ne tür bir dosya olduğunu öğrenebiliriz.
	
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/0b39830e-81e3-434e-a9b9-db245f7dfbe1"/>

<div>



---

- `ismail@kaya:~$wc DosyaAdi `---> Dosya hakkında bilgi alırız.(Satır sayısı, kelime sayısı, dosyanın bayt türünden dosya boyutu)

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/a4672a1c-997e-4d1b-aa99-bf341316788b"/>
<div>



---

- `ismail@kaya:~$wc -w DosyaAdi`---> Dosyanın içinde kaç kelime olduğunu öğreniriz.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/c18687a3-0e5a-46b9-8fb6-fa6a5fab7b9f"/>

<div>


---

- `ismail@kaya:~$wc -l DosyaAdi`---> Dosyanın içinde kaç satırdan oluştuğunu öğreniriz.
	
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/de2768cb-297c-4a07-b6cf-aeeb5c92f106"/>

<div>



---

- `ismail@kaya:~$wc -c DosyaAdi`---> Dosyanın kaç byte olduğunu öğreniriz.
	
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/d48d70a1-fa2b-4cca-896a-4eb51bd68ab1"/>

<div>



---

- `ismail@kaya:~$wc -L DosyaAdi`---> Dosyanın içindeki en uzun satırın kaç harften oluştuğunu öğreniriz.
	
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/9d3d8332-4826-4f5e-9efe-250f2378170f"/>

<div>



---

-  `ismail@kaya:~$man KullanmayiÖgrenmekIstedigimizKomut`---> Kılavuzu bulunan komut ve programların kılavuzlarını okur.

	
---

-  `ismail@kaya:~$head DosyaAdi`---> Bir dosyanın ilk 10 satırını yazdırır.

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/c62036e7-e552-4e80-96b0-3d452aee072a"/>

<div>

---

-  `ismail@kaya:~$tail DosyaAdi`---> Dosyanın son 10 satırını yazdırır.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/442b8446-a815-40b2-97dc-32a47bccec8e"/>
<div>
	

---

-  `ismail@kaya:~$more DosyaAdi`---> Terminal ekranına sığmayan metinleri okumayı kolaylaştırır.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/393b69f7-43a3-43b7-9c31-da01bda56a69"/>

<div>

---

-  `ismail@kaya:~$nl DosyaAdi`---> Boş olan satırlar hariç diğer satırlara satır numarası ekler.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/61f77e5f-6949-47e1-8d0b-e66b32207041"/>

<div>

---

-  `ismail@kaya:~$sort DosyaAdi`---> Dosyanın içinde yazan yazıları sırası ile yazdırır.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/806a33d8-3780-4761-8099-5b9614a3def3"/>

<div>

---

-  `ismail@kaya:~$sort -R DosyaAdi`---> Dosyanın içindeki bilgileri karışık olarak sıralar.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/40124014-3785-40d2-8d0b-c308c4b2405a"/>

<div>

---

-  `ismail@kaya:~$sort -r DosyaAdi`---> Dosyanın içindeki bilgileri tersten sıralar.


---

-  `ismail@kaya:~$sort -c DosyaAdi`---> Yandaki komut ile dosyanın sıralı olup olmadığını bize söyler.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/00321265-645b-4d37-bb84-89d1bc86369d"/>
<div>


---

- `ismail@kaya:~$sort -k DosyaAdi`---> Yandaki komut dosyaları belirttiğimiz sütundan sıralamamızı sağlar.
-  `ismail@kaya:~$sort -k SayiDegeri DosyaAdi`---> Yandaki komut dosyanın verdiğimiz sayının sütununda bulunan satıra göre sırayla listeler.
-  `ismail@kaya:~$sort -k SayiDegeri DosyaAdi`--->  Yandaki komut dosyanın verdiğimiz sayının sütununda bulunan satıra göre tersten sıralamayla listeler.
