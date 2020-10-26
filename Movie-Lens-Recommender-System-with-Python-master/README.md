# Movie-Lens film veri setini kullanarak Python ile Tavsiye Sistemleri oluşturma
Kullanıcılara Filmler önererek öneri sistemlerine giriş yaptım.
Film önermek için <a href="https://grouplens.org/datasets/movielens/100k/">MovieLens</a> veri kümesini kullanacağız.
Kullanacağımız teknik, teknik terimlerle "İşbirlikçi filtreleme" olarak bilinir.

Öğeleri önermek için basit buluşsal yöntemler kullanıyoruz. Beğenmek,

Kullanıcı tabanlı:

Diyelim ki A kullanıcısına öneriler göstermek istiyoruz. Bu yöntemde, A kullanıcısının sevdiği öğeleri beğenme eğiliminde olan benzer bir B kullanıcısını bulmaya çalışıyoruz.
Bu nedenle, kullanıcı B'nin A kullanıcısına sevdiği diğer öğeleri öneriyoruz.
Bunun arkasındaki mantık, benzer insanlar benzer öğeleri beğenebilir.

Ürün temelli:

Bir kullanıcının P ürününü satın aldığını varsayalım.
Artık, kullanıcının tüm verilerinden, P öğesi her satın alındığında kullanıcıların neredeyse her zaman satın aldığı bir S öğesi vardır.
Bu nedenle, P ürününü satın aldıklarında kullanıcılara S ürününü öneriyoruz.
Bunun arkasındaki mantık, benzer ürünler birlikte satılabilir.
