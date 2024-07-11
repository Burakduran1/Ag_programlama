 <span style="font-size: 40px;">Bitki Hastalığı Tespit Projesi</span>



Bu proje, Evrişimli Sinir Ağları (CNN) kullanarak bitki yapraklarındaki hastalıkları tespit etmek için geliştirilmiş graf tabanlı bir web  uygulamayı içermektedir.




Bu projenin temel amacı, bitki hastalıklarını tespit etmek ve tanımlamak için yapay zeka teknolojilerini kullanarak
 graf tabanlı bir web uygulaması geliştirmektir. Bitki sağlığı, tarım ve bitkisel üretimde kritik bir öneme sahiptir. Sağlıklı
bitkiler, yüksek verim ve kaliteli ürün anlamına gelirken, hastalıklı bitkiler verim kaybına ve ekonomik zararlara
yol açar. Bu projeyle amaçlanan, bitki hastalıklarının erken teşhisi ve tedavisi için bir çözüm sunarak tarım
verimliliğini artırmak ve bitki hastalıklarıyla mücadelede daha etkili bir yol sağlamaktır.

Veri Seti
Bitki hastalıklarını tanımlamak için kullanılan 1530 görüntüden oluşan bir veri seti. Bu veri seti,
"Sağlıklı", "Tozlu" ve "Paslı" olmak üzere üç ayrı etiket içermektedir. Eğitim, test ve doğrulama
setleri olarak ayrılmıştır.

Metot
Bu çalışma, bitki hastalıklarının tespiti için evrişimli sinir ağları (CNN) kullanılarak
gerçekleştirilmiştir. Aşağıda çalışmanın temel adımları açıklanmaktadır.

![Classes Distribution](https://github.com/Burakduran1/Ag_programlama/blob/main/Pictures/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-07-11%20125302.png)



Oluşturulan model, eğitim veri seti üzerinde eğitilmiştir. Bu süreçte, ağın
ağırlıkları ve parametreleri belirlenmiştir

![Classes Distribution](https://github.com/Burakduran1/Ag_programlama/blob/main/Pictures/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-07-11%20125318.png)


Doğrulama ve Test:
Şekil 4’te görüldüğü üzere Eğitilen model, ayrılan doğrulama seti üzerinde doğrulama işlemine tabi
tutulmuş ve ardından test seti üzerinde performansı değerlendirilmiştir

![Classes Distribution](https://github.com/Burakduran1/Ag_programlama/blob/main/Pictures/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-07-11%20125330.png)


Model Mimarisi:
Çalışmada kullanılan Convolutional Neural Network (CNN) modelinin mimarisi şekil 6’da görüldüğü üzere
detaylı bir şekilde incelenmiş ve katmanlar arasındaki ilişkiler ile kullanılan aktivasyon fonksiyonları
açıklanmıştır. Modelin mimarisi, elde edilen başarı üzerindeki etkileriyle birlikte tartışılarak, her bir katmanın
özellikleri ve işlevi hakkında kapsamlı bir anlayış sunulmuştur.


![Classes Distribution](https://github.com/Burakduran1/Ag_programlama/blob/main/Pictures/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-07-11%20125347.png)



Karmaşıklık Matrisi:
Sınıflar arasındaki karışıklıkları değerlendirmek amacıyla oluşturulan karmaşıklık matrisi, modelin her sınıfta ne
kadar başarılı olduğunu göstermektedir. Şekil 9’da görüldüğü üzere matris üzerinden elde edilen sonuçlar
incelenerek, modelin hangi sınıflarda daha fazla hata yaptığı analiz edilmiş ve bu hatalardan kaynaklı geliştirme
alanları belirlenmiştir. Bu analiz, modelin performansını artırmak ve özellikle belirli sınıflarda daha etkili olmasını
sağlamak adına önemli bilgiler sunmaktadır [3]. Bu veriler doğrultusunda veri dengesizliğiyle mücadele etmek
için veri dengeleme tekniklerinin uygulanması ve modelin performansını artırmak için özellik mühendisliğine daha
fazla önem verilmesi gerekmektedir. Bu adımlar, modelin genel doğruluğunu ve özellikle zayıf performans
gösterdiği sınıflardaki başarısını artıracaktır.


![Classes Distribution](https://github.com/Burakduran1/Ag_programlama/blob/main/Pictures/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-07-11%20125421.png)



SONUÇLAR
Bu proje, bitki hastalıklarının yapay zeka tabanlı bir yaklaşımla %78 başarı oranıyla tespit edilebileceğini ve
geliştirilen web uygulamasının çiftçilere ve bitki uzmanlarına erken teşhis ve yönetim konusunda etkili bir araç
sağladığını gösteriyor. Gelecekteki çalışmalar, modelin genelleme yeteneğini artırmak, web uygulamasını kullanıcı
geri bildirimlerine dayalı olarak geliştirmek ve benzer projeleri entegre ederek daha kapsamlı bir çözüm sunmak
üzerine odaklanabilir. Bu proje, tarım sektöründe yapay zekanın bitki hastalıklarıyla mücadelede potansiyelini
vurgulayarak gelecekteki araştırmalara önemli bir katkı sağlıyor. Bu bağlamda, proje tarım sektöründe yapay
zeka teknolojilerinin etkinliğini ve uygulanabilirliğini gözler önüne sermektedir.

![Classes Distribution](https://github.com/Burakduran1/Ag_programlama/blob/main/Pictures/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-07-11%20140851.png)
![Classes Distribution](https://github.com/Burakduran1/Ag_programlama/blob/main/Pictures/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-07-11%20141013.png)




