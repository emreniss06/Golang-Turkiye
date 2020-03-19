---
description: >-
  Google'ı bilmeyen var mı? Ne güzel gizlimiz saklımız yok dercesine Go'yu açık
  kaynak yapmış. Ekmeğimizi banmadan önce biraz saygı duruşu niteliğinde tanışma
  faslına geçelim. El de sıkışırız tabii ki.
---

# Golang'ı Tanıyalım

### Golang arkadaşımıza Go da diyebiliriz hiç problem değil. Google 2007 yılından beri geliştirme yaparak açık kaynak olarak günümüze kadar hala devam eden çalışmalarıyla kullanılmaya hazır bir şekilde stabil bir dil oluşturdu.

{% hint style="info" %}
_Arama motorlarında “go” spesifik bir kelime olduğundan dolayı pek bir sonuca ulaşamayabilirsiniz. Bu yüzden “golang” olarak arama yapmalısınız._ 

_Birkaç “golang” arama sonucu gezintisi sonrasında “go” yazdığınızda sonuçların düzeleceğini umuyorum._
{% endhint %}

İlk versiyonu Kasım 2009 tarihinde çıktı. Ne kadar yeni keşfedilmeye başlanılsa da eski bir tarihi var. Bu sayede güvenimizi kazanıyor. Go'nun derleyicisi **Go Compiler** yine açık kaynak olarak birçok işletim sistemi için çalışmaya hazır olarak geliştirilmiştir. Bu arada derleyici, açık kaynak falan derken biliyoruz bu kavramları bilmeyen arkadaşlarımız olacaktır. Sayfanın en sonunda hepsini tek tek açıklayacağız.

**Neden Golang?**

Golang, Google'ın ihtiyaçları doğrultusunda bazı sorunların çözülmesi amacı ile üç üstat kişi tarafından ilk olarak deney amaçlı çıkmıştır. Diğer dillerde bulunan sorunları, sıkıntıları, gereksiz buldukları her şeyi çözmek ve diğer dillerin iyi taraflarını koruma amacını göz önünde bulundurularak güzel bir başlangıç yapmıştır. İnanın bu dili oluşturan adamlar tam anlamıyla bir üstatlar. Saygılarımızı buradan sunuyoruz onlara. Tabi bu kadar övgüyü hak eden insanların nasıl bir dil ortaya çıkardığı da malum olmalı.

**Kim bu üç üstat?**

<table>
  <thead>
    <tr>
      <th style="text-align:center">
        <p>&lt;b&gt;&lt;/b&gt;</p>
        <p>
          <img src="../.gitbook/assets/ken-thompson (2).jpg" alt/>
        </p>
      </th>
      <th style="text-align:center">
        <p></p>
        <p>
          <img src="../.gitbook/assets/rob-pike (1).jpg" alt/>
        </p>
      </th>
      <th style="text-align:center">
        <p></p>
        <p>
          <img src="../.gitbook/assets/robert-griesemer (1).jpg" alt/>
        </p>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center"><b>Ken Thompson</b>
      </td>
      <td style="text-align:center"><b>Rob Pike</b>
      </td>
      <td style="text-align:center"><b>Robert Griesemer</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:center">B, C, UNIX ve UTF-8</td>
      <td style="text-align:center">UNIX ve UTF-8</td>
      <td style="text-align:center">Hotspot ve JVM</td>
    </tr>
  </tbody>
</table>**Tamam da, bu dilin özellikleri ne?**

* Statik yazılmıştır, fakat dinamik rahatlığındadır.
* Büyük sistemlere ölçeklenebilir.
* Üretken ve okunabilir olması, çok fazla zorunlu anahtar kelime ve tekrarlamaların kullanılmaması
* Tümleşik Geliştirme Ortamına \(IDE\) ihtiyaç duyulmaması fakat desteklemesi
* Ağ ve çoklu işlemleri desteklemesi
* Değişken tanımında tür belirtimi isteğe bağlıdır.
* Hızlı derlenme süresi
* Uzak paket yöneticisi \(go get\)

**Tamam mıyız?**

Hadi artık biraz derleyiciyi kurmaya çalışalım. Diğer sayfada bekliyoruz.

