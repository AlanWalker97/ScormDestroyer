Selam Arkadaşlar,

Yine bir trickle daha sizlerleyim 😀.

Biliyorsunuz ki 2022 sonunda bir çoğunuz Vlearn üzerindeki Güvenli Yazılım Geliştirme eğitimini tamamlamak için baya kasmıştı, şahsen ben videoların belki bir katkısı olur diye sene ortasında boş zamanlarımda oturup izlemiştim. Ancak bugün görmüşsünüzdür, size de vlearn’den eğitim maili gelmiştir. Açıp bakınca zaten izlediğimiz eğitimin tekrar bizden tamamlamamızı beklediklerini görünce bu işle ilgili kolları sıvamaya karar verdim ve videoları izlemeden vlearn’ü izlemiş gibi kandırabileceğiniz bir script yazdım.

Bu script ile totalde 6 kusur saat süren eğitimi yarım saatten kısa sürede bitirmeniz mümkün. Ayrıca bu scriptin sadece bu eğitim değil, scorm player ile oynatılan tüm eğitimler için işe yarayacağını düşünüyorum. Lafı daha fazla uzatmadan scripti nasıl kullanacağımıza geçelim.

Bu işi otomatize etme amacıyla tampermonkey chrome eklentisi kullandım. Eğer sizde yoksa bu eklentiyi chrome web mağazasından kurun. Kurulum bittikten sonra sağ üstteki tampermonkey ikonuna basıp create a new script diyin. Açılan sayfada kod yazdığımız alandaki tüm satırları temizleyip yukarıdaki scorm_destroyer_script.txt dosyası içerisindeki kodu yapıştırın ve Ctrl+S ile kaydedin. Daha sonra vlearn üzerinden bu eğimin herhangi bir part’ını açın videonun başladığını gördükten sonra f12 ye basarak console’a destroyScormPlayer() yazıp enterlayın. İşlem başarılı mesajını gördükten sonra videoyu kapatın. Video kapanınca biliyorsunuz ki vlearn sayfayı yeniliyor. Sayfa yenilenince ilgili eğitim videosunun tamamlandığını göreceksiniz. Bu şekilde eğitimi izlemeden hızlıca bitirebilirsiniz.

Şimdiden kolay gelsin, takıldığınız nokta olursa sorabilirsiniz 😊.
İyi çalışmalar.
