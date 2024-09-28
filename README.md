# JavascriptNot
Kendi tuttuğum Javascript Notlarıdır.




            -JAVASCRİPT NEDİR?  DERS 1 -
WEB SAYFALARININ %97 SİNDE JS KULLANILIR.
MOBİL OYUN VERİ ANALİZ GİBİ ÇOĞU ALANDA KULLANILIR.

JS FRONTEDDE SLİDER YAPIMI SEARCH ALANI GİBİ 
BACKENNDE NODEJS ALANINDA
MOBİLDE REACT NATİVE ALANINDA

BİZLER JS İ CLİENT TARAFINDA KULLANACAĞIZ.
CLİENT İÇİNDE BİR SERVERİMİZ VARDIR. BU SERVERLAR İNTERNET İÇERİSİNDE SÜREKLİ ÇALIŞAN BİR PC GİBİDİR.
TARAYICIMIZ BİR CLİENTTİR.
DOMAİN ADIMIZI CLİENTTE ARATIRIZ. VE CLİENT SERVERDA BİR İSTEKTE BULUNUR.
DOMAİNİMİZ ASLINDA BİR İP DİR. SERVERA BAĞLI İP YE İSTEK ATINCA SERVERDA O İP ALTINDA NE VARSA BİZLERE GERİ DÖNER.
BİZLER FULL CLİENT TARAFINDA ÇALIŞACAĞIZ.

          
          
          
            -    GENL JS YAPISI    DERS 2 -
js i sunucu tarafında çalışıtrmak için node js i kullanmalıyız
tarayıcı tarafında da js kullanılabilir.


eğer js kodlarımızı terminalimizde çalıştırmak istiyorsak yani server tarafında bunun için node js i kullanmamız gerekir.
node u kurduktan sonra terminalimizi açarız js zaten terminalde yazılır. terminal ksayolu  ctrl+   "   işaretidir.
işlem yapacağınız dosyanın olduğu dizini terminalde açtıktan sonra = bu işlemi yaparken cd dosya ismi ile giriş yaparız.

PS C:\Users\hpvic\OneDrive\Masaüstü\front end road map> cd javascript-tutorial
PS C:\Users\hpvic\OneDrive\Masaüstü\front end road map\javascript-tutorial> cd JAVASCRİPT-GENEL-YAPİ

terminalde node index.js(index.js sizin js dosyanızın ismi ) diyerek js dosyamızı çalıştırabiliriz.



bir web sayfasında f12 tuşu ile developer toolsa erişiriz. dev toolsda console bölümünde html dosyamıza bağlı js dosyamzın işlemlerini görürürz. 
yani bizler js i bu işlemde tarayıcıda yazarız 

front end tarafında js kullanmak için html de yani tarayıcıda çalışılır. 
back end tarafında s kullanmak için terminalde yani sunucuda çalışılır.

            
            
           
           
           
                                                 - JS DEĞİŞKENLER DERS 3-
tüm progrmalama dillerinde programlarda geçici olarak saklayacağımız öğeleri dğeişkenlerde saklarız.

örneğin bir ad ve soyad ögesini saklamak için :
let ad = "kubilay";
let soyad="taşkafa";

bunu consol a yazdırmak  için :
clg yazdığımızda console.log() açılacak bizler console.log ile konsola yazdırma işlemi yaparız.

örnek uygulama:

let ad = "kubilay";
let soyad = "taşkafa ";

console.log(ad, " ",soyad);

run= kubilay   taşkafa 

#bizler değişken değerlerini 1 kere atayıp istediğimiz kadar kullanabiliriz.
#ayrıca diyelim ki bir ögeyi birden fazla yerde kullandık. ve b u ögeyi değiştirmemiz gerekiyor.eğer değişken kullanamdan bu işlemi yaparsak
#örnek olarak 100 satırlık kodda teker teker o öge değerini değiştirmek gerekir.
#bunun yerine ögeyi değişkene bağlayıp kullanırsak sadece değişken kısmında yapacağımız değişiklikle bu işlemi halledebiliriz. 

örnek : 

let mudurAdi = "ahmet";
let sinifBaskani = "kubilay";

console.log("müdür adi:" + mudurAdi);
console.log("sınıf başkani  adi:" + sinifBaskani);

not= burada müdür değiştiği anda değişkendeki ismi değiştiririz ve bu sayede bu değişke 100 satırda kullanılsa bile 100 satırda tek hareketle değişiklik yapmış oluruz. 

#değişkenlerimize belirli işlemleri ekleyebiliriz. örneğin maaş ve zam oranını değişkene bağlayıp zamlı maaşımızı bulan bir değişken atayabilriiz.

örnek uygulama:
let maas = 5000;
let zam = 0.2;

let zamliMaas= maas+maas*zam

console.log(zamliMaas)

not= burada maas ve zam oranları değiştikçe zamlımaas değişkeni farklı değerler verecek bu sayede belirli işlemleri değişkenlere atayarak daha hızlı işlem yapabiliriz.
değişken olmadığı takdirde bu işlemleri teker teker yapmamız gerekecek

değişken tanımlamak için let ve const kullanırız. 
let = daha sonra değişiklik yapabildiğimiz değişken keyidir.
örnek olarak bir isim değerini değiştirmek istersek let name="kubilay" olarak tanımlarız .
 const= daha sonradan değişklik yapamadığımız değişken keyidir.
 örnek olarak sistemi açan bir değişmeyecek şifreyi const password=12232 olarak tanımlarız .

 alt satırlardaki işlemlerde let keyine bağlı değişken değişebilirken const keyine bağlı değişken değiştirilemez 


     
      
      
      
                                          -DEĞİŞKEN TÜRLERİ DERS 3-

string veri türü :
bir isim vb yazı öğeleri string veri türüdür. burada yazı ögesindeki her bir harf ve boşluk karakter olarak bellekte depolanır .

örnek olarak let name="kubilay" bu değişkenimizin türü stringtir.

string değerler tırnak içinde yazılmalıdır. aksi takdirde program string değeri okumaz hata alırız. 


değişken tipini öğrenmek için typeof  operatörünü kullanırız. typeof dedikten sonra değişken adını kullanmamız gerekir.
örnek kullanım :

let name = "kubilay taşkafa ";

console.log(typeof name);


number veri tipi :
sayı ögeleri number veri tipidir. 

let password=12321 gibi 

number veri tipinde tırnak işareti kullanılmaz eğer tırnak işareti kullanılırsa program değeri string olarak algılar .
let password="2341" değeri typeof ile kontrol edildiğinde string olarak çıkar.

örnek problem 
let sayi1="10";
let sayi2="20";

let toplam=sayi1+sayi2

console.log(toplam)
burada toplama işlemi sonucu 30 çıkması gerekirken program değerleri string alıp topladığı için yan yana yazılır. 1020 olarak çıkar .
biz veri tiplerini dönüştürebiliriz. 
öreneğin yukarıdaki sayi1 ve sayi 2 ögesini number veri tipine dönüştürmek için Number operatörünü kullanabiliriz. 
Number(sayi1)
Number(sayi2)
bu şekilde string olan ifadeyi number ver tipine dönüştürdük.

let sayi1="10";
let sayi2="20";

let toplam=Number(sayi1)+Number(sayi2)

console.log(toplam)

YUKARIDAKİ KODLAMADA KONSOLUMUZDA 30 YAZACAKTIR. 

bir number değerini toString operatörü ile stringe çevirebiliriz. 

let number1=10;
let number2=20;

console.log(number1.toString())

burada number değerini toString fonksiyonu ile string bir ifadeye çevirdik 
örnek uygulama:
let number1=10;
let number2=20;
toplam=number1.toString()+number2.toString()

console.log(toplam)

bu kodlamada normalde number1 ve number2  number veritipi olduğu için toplamları 30 olmalıdır. fakat bizler toSTring kullandığımız için 
ikisi de string ifade olur ve string toplamada iki string yan yana yazıldığı için 1020 çıktısı alırız.


boolean veri tipi:
boolean veri tipi true ve false dır .
0 ve 1 diye de adlandırılır. 1==true 0 ==false 

örneğin 
sayi1=10
sayi2=20

console.log(sayi1 > sayi2 )

bu kodlamada konsolumuzda false çıktısı alacağız bu da boolean veri tipini verir.

undefined veri tipi:
undefined veri tipi tanımlanmamış veri tipidir. örnek olarak bir değişken oluşturup tanımlama yapmazsanız bu değişkenin veri tipi undifined olur.

let ogrenciİsmi;  ==> bu değişkenin veri tipi undefined dır .

                  
                  
                  
                  
                  
                     
                        -JAVASCRİPT DEĞİŞKENLER UYGULAMA DERS 4-

/* 
SHİFT+ALT+A ÇOKLU YORUM SATIRI AÇAR

*/
/* 
    ÖGRENCİ BİLGİLERİ 
    1-kubilay taşkafa
    dogum tarihi 2003
    bilgisayar notları 90 100 30
    
    2-şeyma gül 
    doğum tarihi 2004
    bilgisayar notları: 60 30 40
    
    3-

    geçer not=45 

    program şartları: 
    1-öğrencilerin yaşlarını hesaplayınız.
    2-öğrencilerin ders ortalamasını hesaplayınız.
    öğrencilerin dersten kalıp kalmadığını öğrenelim

    */
let mevcutYİl = new Date().getFullYear();  // bilgisayardaki mevcut yılı bulmak için kullanılan method

let ogr1 = "kubilay taşkafa";
let ogr1Dogumt = 2003;
let ogr1Yas = mevcutYİl - ogr1Dogumt;
let ogr1Not1 = 90;
let ogr1Not2 = 100;
let ogr1Not3 = 30;
let ogr1ORt=(ogr1Not1+ogr1Not2+ogr1Not3)/3
let ogr1DersDurum=ogr1ORt>45
console.log(parseInt(ogr1ORt))    // parseInt ile ondalıklı sayının sadece tam kısımlarıno yazdırırız.


let ogr2 = "şeyma gül";
let ogr2Dogumt = 2004;
let ogr2Yas = mevcutYİl - ogr2Dogumt;
let ogr2Not1 = 60;
let ogr2Not2 = 30;
let ogr2Not3 = 40;
let ogr2ORt=ogr2Not1+ogr2Not2+ogr2Not3/3
let ogr2DersDurum=ogr2ORt>45


                            
                            
                                -JAVASCRİPT OPERATÖRLER DERS 5-

4 adet operatörümüz vardır:

1-       aritmetik OPERATÖRLER
aritmetik operatörler işlem operatörleridir.   

+ toplama
- çıkarma 
* çarpma 
/ bölme 
% mod alma=bölümünden kalan sayıyı bulma genelde sayı tek mi çift mi bulmak için yapıyoruz. 

++  == bu işlemde ++ işlemi sağa konursa sayıyı değişkene bağladıktan sonra sayıyı 1 arttırır örnek: 
number=10;
result = number++;
bu işlemde resulta number değeri 10 olarak atanır daha sonra number değeri 11 olur .

sola konursa number önce kendine 1 ekler ve sonra değişkene bağlanır. 
number=10;
result =++number;

burada number kendine 1 ekleyerek 11 olacak ve değişkene bağlanacak 

--  == bu işlemde -- işareti sağ tarafa konursa önce değer değişkene bağlanır sonra bir eksilir.
        -- işareti sol tarafa konursa önce değer bir eksilir sonra değişkene bağlanır.


2 -      atama öperatörleri

klasik değişkene değer atama operatörleridir. 
= işareti ile değişkene değer atayabiliriz.
let a=10   burada artık 10 değeri a değişkenine bağlandı bizler programda 10 yerine a kullanabiliriz.

+=, -= , *= , /= , %= gibi işaretlemeler birer kısayoldur. 

number=number+1 demek yerine  number+=1 dediğimiz anda kısayoldan bu işlemi yapmış oluruz.



3-       Karşılaştırma Operatörleri
karşılaştırma yapılırken kullanılan operatörlerdir.

==  eşittir işaretidir.   2 tane eşittir işareti varsa sadece eşitliğe bakar.   
örnek: a=20   b=10       a==b  burada sadece a ile b değişkeni birbirine eşit mi diye bakarız.  sonuç true ya da false çıkar 

!=   bu işaretleme eşit değilse kontrolü yapar.

===   3 tane eşittir işaretlemesinde tip kontrolü yapılır.   örnek olarak a=10 ve b="10"  burada == ile kontrol yapılırsa sonuç true çıkar.
fakat === ile işlem yapılırsa sonuç false çıkacaktır. iki sayıda birim olarak 10 olsa bile a number tipinde b string tipinde olduğu için === işlemi bize false döndürür.
bu işlemde hem tip hem de değer kontrolü yapılır yani = a="10"  b="20"  burada === ile işlem yaparsak tipler uyuşsa bile değer uyuşmaz ve false döner.

<  küçüktür.
 
>  büyüktür.

>= büyük eşittir. büyük veya  eşitse true

<= küçük eşittir. küçük veya eşitse true 




4-       MAntıksal öperatörler

&&  ve operatörü:

ve operatörü ile en az 2 durumu değerlendiririz. ve operatöründe true sonucu almak için bütün durumların true olması lazımdır.
eğer bir tane durum bile false gelirse işlemin sonucu false olur. 

örnek:
let a =10;
let b=20;
let c=30;

let result= (a>b && c>b)  burada 2 tane durumu ve ile bağladık ilk durum false değeri verdiği için result değeri false gelecek 
let result= (a>b && c>b)  burada 2 tane durumu ve ile bağladık iki durum da true olduğu için result değeri true olacak 



||  veya operatörü

veya operatörü ile en az 2 durumu değerlendiririz. veya operatöründe en az bir tane true değeri alınırsa sonuç true olur.
sonucun false çıkması için bütün durumların false değerini vermesi gerekir.

örnek:
let a =10;
let b=20;
let c=30;
let result= ( a>b || c>b )  burada 2 tane durumu veya ile bağladık. 2. durum true olduğu için result değişkeni true olacak 
let result =  ( a>b || c<b ) burada 2 tane durumu veya ile bağladık. 2 durum da false olduğu için result değişkeni false olacak 


!  tersi operatörü 
tersi operatörü değili işlemini yapar. bir durumun başına ünlem eklersek yani tersi işlemini yaparsak burada 
örnek:

let a =10;
let b=20;
result=!(a>b)
console.log(result)

bu işlemde result sonucu normalde false değerini verir çünkü 10 20 den büyük değildir.
fakat tersi operatörü (!) kullandığımız için result sonucu true değerini verecektir.


               
               
               
                    -JAVASCRİPT İF ELSE DERS 6-
if else koşullu ifadelerdir. bir durum olursa şu olsun gibi 

if eğer demektir.
kullanımı: 
if(bu kısım paremetredir.burası karşılandığı sürece ){
    bu kısım blok kısmıdır. parametre karşılandığında bu bloktaki işlemler çalışır.}

örnek:
let login=true;

if(login==true){
    console.log("çalıştı.")
}

burada js yukarıdan aşağı okuma yapar. loginin true olduğunu görür.
if sorgusunda parametre login true mu diye sorgu yapar. parametre sağlandığı için 
if bloğu çalışır ve konsola çalıştı yazar.

eğer if parametresi karşılanmazsa js bu bloğu okumadan atlar.

else değil ise demektir. bir if sorgusu yaptığınızda eğer sorgusu yaparsınız.
bu sorgunun değil ise sorgusunu yapabilmek için else kullanabilirsiniz.

else kullanımı: else in bir parametre almasına gerek yoktur. 
else in parametresi if sorgusunun karşılanmaması gibi düşünülebilir.
else kullanırsak if karşılanmadığı anda js else bloğunu okur.

örnek olarak:

let login=false;

if(login==true){
    console.log("çalıştı.")
}
else{
    console.log("çalışmadı")
}

burada if parametresi karşılanmadı ve js if bloğunu atladı.
else kullandığımız için otomatik olarak else bloğu çalıştı ve konsola çalışmadı yazdırdı.

gelişmiş örnek:


const username = "kubilaytaskafa";
const password = "12345";

if (username == "eminbasbayan") {
  if (password === "12345") {
    console.log("giriş yapıldı");
  } else {
    console.log("şifre yanlış!");
  }
} else {
  console.log("kullanıcı bulunamadı");
}
burada username ve password üzerinden bir sorgu işlemi yaptık .
iç içe if sorgularını  kullandık.
! önemli hatırlatma: bu işlemlerde daha titiz bir kullanım istersek sorgulamalarda tip kontrolünü de yapmalıyız.

              
         
         
         
         
              - JAVASCRİPT İF ELSE UYGULAMA DERS 7-
BU UYGULAMAMIZDA DEĞİŞKENLERİMİZE GÖRE EHLİYET ALIP ALAMADIĞIMIZI GÖSTEREN BİR UYGULAMA YAZACAĞIZ.
uygulama:

let yas=17;
let mezuniyet="üniversite";

// yaş 18 ve büyükse ve mezuniyeti lise ya da üniversite ise 
if (yas>=18 && (mezuniyet=="lise" || mezuniyet=="üniversite")){
    console.log("ehliyet alabilir.") 
}else if(yas==17){    // birden fazla if sorgusu yani fi bloğu kullanmak için ilk iften sonraki sorgulardda else if kullanılır.
    console.log("a1 ehliyet alabilir.")
}
else{   // if bloğu çalışmazsa
    console.log("ehliyet alamaz")
}



            
              -JAVASCRİPT STRİNGLER DERS 8-
stringler birden fazla karakterin yan yana gelmesiyle oluşan yapılardır.

stringler birbiriyle toplanabilir.yani birden fazla stringi toplayarak işlem yapabilir cümle kurabilirsiniz.
örnek olarak:

const ad = "kubilay";
const soyad = "taskafa";
const yas = 21;
const meslek="front-end developer"
const bio="benim adım "+ad+" soyadım "+soyad +" yaşım "+ yas+" mesleğim "+ meslek;

console.log(bio)

burada konsola benim adım kubilay soyadım taşkafa yaşım 21 mesleğim front end developer çıktısını alacağız.
! stringlerde toplama işleminde boşlukları kendimiz vermeliyiz istersek  +" " şekline istersek yukarıdaki gibi ifadelerin içerisinde boşluk verebilriiz.

bu işlemi kullanabilirsiniz fakat bu işlemi uygularken çok fazla zaman kaybedersiniz.
ve fazlaca hata alabilirsiniz.

bizler bu işlemi yaparken template lateral işlemini kullanıyoruz.
bu işlemde backtickler kullanılır. backtick işaretini klavyede altgr+ virgüle 2 kere basarak kullanabiliriz.

! string ifadeler içerisinde javascript yazmak istiyorsak template literal kullanmak zorundayız.

nasıl kullanılır?
backtick içerisinde dolar işareti ($) ve süslü parantez ile javascript yazabiliriz.
dolar işareti=altgr+4 ile oluşur.

örnek uygulama:
yukarıdaki programı template literal yardımı ile yazdık.

const ad = "kubilay";
const soyad = "taskafa";
const yas = 21;
const meslek="front-end developer"

const newbio=`benim adım ${ad} soyadım ${soyad} yaşım ${yas} mesleğim ${ meslek}`
console.log(newbio)

burada konsola aynı çıktıyı aldık.



       
       
       
       
        -STRİNG METHODLAR DERS 9-
STRİNG METHODLARI STRİNG CLASS ININ İÇİNDEN GELİR.
!METHODLARI KULLANIRKEN () İLE KAPATMAK GEREKİR.

let youtube = "bilgisayar Genetiği";
let result;
result =youtube.toLowerCase(); // string harfleri küçültür.
result=youtube.toUpperCase()  // string harfleri büyültür.
result=youtube.length    // string içeriisnde kaç karakter olduğunu söyler. bu uygulamada stringi numbere çevirir
result=youtube.trim()  // string ifadelerde başta ve sondaki boşlukları siler
result=youtube.slice(0,6) //verilen değerler arasındaki karakterleri almaya yarar.
result=youtube.split(" ") //parametre değerine göre string ifadeyi ayırarak bir array oluşturur.
result=youtube[0]  // bu şekilde stringteki belirli bir karakterin index numarasını vererek o karakteri alabilirsiniz.
console.log(result);



  
    -STRİNG METHODLARI UYGULAMA DERS 10-

let url = "https://www.bilgisayargenetigi.com";
let youtube = "bilgisayar genetiği";
let result;
//! karakter sayısı bul
result = url.length;
result = youtube.length;

//!  boşlukları birleştir.
result = youtube.replace(" ", "");
//replace değiştirme işlemi yapar. ilk parametre değişmesini istediğiniz veri 2. parametre yerine gelecek veri

//! değişken kaç kelimeden oluşuryor.
result = youtube.split(" ").length;
//split parametrede verilen değer üzerinden string ifadeleri ayırarak array biçiminde yazdırır.
// örneğin , verseydik her virgülden sonra ayırma yaparak array biçiminde yazdırır.
// length ile arrayde kaç eleman var bulduk.

result = url.split(".").length;

//!  kanal adı başlangıç kontrol
result = youtube.startsWith("bilgisayar");
// startswith stringin ne ile başladığını sorgulamamıza yarar.
// eğer string parametre içerisindeki değerle başlıyorsa true aksi takdirde false çıktısı verir.
// örnek algoritma=
if (result) {
  // eğer result true ise konsola yapılacaklar yazdır.
  console.log("yapılacaklar");
} else {
  console.log("false döndü"); // if bloğu false ise
}

//! kelime kontrolü
console.log(youtube.indexOf("genetiği"));

// index of ile stringte kelime var mı yok mu kontrolü yapabiliriz.
//  eğer varsa index numarasını çıktı olarak verir.
// yoksa  -1 çıktısı verir.
// örnek algoritma:
if (youtube.indexOf("genetiği") > -1) {
  //eğer index of çıktısı -1 den büyükse yani bir bakıma string ifadede parametredeki ifade varsa
  console.log("çalıştı");
} else {
  console.log("çalışmadı");
}
//! url ve youtube değişken birleştir.
youtube = youtube.toLowerCase().replace(" ", "-");
// youtube değişkenindeki stringi küçük harflere çevir ve her boşluk olan yere - işareti ekle
url = url.replace("com", "com/");

let newUrl = url.replace(url, url + youtube);
//template literal ile yazma
newUrl = `${url}${youtube}`;
console.log(newUrl);


                             
                             
                                  -JS TERNARY OPERATOR DERS 11-
TERNARY OPERATOR İF VE ELSE BLOKLARININ DAHA KOLAY YAZILMASINI SAĞLAYAN YAZIM STİLİDİR.

kullanım şekli:
parametre ? parametre true ise çalışacak bölüm : else kısmı yani parametre false ise çalışacak kısım

burada soru işareti (?) if i temsil eder.
iki noktanın solundaki bölüm true  sağındaki bölüm false olma durumunda çalışacak bloğu temsil eder.
örnek:

// ternary operator kullanmadan
const username = "kubilaytaskafa";
const password = "1234565"; //length özelliği number da kullanılmaz.

if (password.length > 3) {
  console.log("çalıştı");
} else {
  console.log("çalışmadı");
}
// ternary operator ile tek satırda yazabiliriz.
password.length > 6 ? console.log("çalıştı") : console.log("çalışmadı");




          -JAVASCRİPT NUMBERS DERS 12-
number veri tipidir. sayılar number veri tipidir.
sayılar " " içerisinde tanımlanırsa tipi string olur.

bir veriyi number veri tipine çevirmek için:
Number() özelliğini kullanırız.

örnek:
const yas=Number("25");


number methodlarımız:


const username="kubilay"
const yas=21;
let result;
result=25;
result=Number("25"); //string değeri number a çevirme 
result=parseInt("25") //veriyi number a çevirir ve tam kısmını alır.
result=parseFloat("23.5") //veriyi number a çevirir ve ondalıklı kısım dahil hepsini alır.
// string ifadeleri number a çevirirken:
// eğer ifade başında string karakter varsa NaN(not a number çıktısı alırız.)
// eğer string ifade sonda ise sadece number olan veriyi çıktı alırız.
result=parseInt("a27")  // çıktı NaN
result=parseInt("27a")   // çıktı 27
result=isNaN("25") //bir verinin number olup olmadığını bulmamıza yarar. numara ise false değeri numara değilse true değeri döner.

let myNumber=10.500913;


result=myNumber.toPrecision(5) 
// ondalıklı sayının kaç basamağını alacağınacağını ayarlarız.
//alınacak son sayının bir sağındaki sayıya göre sayıyı yuvarlama işlemi yapar.


result=myNumber.toFixed(3)  
// ondalıklı sayılarda noktadan sonra kaç hane olacağını belirlemeye yarar.


result=Math.round(1.4); // sayı yuvarlamaya yarar.

result=Math.ceil(1,2) //sayıyı her zaman yukarı yuvarlar

result=Math.floor(1.2) //sayıyı her zaman aşağı yuvarlar.
 m  
result=Math.pow(2,3) //sayının kuvvetini alır.  (sayı,kuvvet)

result=Math.sqrt(10)  //sayının karekökünü alır.




console.log(result)



number methods araması ile methodlara ulaşabilirsiniz.


          -JAVASCRİPT DATES&TİMES DERS 13-
tarihlerimiz javascriptte Dates objesinden alınır.

dates objesi new Date() olarak kullanılır.

new Date() bize tarih ve saat bilgisini döndürür.


örnek kullanım:

let tarih=new Date()

console.log(tarih)

bu uygulamanın çıktısı  2024-07-22T09:33:18.335Z olarak döner.


Date objesi özellikleri:


let tarih = new Date();

let result;

//!get methods= pc üzerinden getirme methodları
result = tarih.getDate(); //! ayın hangi günündeyiz.
result = tarih.getDay(); //! haftanın hangi günündeyiz.
result = tarih.getFullYear(); //! güncel yılı alır.
result = tarih.getHours; //! güncel saati alır.
result = tarih.getTime(); //! güncel saati milisaniye cinsinden alır.

//! set methods= güncelleme methotları.
tarih.setFullYear(2025); //! parametre olarak yıl kesin almalı ay ve gün değeri opsiyonel
tarih.setMonth(2); //! tarihi güncellemeye yarar. burada önemli kısım parametre de 2 verirsek 3. ay olur. çünkü index 0 dan aylar 1 den başlar
tarih.setDate(15); //! günü güncellemeye yarar.

//! doğum Tarihi
//? bir insanın kaç yaşında olduğunu bulmak için Date objesi kullanılabilir.
let dogumTarihi = new Date(1996, 8, 14);

result = tarih.getFullYear() - dogumTarihi.getFullYear();

result = tarih;
console.log(result);


          -JAVASCRİPT ARRAYS(DİZİLER) DERS 14-
array tek satırda birden fazla veriyi saklamamızı sağlar.
örneğin bir e ticaret sitesindeki aynı kategorideki yüzlerce ürünü tek tek kaydetmek çok zor olur.
bunun yerine array içerisinde bu ürünleri listeleyip array içerisinden kullanabiliriz.

arrayleri bir değişkene bağlı olarak kullanabiliriz.

kullanımı:

const urunler=["samsung","apple","huawei"]

! arrayler her zaman sıfırdan başlar.
bu kuramda :
samsung 0. index
apple 1. index diye gider.

arrayler [] ile tanımlanır. her 2 veri arasında virgül bulunmak zorundadır.

arrayde number veriler de tutulabilir.

hem string hem number veri değeri yazılabilir.

iç içe arrayler de yazılabilir.

const yeniUrun=["samsung",1150,["apple",20]]

! eğer iç içe arrayde içteki arrayin verisine ulaşmak istiyorsak:

const yeniUrun=["samsung",1150,["apple",20]]

console.log(yeniUrun[2][0])



                - JS ARRAY METHODLARI DERS 15-


let products=["iphone5","samsung","huawei"]


let result;
result=products

result=products.length;  //arrayde kaç eleman var
//! array to string
result=products.toString(); // arreyi stringe çevir
result=products.join("/") ;  // arrayi stringe çevirir. parametre vererek array array elemanlarını ne ile ayıracağımızı seçeriz.

//! diziden eleman silme 

result=products.shift();  // arrayden ilk elemanı siler ve geri döndürür.
result=products.pop();  // arraydeki son elemanı siler ve o eleamnı geri döndürür.

//!diziye eleman ekleme
result=products.push("xiaomi")  //arrayin sonuna eleman ekler.
result=products.unshift("xiaomi")  // arrayin başına eleman ekler.

//! array birleştirme

let urunler1=["asus","apple"]
let urunler2=["dell","casper"]
let urunler3=["acer","exper"]

result=urunler1.concat(urunler2,urunler3)  // birden fazla arrayi birleştirir.

result=urunler1.splice(0,0,urunler2)  // arrayden çıkarma işlemi yapan methodda hiçbir arrayi seçmeden son parametreye değer vererek array birleştirebiliriz.
//! splice bir eleman silerse onu return eder.

result=products.splice(0,1) // splice parametresinde ilk numaralı indexsten başlayarak kaç tane eleman silineceği verilir ve o silinen eleman return olur.


console.log(result)

//! W3SCHOOLS.COM DAN ARRAY METHODLARINA BAKABİLİRSİNİZ.



          -JAVASCRİPT OBJELER (OBJECTS) DERS 16-

objeler key ve value ile değişken tanımlama yapmamızı sağlar.

kullanımı:
let customer={
    ad:"kubilay", 
}

burada ad key kubilay value dir .

yani kodlama     key:"value" olarak yapılır.

bizler keylerden value lere erişebiliriz. 

bunu yapmak için:

console.log(customer.ad)

hangi değişkendeki key in valuesine ulaşmak istiyorsak o değişken isminden sonra nokta ile key ismini belirtiriz.
yukarıdaki işlemde customer değişken tipi objedir. objenin ad keyini alıp konsola yazdırdık.

js formatında keyler default olarak "" içerisine alınmaz ama "" içerisinde de kullanabiliriz. daha sonra json formatında keyleri "" içerisine alacağız.

! bizler value ler  tekrardan obje kullanabiliriyoruz. array de kullanabiliriz.


let customer3 = {
  ad: "şeyma",
  soyad: "taşkafa",
  sehir: "antalya",
  yas: 21,
  products: {
    laptop: "asus",
    araba: "honda",
  },
};


obje içerisindeki objelere ulaşmak için :


console.log(customer3.products.laptop);

bizler arrayler içerisinde objeler tanımlayabiliriz.


let urunler=[
    {
        urunAdi:"asus",
        fiyati:20000
    },
    {
        urunAdi:"vestel",
        fiyati:24000
    }
]


bu array içindeki objelere ulaşıp daha sonra bu objelerdeki keylere ulaşabiliriz.

console.log(urunler[1].urunAdi)



                -JAVASCRİPT DÖNGÜLER DERS  17-
döngüler bir durumu birden fazla kez oluşturmamıza yarar.

örneğin bir arrayin içindeki elemanları konsola yazdırmak için:

console.log(urunler[0]) gibi bir yol izliyorduk 

fakat bir arrayin içerisinde milyonlarca veri bulunabilir.
tek tek console.log() yapmak imkansız hale gelebilir.

işte tam burada döngüler bizlere yardımcı olur.


döngüler aynı kodun belirli bir koşula bağlı olarak sürekli çalışmasını sağlar.


//! for döngüsü

for(let i=0; i<meyveler.length;i++){
    
}

bu döngüde i bizim sayacımızdır. sayacı 0 dan başlattık

i<meyveler.length bizim koşulumuzdur. bu koşul sağlandıkça döngü devam eder. yani i değeri meyveler arrayinin uzunluğundan küçük olduğu sürece

tabi burada sonsuz bir döngüye girmememiz gerek. eğer sonsuz döngüye girersek program çöker.
sonsuz döngüye girmemek için her döngüde i değerini i++ olarak arttırıyoruz.


for(let i=0; i<meyveler.length;i++){
    console.log(meyveler[i])
}

burada bloğun içerisinde konsola meyvelerden index numarasına göre veri dönecek. index parametresine i verdik.
i her değiştiğinde index numarası i değeri olacak



                              -JS SCOPE DERS 19-

js uygulamarımızda değişkenler oluşturduğumuzda var let const ile oluşturuyoruz.

scope nedir?
bizler bloklar içerisinde bir tanımlama yaparsak o tanımlama sadece o blok içerisinde olur.

örnek olarak:
var kullanici = "emin";

function isimYazdir() {
  var kullanici = "kubilay";
}

console.log(kullanici);
isimYazdir();

burada hem blok içinde hem de normal kod satırında var ile kullanici tanımladık

kod satırındaki kullanici olan emin bizim global scope umuzdur. blok çalışmadıkça konsolda kullanici daima emin olur.
bloktaki kullanici olan kubilay bizim function scope umuzdur.

function isimYazdir2() {
  console.log(kullanici);
}

eğer biz blok içerisinde bir kullanici tanımlamadan konsola kullanici yazdırırsak global scope olan emin i kullanır.

bu kullanım functiona özeldir.
fonksiyonlar kendi scope alanlarını oluşturur.
var ile if blok içerisinde scope sıkıntı yaşatır. global scope u değiştirir..


let ve const ile blok içi scope oluşumu sağlayabiliriz.

const sabittir. uygulama boyunca const u değiştiremeyiz.

const name="kubilay";

name="şeyma"  olarak bir kullanım yapamayız.


            -JAVASCRİPT DOM DERS 20-
HTML ETİKETLERİNDE JS KULLANABİLMEK İÇİN DOM KULLANMAK ZORUNDAYIZ.

ARTIK TARAYICI TARAFINDA ÇALIŞACAĞIZ.

DOM KONUSU:

DOCUMENT =BÜTÜN HTML ÖGELERİMİZİ TEMSİL EDER.


HTML ETİKETİ

BİZLER CSS DEKİ GİBİ JS DE HTML ETİKETLERİNE ULAŞIP İŞLEM YAPIYORUZ.
dom ile js i html de kullanabiliriz.
Dom html ögelerini js in çalışabileceği array string ve objelere dönüştürür.

Bizler html etiketleri üzerinde js kullanmak için seçicileri kullanıyoruz.
seçicileri kullanmak için:

document üzerinde işlem yapıyoruz:


    -tEKLİ seçiciler-
document.querySelector() =tekli seçim yapar ilk bulduğu elementi seçer.
document.querySelector("h1")= ilk h1 elementini alır.
document.querySelector(".title")= ilk title classına sahip elementi alır.
querySelector # ile id yi seçer.

bizler hmtl dosyalarımıza js dosyalarını eklemek için body nin en altına script tagı açıyoruz.
 <script src="./index.js"></script>

 scriptin src sine js dosyasını ekliyoruz.

 direkt script tagları içerisine de js yazabilirz.


ufak bir örnek:


html:
<body>
    <h1>javascript Dom</h1>

    <script src="./index.js"></script>
</body>

js:
const title=document.querySelector("h1")  //ilk bulduğu elementi alır.
console.log(title)

js ile html etiketine stil verebiliriz.

<body>
    <h1>javascript Dom</h1>

    <script src="./index.js"></script>
</body>

const title=document.querySelector("h1")  //ilk bulduğu elementi alır.
title.style.color="red"



document.getElementById()= id ye göre element seçer.

örnek:

html:
<body>
    <h1 class="title">javascript Dom</h1>
    <h1  class="title" id="blue">javascript Dom</h1>
    <h1 class="title">javascript Dom</h1>
    <h1 class="title">javascript Dom</h1>
    <h1 class="title">javascript Dom</h1>

    <script src="./index.js"></script>
</body>

javascript:

const title2=document.getElementById("blue")
title2.style.backgroundColor="yellow"

!bizler dom seçicileri css seçici olarak kullanabiliriz.
verdiğimiz css özelliklerini inline olarak verir.

<h1 class="title" id="blue" *style="background-color: yellow;*">javascript Dom</h1>


bizler JS ile html etiketi içerisindeki yazıyı değiştirebiliriz.
bu işlemi innerText ile yapabiliriz.

örnek:

html:
    <h1 class="title" id="blue">javascript Dom</h1>

    <script src="./index.js"></script>

js:
    const title2 = document.getElementById("blue");
    title2.innerText="DOM"  


! JS İLE HTML ELEMENTİMİZİN İÇERİSİNE BAŞKA BİR ELEMENT EKLEYEBİLİRİZ.

BUNU İNNERHTML ÖZELLİĞİ İLE YAPABİLİRİZ.

ÖRNEK :

HTML:
      <h1 class="title" id="blue">javascript Dom</h1>

    <script src="./index.js"></script>
  </body>

JS:
const title2 = document.getElementById("blue");
title2.innerHTML= "<button>click</button>"



-ÇOKLU SEÇİCİLER-
document.querySelectorAll()=çoklu seçicidir. içine aldığı değerlerin hepsini seçer.
document.querySelectorAll("h1")=bütün h1 elementlerini seçer.
document.querySelectorAll(".title")=bütün title classlarına sahip elementleri seçer.



getElementsByClassName()= bir class a sahip bütün elementleri seçer.
örnek:

html:


    <ul>
        <li class="listItem">ali</li>
        <li class="listItem" >veli</li>
        <li class="listItem">ahmet</li>
        <li class="listItem">ardaa</li>
    </ul>
    <script src="./index.js"></script>
  </body>

js:

//çoklu seçicilerde her bir elemente renk özelliği vermek için döngğye sokarız.
const listItem=document.getElementsByClassName("listItem")

for(let list of listItem){
    list.style.color="red"
}


getElementsByTagName() =  içine parametre olarak element veririz. sayfadaki bütün o elementleri seçer.


// bizler daha ayrıntılı bir seçmek için css seçiciler gibi seçiciler kullanabiliriz.

const listItems=document.querySelectorAll("#list-items li")

// burada list-items id li elementin içindeki li leri seçer.


örnek:

html:

    <ul id="list-items">
      <li>ali</li>
      <li>>veli</li>
      <li>>ahmet</li>
      <li>>ardaa</li>
    </ul>

    <script src="./index.js"></script>
  </body>
</html>


javascript:

          -JAVASCRİPT OOP DERS 21-
nesne yönelimli programlama ile karmaşık yazdığımız kodları clean şekilde yazmamızı sağlar.

JavaScript'te her şey bir nesnedir. Nesneler, anahtar-değer çiftleri olarak tanımlanır 
ve özellikleri ve metotları içerebilir. Örneğin, aşağıdaki kod, bir "Araba" 
nesnesi oluşturur ve "renk" ve "hız" özelliklerini ve "hızlandır" metodunu içerebilir

örnek:
let araba = {
    renk: "siyah",
    hız: 0,
};
console.log(araba.renk); // "siyah"
console.log(araba.hız); // 0
console.log(araba.hız); // 10

Bu kod bloğunda, nesne literaller kullanılarak oluşturuldu. 
Bu nesnenin özellikleri (renk, hız) anahtar-değer çiftleri olarak tanımlandı. 
Özellikleri kullanarak nesnenin durumunu sorgulayabilir ve metotları çağırarak nesnenin davranışlarını değiştirebiliriz.
 Bu kod bloğunda, araba adında bir nesne oluşturuldu. 
Bu nesnenin renk özelliği "siyah" ve hız özelliği 0'dır.





//!OBJECT
let araba1 = {
  renk: "mavi",
  hiz: 0,
};

//objeler içerisindeki özelliklere property denir.
// console.log(araba1.renk);
// console.log(araba1.hiz);

//!METHOD
// objelerimiz içerisinde tanımlayabileceğimiz fonksiyonel işlemlere method denir.

let araba2 = {
  renk: "kırmızı",
  hiz: 0,
  hizlandir: function (deger) {
    this.hiz += deger;
  },
};
//buradaki this ifadesi araba2 bloğu içinde olduğumuz için araba2 yi temsil eder. ve this ile araba 2 objesinin özelliklerine erişebiliriz.

araba2.hizlandir(30); //bizler methodları bu şekilde çalıştırabiliriz.
console.log(araba2.hiz);

// ! Constructor ES5

// es5 versiyonunda
// class tanımıyoruz baş harf büyük olacak
// blok içerisindekiler constructor oluyor.
function Araba(renk) {
  this.renk = renk;
  this.hiz = 0;
}
// class içindeki constructorları kullanabilmek için

const araba = new Araba("red");
console.log(araba.renk);

// prototype ile yeni bir method ekleyebiliriz.
Araba.prototype.hizlandir = function (deger) {
  this.hiz += deger;
};

araba.hizlandir(100);
console.log(araba.hiz);

// ! CONSTRUCTOR ES6
// es6 ile artık fonksiyon olarak değil direkt class ile class oluşturuyoruz.
class Araba3 {
  constructor(renk) {
    this.renk = renk;
  }
}

let araba3 = new Araba3("siyah");

console.log(araba3.renk);

// ! CLASS
//! nesnelerin oluşturulması için şablondur.
// kod okunabilirliği için iyidir.
class Car {
  // class içinde özellik tanımlamak için constructor ekliyoruz.
  constructor(renk) {
    // farklı methodlarda bu özellikleri kullanabilmek için global olarak tanımlamak gerekir.
    this.renk = renk;
    this.hiz = 0;
  }
  // es6 ile direkt
  hizlandir(deger) {
    this.hiz += deger;
  }
}

// bizler class üzerinden bir nesne oluşturuyoruz.
// car nesne  new Car bir class dır.

let car = new Car("siyah");
car.hizlandir(200);
console.log(car.renk);
console.log(car.hiz);

// ! instantiation(örnekleme)
// bir class dan nesne oluşturmak örneklemedir.

// ! inheritance (kalıtım)
//  classların birbirinden kalıtım almasıdır.
// extends kullanılır.

class Araba5 {
  constructor(renk) {
    this.renk = renk;
  }
}
// burada motorluAraba classı Araba classından bir özellik miras alacak
class motorluAraba extends Araba {
  // constructor parametrelerinde ilk önce miras alacakları parametre yazılır.sonra kendi özelliklerinin parametresi yazılır.

  constructor(renk, motor) {
    // bizler super ile miras alacağımız özelliği tanımlarız.
    super(renk);
    // classın kendi özelliğini tanımlarız.
    this.motor = motor;
  }
}

let motorAraba5 = new motorluAraba("siyah", "v8");
let araba5 = new Araba5("red");
console.log(motorAraba5.renk);
console.log(motorAraba5.motor)
console.log(araba5.renk)

// burada yaptığımız işlemde araba classında bir renk özelliği ekledik .
// motorlu araba classında renk özelliğini baştan yazmak yerine arba sınıfındaki özelliği kalıtım aldık ve kullandık
// bu sayede tekrardan bir bir constructor yazmamıza gerek kalmadı ve kod temizliği ve bakımı sağlandı.

// ! encapsulation
//?  nesnelerin özellikleri ve methodlarının dışarıdan erişilememesi için kullanılan yapıdır.
//? bu sayede nesnenin özellikleri ve methodları güvenli bir şekilde kullanılabilir.


class Araba6{
    // burada eklediğimiz özelliğin başına # koyduğumuzda kodun başka bir yerinde ulaşamıyoruz.
    #renk;
    constructor(renk){
        this.#renk=renk
    }
    // burada renkleri kullanmak için bir method yazmalıyız.
    getRenk(){
        return this.#renk
    }
    setRenk(renk){
        this.#renk=renk
    }
}

const araba6= new Araba6("siyah")
console.log(araba6.renk)

 let result=araba6.getRenk();
 console.log(result)

//  !  POLYMORPHİSM (ÇOK BİÇİMLİLİK)
// JS DE AYNI METHODUN FARKLI NESNELER İÇİN FARKLI İŞLEVLERİ YERİNE GETREBİLDİĞİ BİR KAVRAMDIR.

class Shape{
    draw(){
        console.log("şekil çiziliyor..")
    }
}



class Circle extends Shape{
    draw(radius){
        console.log(`${radius} radiuslu bir daire çiziliyor.`)
    }
}

let shape= new Shape();
let circle=new Circle();
console.log(circle.draw("20"))

// ! abstraction (soyutlama)
// Sınıfların, nesnelerin oluşturulduğu sınıfın sadece gerekli olan özelliklerini ve metotlarını göstermesidir. 

class Database {
    constructor(data) {
        this._data = data;
    }
    getData() {
        return this._data;
    }
    setData(value) {
        this._data = value;
    }
}

class DataController extends Database {
    constructor(data) {
        super(data);
    }
    getData() {
        return "Data: " + super.getData();
    }
}

let dataController = new DataController("Database Data");
console.log(dataController.getData()); // "Data: Database Data"



              - MODERN JAVASCRİPT DERS 22-

//! -arrow function-
// ? es6 ile birlikte gelen fonksiyon oluşturma türüdür.
// ? clean kod kavramında bize yardım eder.

// ! normal fonksiyon

const sayHello = function () {
  console.log("hello");
};

// ! arrow function
const sayHello2 = () => {
  console.log("hello");
};

// ! blokta tek işlem olacaksa tek satırda kullanabiliriz.
const sayHello3 = () => console.log("hello");
sayHello3();

// ! ARRay Methods

//? map() methodu : arraydeki her elemanı döner.
// ? map parametrede önce bir örnek değer alır. x gibi yani arraydeki her eleman x yerine konur.
// ? daha sonra bloğunda x e göre işlemler yapılır.
// ?forEach() methodunun gelişmiş versiyonudur.
const numbers1 = [1, 2, 3, 4, 5, 6];
const squares = numbers1.map((x) => x * x);

console.log(squares);

//! filter methodu: belirli bir kritere göre elamanları seçer.
//?içerisinde bir arrow function kullanıyoruz.

const numbers2 = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
const ciftSayiBul = numbers2.filter((x) => x % 2 === 0);

//? x array üzerinde dönüyor ve 2 ile bölümünden kalanı 0 olanları bulup değişkene dönüyor.
console.log(ciftSayiBul);

//! reduce methodu:
const numbers3 = [1, 2, 3, 4, 5, 6, 7, 8];

const sum = numbers3.reduce((acc, x) => acc + x, 0);
// ! reduce 2 tane parametre ister  (şuanki değer,her bir dönen değer.)
// ! sondaki sıfır değeri aslında başlangıç değeridir. yani acc dir.
// !x arrayin her bir elemanı üzerinde dönerek acc ile toplar. acc her dönmede bir önceki array değerini tutarak toplama işlemi yapar.

console.log(sum);

// ! find methodu: Bu method, array içinde ilk kriterlere uyan elemanı döndürür.

const numbers4 = [1, 2, 3, 4, 5];

const findNumber = numbers4.find((x) => x > 2);

console.log(findNumber);

// ! some methodu= array içerisinde belirli bir kritere göre eleman var mı bulmaya yarar.
// some bize true vey false sonucu döner.
const numbers5 = [1, 2, 3, 4, 5, 6];
const result = numbers5.some((x) => x > 10);

console.log(result)

//! every methdu= array içindeki tüm elemanların bir kritere uygun olup olmadığını kontrol eder.

const numbers6= [2, 4, 6, 8, 10];
const isAllEven = numbers6.every(x => x % 2 === 0);
console.log(isAllEven);
// ? burada tüm sayıların çift olup olmadığını kontrol ediyoruz. tüm array elemanları şartı sağlamak zorunda 


// ! SPREAD OPERATÖRÜ
// Spread operator, array veya object içindeki elemanların başka bir array veya object içine kopyalanmasını sağlar.
const numbers7 = [1, 2, 3];
const numbers8 = [...numbers7, 4, 5, 6];
console.log(numbers2);

// BURADA NUMBERS7 ARRAYİNİ NUMBERS8 ARRAYİNE EKLEDİK. BUNU YAPMAK İÇİN NUMBERS7 ARRAYİNİN BAŞINA ÜÇ TANE NOKTA KOYUYORUZ.
// BU İŞLEM SAYESİNDE 2 TANE ARRAYİ KOLAYLIKLA BİRLEŞTİREBİLİRİZ.

// Ayrıca, spread operator ile bir arrayin elemanlarını bir fonksiyona veya metoda parametre olarak geçirmek için kullanılabilir

// Örneğin, aşağıdaki örnekte, bir array içindeki elemanlar bir fonksiyonun parametreleri olarak geçirilmiştir:
const numbers9 = [1, 2, 3];
const add = (x, y, z) => x + y + z;
console.log(add(...numbers9));

// AYNI İŞLEMİ OBJELER ÜZERİNDE DE GERÇEKLEŞTİREBİLİRİZ.
const obj1 = {name: "John", age: 30};
const obj2 = {...obj1, job: "Developer"};

// BURADA OBJ2 DE OBJ1 İÇİNDEKİ VERİLERİ ALIP ÜSTÜNE YENİ BİR VERİ EKLEDİK.

// BU İŞLEMLERDE DİKKAT EDİLMESİ GEREKEN KONU EĞER BİR OBJEYİ SPREAD KULLANARAK BAŞKA BİR OBJEYE EKLERSENİZ.
// 2 OBJEDE ÇAKIŞAN AYNI KEYLER DE SPREAD İLE EKLENEN OBJE BASKIN GELİR.
const obj3 = {name: "John", age: 30};
const obj4 = {name: "Mike", job: "Developer", ...obj3};
// BURADA NAME DEĞERİ MİKE YERİNE JOHN OLACAKTIR.
// ARRAYLERİ VE OBJELERİ DAHA KOLAY MANİPÜLE EDEBİLİRİZ.

// ! Destructuring
// ? Destructuring, object içindeki belirli key-value pair'ların çekilmesini ve değişkenlere atanmasını sağlar.

const obj = {name: "John", age: 30};
const {name, age} = obj;
// BURADA BİR OBJEDEKİ BELİRLİ VERİLERİ ALIP TEKRARDAN DEĞİŞKENE BAĞLAYABİLİR VE BİR OBJEDEKİ SADECE BELİRLİ VERİLERİ KULLANABİLRİZİ.

// BİZLER destricting ile bir objenin içindeki verininin keyini değiştirebiliriz.
const obj5 = {name: "John", age: 30};
const {name: firstName} = obj;
console.log(firstName);
// artık obj5 objesinin name keyi firsName oldu.

//? obje içerisindeki belirli verileri değişkene atayabiliriz.
const numbers = [1, 2, 3, 4, 5];
const [first, second, ...rest] = numbers;
console.log(first); 
console.log(second); 
console.log(rest);

// burada 1 ve 2 değerini değişkenlere atadık. array içerisindeki diğer verileri de ...rest ile rest değişkenine atadık.
// bu sayede first=1  second=2   ve rest=[3,4,5] oldu.
// burada verileri ayırırken kullandığımız ...rest spread operatörü değil rest operatörüdür.karıştırmayalım.

// !  Maps
// Modern JavaScript ile birlikte, Map yapısı özellikle verilerin saklanması ve erişilmesi için çok kullanışlı bir araç haline gelmiştir.
// Map yapısı, key-value pair'ları saklar ve bu pair'ları hızlı bir şekilde erişebilir.

// Map yapısını oluşturmak için new Map() kullanılır.
const map = new Map();
map.set("name", "John");
map.set("age", 30);
map.set("job", "Developer");

// Map yapısındaki verileri erişmek için get() methodu kullanılır. Örneğin, aşağıdaki örnekte, "name" key'inin değeri erişilmiştir:
console.log(map.get("name")); // "John"

// Map yapısındaki verileri silmek için delete() methodu kullanılır. Örneğin, aşağıdaki örnekte, "job" key'inin değeri silinmiştir:
map.delete("job");
console.log(map);

// Map yapısındaki verileri iterate etmek için forEach() methodu kullanılır.
// Örneğin, aşağıdaki örnekte, map içindeki tüm key-value pair'lar yazdırılmıştır:
map.forEach((value, key) => console.log(`${key}: ${value}`));

// Map yapısı, verilerin saklanması ve erişilmesi için daha kolay ve hızlı bir yol sunar. 
// Ayrıca, Map yapısı ile key-value pair'ların değerleri değiştirilebilir ve silinebilir. Bu nedenle, modern JavaScript geliştirmelerinde sıklıkla kullanılmaktadır.

// ! Sets
//  Set yapısı, unique değerleri saklar ve bu değerlere hızlı bir şekilde erişebilir.
// Set yapısını oluşturmak için new Set() kullanılır
// Örneğin, aşağıdaki örnekte, bir Set yapısı oluşturulmuş ve değerler eklenmiştir:

const set = new Set();
set.add(1);
set.add(2);
set.add(3);
set.add(3);

// setle eklediğiniz bir değeri tekrar ekleyemezsiniz.

// Set yapısındaki verileri erişmek için has() methodu kullanılır.
// Örneğin, aşağıdaki örnekte, 2 değerinin set içinde olup olmadığı kontrol edilmiştir:
console.log(set.has(2)); // true
console.log(set.has(4)); // false

// Set yapısındaki verileri silmek için delete() methodu kullanılır. 
// Örneğin, aşağıdaki örnekte, 2 değeri silinmiştir:
set.delete(2);
console.log(set); // Set { 1, 3 }

// Set yapısındaki verileri iterate etmek için forEach() methodu kullanılır.
// Örneğin, aşağıdaki örnekte, set içindeki tüm değerler yazdırılmıştır:
set.forEach(value => console.log(value));


      -JAVASCRİPT STORAGE KAVRAMI - 

JavaScript'te storage kavramı, kullanıcıların web tarayıcılarında veri saklamasını sağlayan teknolojilere atıfta bulunur. Bu veri, tarayıcı kapansa bile belirli bir süre (geçici veya kalıcı olarak) saklanabilir ve farklı sayfalarda kullanılabilir. JavaScript'te en yaygın iki saklama yöntemi vardır:


1. Local Storage (Yerel Depolama)
Süresi: Kalıcıdır, tarayıcı kapatıldıktan sonra bile veriler silinmez.
Veri Kapasitesi: Yaklaşık 5-10 MB arasında değişir.
Kullanımı: key-value (anahtar-değer) çifti şeklinde veri saklar.

Örnek Kullanım:

// Veri eklemek
localStorage.setItem('anahtar', 'değer');

// Veri okumak
let veri = localStorage.getItem('anahtar');
console.log(veri); // 'değer'

// Veri silmek
localStorage.removeItem('anahtar');

// Tüm verileri temizlemek
localStorage.clear();


2. Session Storage (Oturum Depolama)
Süresi: Geçicidir, tarayıcı sekmesi kapandığında veriler silinir.
Veri Kapasitesi: Genellikle 5-10 MB civarındadır.
Kullanımı: key-value çifti şeklinde veri saklar.
Örnek Kullanım:

// Veri eklemek
sessionStorage.setItem('anahtar', 'değer');

// Veri okumak
let veri = sessionStorage.getItem('anahtar');
console.log(veri); // 'değer'

// Veri silmek
sessionStorage.removeItem('anahtar');

// Tüm verileri temizlemek
sessionStorage.clear();

3. Cookies (Çerezler)
Süresi: Tarayıcı veya sunucu tarafında belirlenen bir süre boyunca geçerlidir.
Veri Kapasitesi: Genellikle 4 KB ile sınırlıdır.
Kullanımı: Tarayıcıya küçük veri parçaları saklayıp gönderir. Daha çok kullanıcı oturumlarını takip etmek için kullanılır.
Örnek Kullanım:

// Çerez oluşturmak
document.cookie = "isim=değer; expires=Sun, 1 Jan 2024 12:00:00 UTC; path=/";

// Çerezi okumak
let tümÇerezler = document.cookie;
console.log(tümÇerezler); // "isim=değer"

// Çerezi silmek
document.cookie = "isim=değer; expires=Thu, 01 Jan 1970 00:00:00 UTC; path=/";

Farklar
Local Storage verileri kalıcıdır, tarayıcı kapanana kadar saklanır.
Session Storage oturum süresi boyunca geçerlidir.
Cookies, hem tarayıcı hem de sunucu tarafından kullanılabilir, ancak daha küçük boyutludur ve genellikle HTTP istekleriyle birlikte sunucuya gönderilir.

Her bir yöntem, farklı kullanım senaryolarına uygun olarak seçilmelidir. Örneğin, kullanıcı bilgilerini sayfalar arasında saklamak için localStorage kullanılırken, geçici oturum bilgileri için sessionStorage kullanılabilir.
