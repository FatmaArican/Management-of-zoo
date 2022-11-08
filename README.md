# Management-of-zoo
OOP patikası dahilinde hazırladığım Hayvanat bahçesi UML diyagramı

Bir hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için bir sistem tasarlandı.

Hayvanlar:
Atlar (atlar, zebralar, eşekler vb.),
Kedigiller (kaplanlar, aslanlar vb.),
Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edildi.

Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır. (tür adı, ağırlığı, yaşı vb.)

Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()
Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()

Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.

Polimorfizm modelini kullanarak, yukarıda açıklanan durumu ele alan bir sınıf diyagramı oluşturuldu.
