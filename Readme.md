Tüm fotoğrafları eit boyutlara getirmek için kullandığım uygulama: [Fotosizer] https://www.fotosizer.com/
Toplu resim indirmek için yararlandığım kaynak: https://medium.com/@ozgurs/h%C4%B1zl%C4%B1-%C5%9Fekilde-resim-dataseti-olu%C5%9Fturma-cfccf4a40c79
VeriSeti : kaggle...
Ödevin adımları:
A) İLK ADIM : Normal olarak CNN-maxpool olayı sürecinde örneğin 20-30 epoch seçilerek 
		Train/validation accuracy grafiği
		train/validation  loss grafiği
                            
B) İKİNCİ ADIM: Data augmentation yöntemi ile deney tekrarlanmalı
		Train/validation accuracy grafiği
		train/validation  loss grafiği

C) ÜÇÜNCÜ ADIM: Drop-out  ile deney tekrarlanmalı (augmentation dan devam ediyoruz en baştan başlamıyoruz!)  yani:  augmentation + drop_out etkisi gözlenecek! 
		Train/validation accuracy grafiği
		train/validation  loss grafiği

D) Overfitt eden nokta gözleniyorsa train süreci erken bir EPOCH’ta kesilerek  (artık augmentation, drop-out üzerine bir de epoch etkisi gözlenecek!)    
		Train/validation accuracy grafiği
		train/validation  loss grafiği

CNN-Maxpool nedir, nasıl çalışır?
Data Augmentation Nedir?
Drop-out Yönetimi Nedir?
Epoch kesmek nedir ne işe yarar?