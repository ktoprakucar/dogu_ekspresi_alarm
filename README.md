# Doğu Ekspresi Alarm Uygulaması
Seçilen günde, Ankara-Kars doğu ekspresi tren biletleri çıktığı anda alarm çalan uygulama.

## Gereksinimler
Uygulamayı çalıştırabilmeniz için bilgisayarınızda Python'un kurulu olması gerekmektedir. Bu uygulama Jupyter Notebook'ta geliştirildi. Eğer bilgisayarınızda kurulu değilse ve sadece Python kurulu ise, kodu kopyalayıp kendi platformunuzda çalıştırabilirsiniz. 

Ayrıca alarm çalmak için *playsound* paketini kullandık. Paketi PyPi'den **pip install playsound** komutu ile indirebilirsiniz

## Seçenekler
Tarihi *date* ve kişi sayısını da *passengers* parametreleriyle belirleyip uygulamayı çalıştırın. Parametrelere herhangi bir kontrol koymadık. Tarihi **GG.AA.YYYY** formatında **String** olarak, yolcu sayısını da aynı şekilde **String** olarak girmeniz gerekmektedir. 

#### Önemli Not : **Tarihle ilgili olarak da, biletler yolculuk gününden 1 ay önce satışa çıkmaktadır.**

## Uygulama Nasıl Çalışır?
Girmiş olduğunuz parametrelerden sonra, uygulama bir döngü içinde çalışır. Biletlerin seçildiği istek atar, eğer biletler çıktıysa alarm çalar. Eğer satışa çıkmadıysa, çıkana kadar sorgu atmaya devam eder. 

p.s. Bu uygulamayı yazma amacımız geceyi bilgisayar başında geçirmeyip, uykunuzdan olmamanızdır. Bilet almayı kesinlikle garanti etmez. Bilet alabilme durumu tamamiyle sizin uykudan uyanma hızınız ve koltuk seçme hızınıza bağlıdır. (ayrıca biletlerin tamamiyle adil bir şekilde satıldığını da düşünmüyoruz..)

