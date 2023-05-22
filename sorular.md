# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

2. Git ile GitHub arasında ne fark var?

3. Neden bir branch oluşturuyoruz?

4. Pull Request'in amacı nedir?

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

7. Merge conflict nedir?

8. Merge conflict'i nasıl çözeriz?


## Cevaplar

1. Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.

2. Git, içeriği (genellikle kod ama yazı, resim veya başka herhangi bir dosya türü de olabilir) depolamak için kullanılan bir sistemdir. GitHub bulut tabanlı bir git barındırma hizmeti sunan bir şirkettir. 

3. Bir repo'nun farklı sürümleri üzerinde birden fazla kişiyle aynı anda çalışabilmek ve diğerleri bir değişiklik yaptıysa bu güncellemeleri alabilmek için branch oluşturuyoruz.  

4. Pull request olarak göndermenin amacı; proje üzerinde değişiklik yaptığımı branch'den sorumlu kişiye iletmek ve kodu eklmek istediğimi belirtmektir.

5. git git switch

6. git fetch: Yerel depomu uzaktaki deponun içeriğine güncelle anlamına gelir. 
   git merge :Başka bir branch'da olan değişiklikleri, bulunduğumuz branch ile birleştirmek istediğimizde kullanılır. 
   git pull: Bu komut, uzak depodaki değişiklikleri almak ve bunları mevcut çalışma dizini ile birleştirmek için kullanılır.

7. Bireden fazla kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olur.

8. Git, merge conflict'i otomatik olarak çözmeye çalışır ancak bazen manuel olarak çözülmesi gerekir.
   Git conflict manuel çözmek için, kullanıcının ilk olarak dosyayı açması ve conflict yaratan bölümleri bulması gerekir. 
   Daha sonra, conflict yaratan bölümleri manuel olarak düzenlemek ve Git’e tekrar birleştirme işlemini yapması gerekir. 
   Bu işlemi yaparken, kullanıcının hangi değişikliklerin korunması gerektiğine karar vermesi gerekir.

