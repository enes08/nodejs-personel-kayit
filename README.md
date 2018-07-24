 Personel Kayıt Sistemi
                           
Console üzerinde NodeJS ile yargs modulu kullanılarak metot isimleri ve parametreler 
alınarak kullanıcı kaydetme işlemi yapıldı.

uygulama ve parametreler hakkında bilgi almak için aşağıdaki metodnu kullanabilirsiniz
node app.js  --help  

Ekran Çıktısı 

Commands:
  create  Personel oluşturue
  get     Tüm Pesonelleri getirir
  delete  id ye göre kullanıcı siler

Options:
  --help  Show help                                                    [boolean]



Kullanmak istediğiniz metot hakkında bilgi almak için aşağıdaki metodnu kullanabilirsiniz
node app.js create  --help  

Ekran Çıktısı

Options:
  --name, -n     Personel Adını giriniz                      [string] [required]

  --surname, -s  Personel soy adını giriniz                  [string] [required]

  --email, -m    Personel Email  giriniz                     [string] [required]

  --help         Show help                                             [boolean]



Personel eklemek için 
 node app.js create -n isim_parametresi -s soyisim_parametresi -m emaail_parametresi

Tüm personelleri listelemek için 
 node app.js get

 İd ye göre personel silmek için 
 node app.js delete -i id_parametresi
