# Araç Fiyat Tahmin Projesi

Bu proje, araç fiyatlarını çeşitli faktörlere göre tahmin etmeye yönelik bir model geliştirmeyi amaçlamaktadır. Proje, araç yaşını, kondisyonunu, kilometresini, rengini ve performansını kullanarak fiyat tahminleri yapmaktadır. Kullanıcılar, bu verilerle bir araç için tahmin edilen fiyatı görebilirler.

## Proje Adımları

1. **Veri İlk Temas**  
   Bu aşamada, projemizin temelini oluşturan veri setine ilk kez temas edilir. Verinin yapısı, türü ve içeriği hakkında genel bir anlayış geliştirilir. Bu adımda, veri seti üzerinde temel incelemeler yapılır, eksik veya hatalı veriler belirlenir ve veri analizi için gerekli ilk hazırlıklar gerçekleştirilir.

2. **Veri Görselleştirme**  
   Veri görselleştirme aşamasında, veri setindeki bilgilerin daha iyi anlaşılması için çeşitli grafikler ve görsel araçlar kullanılır. Bu adımda, veri içindeki trendler, ilişkiler ve dağılımlar görsel olarak temsil edilir. Grafikler, histogramlar, scatter plotlar gibi çeşitli görselleştirme teknikleri kullanılarak verinin anlaşılması kolaylaştırılır.

3. **Model Kurma**  
   Model kurma aşamasında, veriyi analiz etmek ve tahminler yapmak için uygun makine öğrenme modelleri oluşturulur. Bu adımda, çeşitli modeller (örneğin, regresyon, sınıflandırma, vb.) seçilir ve eğitilir. Modelin performansını değerlendirmek için çapraz doğrulama ve hiperparametre ayarları yapılır. Bu süreç, modelin veriye nasıl uyduğunu ve tahmin performansını değerlendirmek için kritik öneme sahiptir.

4. **Tahmin Yaptırma**  
   Model kurma aşamasında elde edilen modeller ile tahminler yapılır. Bu adımda, modelin performansı test edilir ve gerçek veri üzerinde tahminler yapılır. Tahmin sonuçları, modelin doğruluğunu ve verinin ne kadar iyi temsil edildiğini değerlendirmek için kullanılır. Bu aşamada elde edilen sonuçlar, modelin uygulanabilirliği hakkında bilgi sağlar.

5. **GUI ile Kullanıcı Tercihine Göre Tahmin Yapma**  
   Kullanıcıların modelden tahminler alabilmesi için bir grafiksel kullanıcı arayüzü (GUI) oluşturulur. Bu aşamada, tkinter gibi araçlar kullanılarak kullanıcı dostu bir arayüz tasarlanır. Kullanıcı, bu arayüz aracılığıyla araç bilgilerini girer veya seçer ve model tarafından yapılan tahminleri görüntüler. GUI, kullanıcı deneyimini artırmak ve etkileşimi kolaylaştırmak için tasarlanır.

6. **Sonuç**  
   Projenin bu son aşamasında, yapılan tahminler ve analizler özetlenir. Elde edilen sonuçlar değerlendirilir ve projenin genel başarısı hakkında bir değerlendirme yapılır. Bu adımda, kullanıcı arayüzü ve model performansı gözden geçirilir, elde edilen sonuçlar yorumlanır ve projenin güçlü ve zayıf yönleri hakkında bilgi verilir. Sonuçlar, projenin amacına ulaşıp ulaşmadığını belirlemek ve gelecekteki geliştirmeler için öneriler sunmak için kullanılır.

## Veri Seti

Proje veri seti aşağıdaki sütunları içermektedir:
- `id`: Araç kimlik numarası
- `full_name`: Araç tam adı
- `age`: Araç yaşı
- `gender`: Araç türü (örneğin, Sedan, SUV)
- `model`: Araç modeli
- `color`: Araç rengi
- `performance`: Araç performansı
- `km`: Kilometre
- `condition`: Araç kondisyonu (örneğin, Good, Fair, Poor)
- `price`: Araç fiyatı

## Kullanım

1. **Gerekli Kütüphaneler**  
   Proje, aşağıdaki Python kütüphanelerini kullanmaktadır:
   - `pandas`
   - `numpy`
   - `scikit-learn`
   - `tkinter` (GUI için)

2. **Kurulum**  
   Gerekli kütüphaneleri yüklemek için aşağıdaki komutu kullanabilirsiniz:
   ```bash
   pip install pandas numpy scikit-learn


## Veri Analizi ve Model Eğitimi
Veri analizi ve model eğitimi aşamalarını analysis_and_training.py dosyasında bulabilirsiniz.

## GUI Kullanımı
GUI ile kullanıcı tercihine göre tahmin yapmak için gui.py dosyasını çalıştırabilirsiniz. Bu dosya, tkinter kullanarak kullanıcı arayüzü sağlar ve tahminler yapar.

## Katkıda Bulunanlar
[İbrahim Püsküülü] - Proje Yöneticisi ve Geliştirici
## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.
