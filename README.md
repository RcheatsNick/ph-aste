# Hastebin Plus
Hastebin Plus, herhangi bir ağa kolayca kurulabilen, node.js ile yazılmış açık kaynaklı bir Pastebin yazılımıdır.
[Aceleye] (https://github.com/seejohnrun/haste-server) dayanır ve ** Tasarım, Hız ve Basitlik ** konularında gelişmiştir.

## Özellikleri
* Kodu, günlükleri ve neredeyse her şeyi yapıştırın!
* Sözdizimi Vurgulama
* Statik belgeler ekleyin
* Kopyaları çoğaltın ve düzenleyin
* Ham macun görünümü

## Kurulum
[! [Heroku'ya Dağıt] (https://www.herokucdn.com/deploy/button.png)] (https://heroku.com/deploy?template=https://github.com/Snowflake107/HastebinPlus)

1. Git ve node.js'yi kurun: `sudo apt-get install git nodejs`
2. Bu depoyu klonlayın: `git clone https://github.com/MarvinMenzerath/HastebinPlus.git hastebin-plus`
3. "config.json" dosyasını açın ve ayarları değiştirin (isterseniz)
4. Bağımlılıkları yükleyin: "npm install"
5. Uygulamayı başlatın: "npm start"

## Güncelleme
1. Bu depodaki değişiklikleri alın: "git pull`
2. Yeni bağımlılıkları yükleyin: "npm install`

## Ayarlar
| Anahtar | Açıklama | Varsayılan değer |
| ---------------------- | ----------------------------------------------- | ------------- |
| `ana bilgisayar` | Sunucunun çalıştığı ana bilgisayar | `0.0.0.0` |
| `bağlantı noktası` | Sunucunun çalıştığı bağlantı noktası | `8080` |
| `dataPath` | Tüm yapıştırmaların depolandığı dizin | ". / veri` |
| `keyLength` | Macun anahtarının uzunluğu | `10` |
| `maxLength` | Bir yapıştırmada maksimum karakter | "500000" |
| `createKey` | Oluşturulmasına izin vermek için yapıştırmanın önünde olması gerekir | '' |
| `belgeler '| Sunulacak statik belgeler | Aşağıya bakın |

### Varsayılan Yapılandırma
json
{
"ana bilgisayar": "0.0.0.0",
"bağlantı noktası": 8080,
"dataPath": "./data",
"keyLength": 10,
"maxLength": 500000,
"createKey": "",
"belgeler": {
"about": "./README.md",
"javaTest": "./documents/test.java"
}
}
''

## Yazarlar
* [haste] (https://github.com/seejohnrun/haste-server): John Crepezzi - MIT Lisansı
* [jQuery] (https://github.com/jquery/jquery): MIT Lisansı
* [vurgulamak.js] (https://github.com/isagalaev/highlight.js): Ivan Sagalaev - [Lisans] (https://github.com/isagalaev/highlight.js/blob/master/LICENSE)
* [Uygulama Simgesi] (https://www.iconfinder.com/icons/285631/notepad_icon): [Paomedia] (https://www.iconfinder.com/paomedia) - [CC BY 3.0 Lisansı] (http: / /creativecommons.org/licenses/by/3.0/)

## Lisans
Telif Hakkı (c) 2021-2022 Codinator

İşbu belge ile, bu yazılımın ve ilgili belge dosyalarının ("Yazılım") bir kopyasını elde eden herhangi bir kişiye, kullanım, kopyalama, değiştirme, birleştirme hakları dahil ancak bunlarla sınırlı olmamak üzere, kısıtlama olmaksızın Yazılım üzerinde işlem yapma izni verilmektedir. Yazılımın kopyalarını yayınlamak, dağıtmak, alt lisansını vermek ve / veya satmak ve Yazılımın sağlandığı kişilere aşağıdaki koşullara tabi olarak izin vermek için:

Yukarıdaki telif hakkı bildirimi ve bu izin bildirimi, Yazılımın tüm kopyalarına veya önemli kısımlarına dahil edilecektir.

YAZILIM, TİCARİ ELVERİŞLİLİK, BELİRLİ BİR AMACA UYGUNLUK VE İHLAL ETMEME GARANTİLERİ DAHİL ANCAK BUNLARLA SINIRLI OLMAMAK ÜZERE AÇIK VEYA ZIMNİ HERHANGİ BİR GARANTİ OLMAKSIZIN "OLDUĞU GİBİ" SAĞLANIR. YAZARLAR VEYA TELİF HAKKI SAHİPLERİ HİÇBİR DURUMDA YAZILIM VEYA KULLANIM YA DA YAZILIMIN KULLANIMI VEYA DİĞER İLİŞKİLERDEN KAYNAKLANAN, SÖZLEŞME, İŞKENCE VEYA BAŞKA BİR DAVA DURUMUNDA HERHANGİ BİR TALEP, ZARAR VEYA DİĞER YÜKÜMLÜLÜKLERDEN SORUMLU OLMAYACAKLARDIR. YAZILIM.
