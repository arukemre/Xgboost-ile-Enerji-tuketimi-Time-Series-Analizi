# Xgboost ile  Enerji tüketimi Time Series Analizi 


    |─ Hourly Load Data.csv
    |─ model.ipynb
    
        |─ Data Preview
        |─ Data preprocessing
        |─ Data preprocessing  and Feature Engineering stages
        |─ XGBOOST MODEL
        |─ Model optimization with optuna
    
    
 ## Gerekli kütüphaneler ve kurulumlar
    - Xgboost
    - Pandas
    - matplotlib,seaborn
    - optuna
    - scikit-learn
    - openxl 
    - datetime 

* Bu repository de  1999 ve  2001 yılları arasında  Enerji tüketimi verileri analiz edilmiştir.

* Time Seires analizi; zaman içerisinde gelişen olayların ve işlemlerin analiz edilmesi ve iç görüye dönüştürülmesi ile tarihsel etkileri anlamak için önemli bir tekniktir.Zaman serisi temelde önceden gözlemlenen gözlmelere dayanarak geleceğe yönelik forecasting elde etme amacı taşımaktadır.


## Temel oluşturmak için bilinmesi gereken terimler.

### Trend (Eğilim):
* Verilerde uzun vadeli bir artış ya da düşüş eğilimi olduğunda, eğilim yönünü temsil eden bir trend çizgisi oluşur, bu trend çizgisi her zaman doğrusal olmak zorunda değildir. Bazı trendler, artan bir eğilimden azalan bir eğilime doğru gittiğinde, onları yön değiştiren (changing direction) trend olarak adlandırırız.

### Seasonal (Mevsimsel):
* Mevsimsel desenler; günün saatleri, haftanın günleri ya da yılın haftaları gibi döngü oluşturan periyotlarla sıralanan zaman serilerinde, mevsimsel döngülenmenin veri üzerindeki etkilerinden meydana gelir.

### Cyclical (Konjonktürel):
* Zaman serilerinde mevsimsel olmayan ve tamamen nedensel bir etkenden kaynaklanan dalgalardan oluşan döngüler de gerçekleşir. Bu dalgalanmalar genellikle ekonomik koşullardan kaynaklanır ve genellikle iş döngüsü (business cycle) ile ilişkilidir.

### Noise(gürültü)
* Model tarafından acıklanamayan gözlemlerdeki değişkenlik.Genellikle bunları egale etmek için çalışırız.


 `NOT` : `model.ipynb` notebook içerisinde analizin detayları anlatılmıştır.
