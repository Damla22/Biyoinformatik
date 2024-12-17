# Biyoinformatik
Biyoinformatik Veri Analizi ve Dizilim İşleme Projesi
  Bu proje, biyoinformatik alanında kullanılan veri işleme teknikleri ve protein dizilimlerinin karşılaştırılması üzerine odaklanmaktadır. Python dilinde yazılmış kodlarla, biyolojik dizilimlerin işlenmesi ve analiz edilmesi sağlanmıştır. Proje, FASTA formatındaki dizilimlerin uzunluklarını hesaplamak, protein dizileri arasındaki benzerlikleri ölçmek ve çeşitli biyoinformatik analizler gerçekleştirmek için geliştirilmiştir.
_______________________________________________________________________________________________________
İçerik
1. FASTA Formatında Dosya İşlemleri
Bu projede, biyolojik dizilimlerin saklandığı FASTA formatında bir dosya oluşturulmuş ve bu dosyadaki her bir dizilimin uzunluğu hesaplanmıştır.
FASTA dosyası, DNA veya protein dizilerini depolamak için yaygın olarak kullanılan bir format olup, her bir dizilim başlıklarıyla birlikte saklanır ve işlenir.

2. Protein Dizilimlerinin Karşılaştırılması (Blosum-62 Matrisini Kullanarak)
Blosum-62 matrisi, protein dizileri arasındaki benzerlikleri ölçen bir skor matrisidir. Bu projede, iki protein dizisi arasındaki benzerliği hesaplamak için Blosum-62 matrisi kullanılmıştır.
Matris, her iki dizinin her bir amino asidi arasındaki benzerlikleri gösterir ve toplamda bir skor elde edilerek diziler arasındaki ilişki hakkında bilgi sunar.

3. Kullanılan Kütüphaneler
Biopython: Biyoinformatik işlemleri kolaylaştırmak için kullanılan bu kütüphane, protein dizilimlerinin işlenmesi ve analiz edilmesi için geniş bir araç seti sunar.
Numpy: Sayısal hesaplamalar ve veri işleme işlemleri için kullanılan bu kütüphane, analiz sürecinde önemli bir rol oynamaktadır.

_______________________________________________________________________________________________________

Proje Adımları
FASTA Dosyasının Oluşturulması:
Proje, biyolojik dizilimleri içeren bir FASTA dosyasının oluşturulmasını ve bu dizilimlerin dosyaya yazılmasını sağlar.

Dizilim Uzunluklarının Hesaplanması:
Oluşturulan FASTA dosyasındaki her bir dizilimin uzunluğu hesaplanır ve bu uzunluklar ekrana yazdırılır.

Protein Karşılaştırması (Blosum-62 Matrisi Kullanımı):
İki protein dizisi arasındaki benzerlik, Blosum-62 matrisine dayalı olarak hesaplanır. Bu matris, her iki dizinin her bir amino asidi arasındaki benzerlikleri değerlendirir.

Gereksinimler
Python 3.x
Biopython Kütüphanesi: Biyoinformatik işlemler için.
Numpy Kütüphanesi: Veri işleme ve hesaplamalar için.
______________________________________________________________________________________________________
Sonuç ve Uygulama Alanları
  Bu proje, biyoinformatik ve genetik mühendisliği alanlarında temel dizilim analizi yapma becerisi kazandırmayı amaçlamaktadır. Protein dizileri arasındaki benzerliklerin hesaplanması, biyolojik araştırmalar, ilaç geliştirme ve genetik analizlerde yaygın olarak kullanılan bir tekniktir. Bu proje, biyolojik verilerin işlenmesi ve analizi için sağlam bir temel sağlar.

