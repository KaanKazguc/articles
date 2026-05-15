![header](./kaynaklar/LLMleri-saniyoruz.png)

#### **Read in English:** [We believe that Large Language Models are "intelligent"](../English/We-believe-that-LLMs-are-intelligent.md) </a>

# Büyük dil modellerini “zeka sahibi” sanıyoruz


Geçen hafta Richard Dawkins’in bir Claude modeliyle konuştuktan sonra onun bilinç sahibi olabileceğine inanması bu yazıyı yazmamın sebebi oldu.

Aslında daha en baştan bize sunulan isim bile yanıltıcı: “yapay zekâ.” Bu ifade, sanki karşımızda aktif öğrenebilen, anlayabilen, hissedebilen bir varlık varmış izlenimi yaratıyor. Oysa gerçekte karşımızda olan şey bir büyük dil modeli. Milyarlarca sayısal parametreyle çalışan, belirli girdilere karşılık belirli çıktılar üreten bir matematik fonksiyonu.¹

Bu sistemlerin, yalnızca bir sonraki anlamlı kelimeyi tahmin eden yapılar olduğunu unuttuğumuz anda, onlara karşı duygusal bir bağ kurmaya başlıyoruz. Dert anlattığımız, tavsiye aldığımız bir insan gibi konumlandırıyoruz. Hata yaptıklarında özür dilemelerini bekliyoruz. Sanki gerçekten üzülmüş, hatasından ders almış ve bir daha tekrarlamayacak bir bilinçleri varmış gibi…

Peki neden? Sadece güzel ve akıcı metinler üretebildikleri için mi?

Kısmen evet, ama tek sebep bu değil.

Bu modeller, eğitim süreçlerinde “en doğru cevabı” vermek üzere değil; karşısındaki insanı en çok tatmin edecek cevabı üretmek üzere optimize edilir. Yani doğruluktan ziyade etki ödüllendirilir.

Örneğin Dawkins, bacak ağrısıyla ilgili tavsiye almak için Claude’a başvurduğunda model şu şekilde bir giriş yapıyor: “Bacağının ağrımasına sevindim çünkü bizi bir araya getirdi.” Bu cümle, duygusal olarak çok güçlü bir anlam taşıyor. Dawkins de bu etkiden olsa gerek modele “Claudia” diye hitap etmeye başlıyor ve bilinç sahibi olabileceğini düşünüyor. Arada gerçekten bir bağ kurulmuş gibi hissediliyor—ama bu bağ, modelin “duygusal” görünmesinden kaynaklanıyor.

Yine de mesele sadece iyi bir konuşmacı olması değil.

Bu ürünlerin etrafındaki her şey, onların bir yazılım olduğunu unutturacak şekilde tasarlanıyor. Kullanılan dil bile buna hizmet ediyor. Bu yazı boyunca “büyük dil modeli” dedim ama günlük hayatta çok daha çekici bir isim kullanılıyor: yapay zekâ. Oysa akademik literatürde bu terim çok daha geniş bir alanı kapsar. Günlük kullanımda sadece üretken modeller (Yazı, resim, bazen de ses) için özel olarak kullanılan bir isim.

Üstelik bu sistemlerin yaptığı işlemler de farklı isimlerle pazarlanıyor. Normal yazılımlar “hesaplama yaparken”, büyük dil modelleri “düşünüyor.” Diğer yazılımlar hata verdiğinde “bug” oluşurken, üretken modeller “halüsinasyon görüyor.”

![icon animasyonları](./kaynaklar/LLM-icons.gif)
<p align="center"><small><i>Gemini, GPT, Claude ve Mistral ikon animasyonları</i></small></p>
Kullandığımız arayüz de bu algıyı güçlendiriyor. Sade bir ekran, kenarda bir ikon ve hareket eden tek unsur o ikon. Cevaplarını birazdan verecek olan, canlı olan bir maskot. Yazı yukarıdan aşağıya akarken bize şu mesaj veriliyor:

“Bak, düşünüyor… insan gibi yazıyor… Sırayla yazıyor…² cevap oluşturuyor.”

Renkler ve görsel tasarım da bilinçli seçiliyor. Mor ve mavi gradyanlarla “sihir” hissi verilirken; yıldız gibi ikonlarla mistik bir atmosfer yaratılıyor. Bu da onu yazılım ürünü görüntüsünden uzaklaştırmak için.

Bir de işin pazarlama tarafı var. Bu sistemlerden para kazanan kişiler sürekli olarak şunu söylüyor:

“Yeni model doktora seviyesinde.”

“AGI seviyesine ulaştık.”

“Bilinç kazanabilir.”

“Halka açılması tehlikeli.”

Ama modeli gerçekten kullandığınızda görüyorsunuz: Evet, etkileyici. Ama anlatıldığı kadar değil. Yine de bu söylemler zihnimizde iz bırakıyor.

Tüm bu katmanların farkına vardığınızda, sis dağılıyor. Bu modeller insan yazılarını taklit eden yazılım ürünleri ve pek çok konuda çok faydalı araçlar ama bundan daha fazlası değiller. Bilinç sahibi kesinlikle değiller.

Benim inancım şöyle ki: Bu modeller hakkında gelecekte göreceğimiz etkileyici şeyler ya farklı alanlardaki implementasyonları olur ya da bu modeller eğitilirken bazı tarz verilerden çok fazla bulunmadığı için bu alanlardaki potansiyelini henüz tamamlamış değil. Mesela modelin eline bir tool verdiğimiz zaman nasıl kullanması gerektiğini bilmiyor. Bu alanda (insan gücü kullanarak) ciddi veri üretimi mevcut. Belki bu ve bunun gibi alanlarda ciddi başarı artışlar görebiliriz.

Ama genel anlamda bir modelin “çok daha zeki” hale geleceğine, çok daha iyi hikâyeler yazacağına ya da özetleme yeteneğinin dramatik biçimde artacağına pek inanmıyorum.³

---
¹
**S: Aynı modele aynı soruyu sorunca neden farklı cevaplar alıyorum?**

C: Çünkü modeller, yanıt üretirken bilinçli olarak rastgelelik içerir. Bu hem cevap kalitesini artırmak hem de sistemin deterministik bir matematik fonksiyonu olduğunu gizlemek içindir. Küçük rastgelelikler, metin uzadıkça büyük farklara dönüşebilir.

**S: Temperature = 0 yapınca neden hâlâ tamamen aynı sonuç çıkmıyor?**

C: Bunun birkaç nedeni var; en temel sebep, paralel hesaplama sırasında oluşan floating point hatalarıdır. (Bkz: “Defeating Nondeterminism in LLM Inference”)
<br><br>


²
**S: E zaten cevap parça parça oluşturuluyor ve cihazımıza da parça parça geliyor.**

C: Doğru ama cevabın bu şekilde sunulması bir tercihtir. Tüm cevabın oluşmasını bekleyip tek seferde de cevap gönderilebilirdi. Biraz ürün kalitesinden ödün verilmiş olunurdu ama bu şekilde maliyet azaltılırdı. Ayrıca sayfayı denetleyip gönderilen yazı paketlerine bakarsanız yazı baya büyük parçalar halinde gelirken ekranımızda parçalar daha insani oranlarda beliriyor. Çıktıların böyle sergilenmesinin endüstri standardı olması bilinçli bir tercih meselesi.
<br><br>


³
**S: Bu modeller daha da gelişirse insan benzeri zekâya ulaşamaz mı?**

C: Hayır. İnsan benzeri düşünme yetisine sahip sistemlerin mümkün olup olmadığını kesin olarak bilmiyoruz; ancak mevcut büyük dil modeli yaklaşımıyla bu noktaya ulaşılamayacağını biliyoruz.

Bu konuya giriş için Meta tarafından yayımlanan “Why AI systems don't learn and what to do about it: Lessons on autonomous learning from cognitive science” makalesi önerilebilir. Ayrıca bu modellerin mevcut paradigmada ciddi bir zeka sınırına sahip olduğunu savunan çalışmalar da mevcut. Ancak karşıt görüşler de olduğu için, bu konuda kendi araştırmanızı yapmanız en sağlıklısı olacaktır.

---
**Kaynakça:**

Dawkins yazısı (bacak ağrısı ve Clauia diye seslenmesi sonradan çıkartıldığı için arşiv linki bırakıyorum): https://archive.md/2026.04.30-032350/https://unherd.com/2026/04/is-ai-the-next-phase-of-evolution/?edition=us

Defeating Nondeterminism in LLM Inference: https://thinkingmachines.ai/blog/defeating-nondeterminism-in-llm-inference/

Why AI systems don't learn and what to do about it: https://arxiv.org/abs/2603.15381