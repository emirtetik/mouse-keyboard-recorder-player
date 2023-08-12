# Mouse ve Klavye Hareketlerini Tekrarlayan Aracı

Bu proje, kaydedilmiş mouse ve klavye hareketlerini tekrarlayan bir aracı içerir. 'recording.py' ile hareketleri kaydedebilir ve 'player.py' ile kaydedilen hareketleri tekrar oynatabilirsiniz. Ayrıca, 'main.py' kullanılarak bu işlemleri birleştiren ve .exe dosyasına dönüştüren bir sürüm mevcuttur.

## Kurulum

1. Bu projeyi klonlayın: `git clone https://github.com/emirtetik/mouse-keyboard-recorder-player.git`
2. Gerekli bağımlılıkları yüklemek için: `pip install -r requirements.txt`
3. Bu videodan kodun ne işe yaradıgını daha iyi anlayabilirsiniz: `https://www.youtube.com/watch?v=MpmAD-Hd0OQ`
4. ben kodları birleştirdim ve sonsuz bir döngüde kodun işlemesini sağlamaya çalıştım.
   
## Kullanım

### Hareketleri Kaydetme ve Oynatma

- 'recording.py' dosyasını çalıştırarak hareketleri kaydedebilirsiniz.
- Varsayılan olarak 200 px kaydedilir. Eğer farklı bir değer girmek isterseniz, "Yeni bir px değeri girmek istiyor musunuz? (Y/n)" sorusuna cevap vererek devam edebilirsiniz.
- Hareketler 'event.json' dosyasına kaydedilir.
- 'player.py' dosyasını çalıştırarak kaydedilen hareketleri tekrar oynatabilirsiniz.

### .exe Dosyası Oluşturma

- 'main.py' dosyası, kaydetme ve oynatma işlemlerini birleştiren bir versiyon içerir.
- Projeyi kullanıcı dostu bir arayüze dönüştürmek ve .exe dosyası olarak kullanmak isterseniz, 'main.py' dosyasını kullanabilirsiniz.
- pip install pyinstaller ile .exe dosyası oluşturabilirsiniz.
- dikkat edin başka bir bilgisayara aktarmak isterseniz pyinstaller --onefile yerine --onedir kullanmanız önemli sonra .exe dosyanızda hatalar çıkabilir.



