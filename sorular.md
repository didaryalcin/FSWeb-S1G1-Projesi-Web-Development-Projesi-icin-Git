# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, dağıtık bir sürüm kontrol sistemi ve kaynak kod yönetim aracıdır. Geliştiricilerin proje dosyalarının farklı sürümlerini takip etmelerini, değişiklikleri izlemelerini, işbirliği yapmalarını ve projeleri yönetmelerini sağlayan bir yazılımdır. Git, özellikle yazılım geliştirme süreçlerinde yaygın olarak kullanılır ve projelerin geçmişini kaydederek eski sürümlere geri dönme, paralel geliştirme dalları oluşturma gibi işlevlere sahiptir.

2. Git ile GitHub arasında ne fark var?

Git, bir sürüm kontrol sistemi veya kaynak kod yönetim aracıdır. GitHub, Git tabanlı projelerin barındırılması, işbirliği yapılması ve paylaşılması için bir bulut tabanlı platformdur.

3. Neden bir branch oluşturuyoruz?
Branch oluşturmak, projenin düzenli ve etkili bir şekilde geliştirilmesine ve yönetilmesine yardımcı olur. Her bir dal, belirli bir görevi veya değişikliği izlemek için kullanılır ve ana projeyi korurken geliştirme sürecini düzenler.






4. Pull Request'in amacı nedir?
Pull requestler, açık kaynaklı projelerden büyük şirket içi yazılım geliştirme süreçlerine kadar birçok senaryoda kullanılır. Bu süreç, yazılım geliştirme ekibinin işbirliği yapmasını, değişikliklerin kalitesini artırmasını ve projenin sağlıklı bir şekilde yönetilmesini sağlar.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
Mevcut branch'i kaydetmek ve değişiklikleri tamamlamak (commit):Bu komut, "main" branch'ine geçer ve çalışma alanınızı bu branch'e taşır. Artık "main" branch'inde çalışıyormuş gibi devam edebilirsiniz.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch uzaktaki değişiklikleri indirir, git merge iki branch'i birleştirirken kullanılır ve git pull, uzaktaki değişiklikleri alır ve hemen yerel branch'le birleştirir. Hangi komutun kullanılacağı, ihtiyacınıza ve çalışma akışınıza bağlıdır.
7. Merge conflict nedir?
Merge conflict, aynı dosyanın aynı satırlarında farklı değişikliklerin yapıldığı durumlarda, Git veya diğer sürüm kontrol sistemlerinde iki veya daha fazla dalın birleştirilirken ortaya çıkan bir durumdur. Bu, sürüm kontrol sistemi tarafından otomatik olarak çözülemediği için geliştiricilerin müdahale etmesi gereken bir durumdur.

8. 
Merge conflict çözmek için aşağıdaki adımları takip edebilirsiniz:

İlk adım, merge conflict'ı çözmek için etkilenen dosyayı bir metin düzenleyici veya kod düzenleyici ile açmaktır.

Çakışan bölgeleri tanımlamak için Git tarafından eklenen işaretlemeyle çakışmanın olduğu bölgeyi belirleyin. Genellikle <<<<<<<, =======, >>>>>>> gibi işaretler kullanılır. Bu işaretler arasındaki bölge, çakışan değişiklikleri gösterir.

Çakışan değişiklikleri inceleyin ve nasıl çözmek istediğinizi belirleyin. İki geliştiricinin yaptığı değişiklikler arasında bir denge sağlamak veya birini tercih etmek gerekebilir.

Conflict'ı çözdüğünüzde, dosyayı kaydedin.

İşaretleme işaretlerini (örneğin <<<<<<<, =======, >>>>>>>) kaldırın ve dosyayı yeniden kaydedin.

Çözülen conflict'ı işaretlemek için Git'e git add komutunu kullanın.

Yeniden commit yapın. Commit mesajınızda, merge conflict'ı çözmek için ne yaptığınızı açıklayıcı bir şekilde yazın.

Commit'i kaydettikten sonra, merge işlemini tamamlayın.

Merge conflict çözüldüğünde, iki dal başarıyla birleştirilmiş olur. Çakışan değişiklikleri nasıl çözeceğinizi seçmek ve uygun bir şekilde işaretlemek, projenizin bütünlüğünü korumak ve istenmeyen çakışmaları gidermek için önemlidir