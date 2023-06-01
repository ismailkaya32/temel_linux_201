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
</div>

- ---

Örnek 2:

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/791eeb01-e37a-4b07-9c0b-832430fef786"/> 
</div>

- ---

Örnek 3:    

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/1851eb97-5c0e-4e05-9bb7-2d86bebc09fa"/>
</div>
   
---

Örnek 4:
  
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/269ca173-514d-4c9a-b181-864716d410c5"/>

</div>
   
---
Örnek 5:

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/add49fe2-578e-495f-84a2-dfca30423a55"/>
</div>

---
  
Örnek 6:

<div>
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/bdd5d94b-fc35-4228-8267-a109dea532b1"/>
</div>

---

#### Yönlendirme Operatörleri:

- Komutların girdi ve çıktılarını yönlendirmemizi sağlar.
  
1) Bir tane büyüktür işareti : Bir programın veya bir komutun çıktısını bir başka dosyaya tamamen yazmamızı sağlar.
  
2) İki tane büyüktür işareti : Bir programın veya bir komutun çıktısını bir başka dosyanın sonuna eklememizi sağlar.

---
  
Örnek 1: yazi.txt dosyasının içindeki bilgileri mayis dosyasının içine aktarna işlemi yapılıyor.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/b2041098-5b3f-42f0-9426-08c702d0c099"/>
</div>
  
---

Örnek 2: yazi.txt dosyasının içindeki bilgileri mayis dosyasının sonuna aktarna işlemi yapılıyor.

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/020d1b6a-a8f2-4b93-8902-51a39993376b"/>
</div>
 

---
  
#### Pipe Kullanımı:
  
- Komutlarımız çıktılarını bir başka komuta girdi olarak veren operatördür.
- Pipe işaretini klavyeden alt gr + -  ile yaparız.

Örnek 1: 

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/00e1f902-f2ce-4a7e-9d98-08f292530050"/>
</div>
  
---

Örnek 2: 
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/22d57a23-a116-4ed1-85a9-da92f347b3a7"/>
</div>

---

#### Kullanıcı Nedir?
  
- Linux, çok kullanıcılı bir sistemdir.
  
- Birçok program, sunucu yazılımı, komut; çok kullanıcılı sistem üzerinde çalışır.
  
- Kullanıcılar 2'ye ayrılır: Bunlar:
  
##### 1) Genel amaçlı Kullanıcılar:

- Kendilerine veya gruplarına tanımlı yetkileri kullanırlar.
  
- Ev dizinleri /home dizini altında bulunur.
  
##### 2) Root Kullanıcısı:
  
- Tüm yetkilere ve erişimlere sahiptir.
  
- Sistem seviyesinde yetkiler için kullanılır.
  
- Ev dizinleri /root dizinidir.

---

#### Grup Nedir?
  
- Birden fazla kullanıcının bir arada bulunduğu erişim gruplarıdır.
  
- GID = Grup ID
  
- Bir kullanıcı birden fazla gruba üye olabilir.
  
- Grup üyelikleri /etc/group altına tanımlanır.
  
- Örnek olarak çizimler grubuna mimarlar mimarlar yetkilendirilebilir. Veya kodlar grubuna mühendisle yetkilendirilebilir.
  

---

- /etc/shadow  kullanıcı parolalarının olduğu yerdir. Önceden bu parolalar passwd içinde bulunurmuş.


 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/108a3718-b110-4e5e-8970-68f42584b923"/>
</div>


---

 - /etc/shadow içinde bulunan bilgilerin içinde 2. sütunda ünlem işareti varsa oraya parola dahil olmaz üzere girilemeyeceğini  belitir.

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/186554d3-601c-4cef-a629-5d7f8adbefd2"/>
</div>

---

- root kullanıcısı olarak useradd komutu ile yeni kullanıcı ekleyebiliriz.
	
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/12362093-d475-4b7a-b723-b2eb40bac2e9"/>
</div>

---

- root kullanıcısı olarak passwd komutu ile istediğmiz kullanıcıya yeni şifre ekleyip değiştirebilirz.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/52e67099-bde7-49e8-896c-9ebd0662be16"/>
</div>

---

- root kullanıcısı olarak deluser komutu veya userdel komutu ile ekli olan istediğimiz kullanıyı silebiliriz.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/bd6c29e1-6ae9-49f9-90fd-fdc806255eef"/>
</div>
	
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/42f68f46-b63a-47c4-8821-969948f01897"/>
</div>

---

- `cat /etc/group` komutu ile birlikte sistemde tanımlı olan bütün grupları isimleri ve ID'leri ile görebiliriz.
	
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/c7454d12-5a44-4e98-850e-f484d3ae5a61"/>
</div>

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/f846f1a1-d157-4ee9-9910-2983a2f4063a"/>
</div>

---

-  root kullanıcısı olarak addgroup komutu ile yeni bir grup ekleyebiliriz.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/d83e2651-7f88-4b10-9214-67ff0938dd0f"/>
</div>
	
---

- root kullanıcısı olarak delgroup ile ekli olan istediğimiz grubu silebiliriz.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/db3fb797-a0e4-4d52-9392-887b0f2d6aab"/>
</div>

---

-  Kullanıcı Değiştirme Örneği: Aşağıdaki örnekte chown komutu ile ismailkaya kullanıcısına ait kaya adlı dosyanın kullanıcısını mavi adlı kullanıcı olarak değiştirdik.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/628168b1-3c33-424e-834a-8c148e0dac63"/>
</div>

---

-  Toplu Olarak Kullanıcı Değiştirme Örneği: Aşağıdaki örnekte chown komutu ile ismailkaya kullanıcısına ait deneme ve yazi.txt adlı dosyaların kullanıcısını mavi adlı kullanıcı olarak değiştirdik.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/d03a2cca-0796-46c0-a596-ca224fbe596e"/>
</div>

---

-  Grup Değiştirme Örneği: Aşağıdaki örnekte chgrp komutu ile ismailkaya grubuna ait kaya adlı dosyanın grubunu siyah adlı grup olarak değiştirdik.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/f4f1267a-d5bc-4182-a38f-89321076ce39"/>
</div>

---

-  Toplu Olarak Grup Değiştirme Örneği: Aşağıdaki örnekte chgrp komutu ile ismailkaya grubuna ait deneme ve yazi.txt adlı dosyaların grubunu siyah adlı grup olarak değiştirdik.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/cc888805-d845-4d8f-bbea-30e4791dfd4f"/>
</div>

---

##### Sahip Kullanıcı ve Sahip Grup Tanımı:

<div align="center">
	<img
src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/3c01f7c6-c993-403a-94cf-de2b585924fa"/>
</div>

---

##### Dosya İzinleri:

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/013728dc-42c1-45b4-a113-ecc4cfad0380"/>
</div>


##### Dosya İzinlerini Gruplandırma: 

- Aşağıdaki örnekte göreceğimiz üzere dosya izin gruplandırmaları 3'e bölerek oluyor.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/bb387f63-f02f-45a4-a651-58263fff1677"/>
</div>

---

- Dosya İzin Ekleme Örneği: Aşağıdaki örnekte gördüğümüz üzere yazi.txt dosyasında çalıştırma izni bulunmamaktadır. `chmod +x yazi.txt` komutu ile kullanıcıya, gruba, kullanıcı ve grup dışındakilerin hepsine çalıştıma izni veriyoruz.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/3ea37285-c3ff-4ba6-a92e-7a1d03368bb4"/>
</div>

---

- Dosya İzin Silme Örneği: Aşağıdaki örnekte gördüğümüz üzere yazi.txt dosyasında çalıştırma izni bulunmaktadır. `chmod -x yazi.txt` komutu ile kullanıcının, grubun, kullanıcı ve grup dışındakilerin çalıştıma iznini geri alıyoruz.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/7a133bd9-de09-496a-9b44-01b12cf98af3"/>
</div>

---

##### Dosya İzinlerinin Sayısal İfadesi:

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/0f37aa24-18a4-4959-a0ca-9452bd06b76c"/>
</div>

---

Örnek: Aşağıdaki örnnekte göreceğiniz üzere ilk başta dosya izin değeri 644 olan yazi.txt dosyasının iznini 555 yaptık. 
- Yani önceden kullanıcı; okuma ve yazma, 
- grup; sadece okuma, 
- kullanıcı ve grup dışındaki kişiler; sadece okuma yaparken şimdi ise
- kullanıcı; okuma ve çalıştırma
- grup; okuma ve çalıştırma
- kullanıcı ve grup dışındaki kişiler; okuma ve çalıştırma yapabilmektedir. 

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlar-_201/assets/122615472/2a656eed-4dd6-4e1c-9914-a76ade037aa3"/>
</div>
