# Dataset-Motif-Batik
***

**kategori:** train, val, test
**Label Motif:** kawung, megamendung, parang, siomukti, truntum
**jumlah citra data train:** 2.800 
**jumlah citra data val:** 700
**jumlah citra data test:** 200
**total citra:** 3.700

## Deskripsi
Dataset ini dikumpulkan dari kaggle, google search image, dan ada juga dari pengambilan citra langsung dengan menggunakan smartphone. Kemudian dilakukan preprocessing dengan beberapa proses. Pertama melakukan pemilihan citra sesuai dengan kebutuhan. Kedua membagi data menjadi data train, val, dan test. Ketiga melakukan resize untuk menyamakan ukuran citra menjadi 256x256 pixel.

Awalnya jumlah citra motif batik yang terkumpul hanya berjumlah 750 citra saja, namun kemudian dilakukan augmentasi data secara manual sehingga jumlah citra motif batik menjadi 3.700 citra. Augmentasi data dilakukan dengan membuat citra baru dari citra yang sudah ada. Citra yang terapat pada data train dan val dilakukan augmentasi dengan 3 kali crop terhadap sumbu x dan y, dan dilakukan 3 kali rotasi yaitu 90˚, 180˚ dan 270˚. Sedangkan citra yang terapat pada data test hanya dilakukan augmentasi dengan 3 kali rotasi yaitu 90˚, 180˚ dan 270˚

## Struktur Direktori Dataset
* dataset
  * test
    * original
      * kawung
      * megamendung
      * parang
      * siomukti
      * truntum
    * rotasi90
      * kawung
      * megamendung
      * parang
      * siomukti
      * truntum
    * rotasi180
      * kawung
      * megamendung
      * parang
      * siomukti
      * truntum
    * rotasi270
      * kawung
      * megamendung
      * parang
      * siomukti
      * truntum
  * train
    * kawung
    * megamendung
    * parang
    * siomukti
    * truntum
  * val
    * kawung
    * megamendung
    * parang
    * siomukti
    * truntum
