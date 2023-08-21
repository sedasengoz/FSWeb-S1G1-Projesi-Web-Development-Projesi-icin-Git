# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir? Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git ile yapacağımız projede adım adım kopya alarak daha sonra ihtiyaç duyduğumuzda bu kopyalara kolayca dönebiliriz.

2. Git ile GitHub arasında ne fark var? Git, bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz portaldır.

3. Neden bir branch oluşturuyoruz? Branch ile yazılımda repolarımızla farklı dallar oluştururuz yani bir nevi kopyasını oluştururuz. Projemizde bir şeyler denemek yada değiştirmek için branch kullanılır.

4. Pull Request'in amacı nedir? Pull Request, proje sahibinin projede yapılan commitleri kabul etmesidir. Proje sahibi onayladıktan sonra yapılan değişiklikler yani commitler projeye dahil olur.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın? Git checkout main komutunu kullanırız.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız. Git fetch ile remote repodan local bilgisayarına değişiklikleri eklersin ancak değişiklikleri kaydetmezsin. Fetch değişiklikleri commit etmeden önce onları gözden geçirmene izin verir. 
Git merge ile birbirinden bağımsız brancleri birleştirirsin. Git pull ile de remote repodaki son güncellemeleri local bilgisayarına çekmek için kullanılır. Git fetch de değişiklikleri yerel bilgisayara alıp bunları uygulamazken Git pull da değişiklikleri alıp bir de bunları kendi commitleri ile birleştirip merge eder.

7. Merge conflict nedir? İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çatışma meydana gelir.

8. Merge conflict'i nasıl çözeriz? Bu durumda Git, conflict bildirir ve kullanıcının bu çatışmayı manuel olarak çözmesini ister. Git conflict çözmek için, kullanıcının ilk olarak dosyayı açması ve çatışmalı bölümleri bulması gerekir.
Daha sonra çatışmalı bölümleri manuel olarak düzenlemek ve Git'e tekrar birleştirme işlemini yapması gerekir.
