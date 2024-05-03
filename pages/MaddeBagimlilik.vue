<template>
  <div class="w-full">
    <div class="w-full flex flex-col items-center">
      <h2 data-aos="flip-down" class="text-3xl sm:text-4xl font-semibold text-center">Madde Bağımlılığı</h2>
    </div>
    <section class="w-full">
      <div id="1"></div>
      <BaseSection>
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 mt-4 xl:mt-20 space-y-6 px-4">
          <h2 class="text-4xl font-semibold sm:pr-8 xl:pr-12">Madde Bağımlılığı Nedir?</h2>
          <p class="paragraph">
            Sağlığı olumsuz yönde etkileyen maddenin kullanılmasının yanı sıra bireyin zarar gördüğü halde kullanımı bırakamaması,
            madde bağımlılığı nedir, sorusuna verilebilecek en basit yanıttır. Madde bağımlısı alkol,
            uyuşturucu içeren maddeleri tüketen ve bu maddelere bağımlı olan kişilerdir. <br />
            <br />
            Madde bağımlısı kişiler ruhsal, fiziksel ve psikolojik olarak zarar görseler bile bağımlı oldukları maddeyi bırakmaz.
            Madde bağımlılığı kişinin yaşamını ciddi derecede zarar verebilir. Kişi madde içmediği zamanlar,
            maddeyi almaya karşı aşırı istek duyabilir. Maddeyi almayı bıraktıklarında yoksunluk belirtileri gösterir.
            <br />
            <div id="nav"></div>
            <br />
            Birden fazla madde bağımlılığı çeşidi bulunur. Madde bağımlılığı insanın yaşamını tehdit edici bir duruma sokabilir.
            Kişi kendini daha iyi hissetmek için bu maddelere yönelir. Bu bireylerde ruhsal,
            fiziksel ve psikolojik bozukluklar görülebilir. Kişi maddeyi bulamazsa çöküntüye girer.
            Madde bağımlısı kişiler bir uzman gözetimi altında tedavi görmesi gerekir.  <br />
            <br />
            <!-- Şiddetin yerine barışı ve hoşgörüyü tercih etmek, her birimizin sorumluluğudur. Küçük çatışmaları bile şiddet yoluyla çözmek yerine, iletişim, anlayış ve uzlaşma yoluyla çözmeliyiz. Bu, daha sağlıklı, daha mutlu ve daha barışçıl bir toplum için adım atmaktır.
          Sonuç olarak, şiddetin hiçbir kazananı yoktur. Şiddet, sadece acıyı ve zararı artırır. Bu nedenle, hepimiz şiddeti reddetmeli ve barış içinde bir arada yaşamanın yollarını bulmalıyız. Her birimiz, küçük adımlarla bile şiddete karşı durabilir ve daha iyi bir dünya için çalışabiliriz. <br> <br> -->
          </p>
        </div>
        <LandingMaddeResimImage data-aos="fade-left" class="hidden sm:block py-48" />
      </BaseSection>
    </section>

    <section
      class="max-w-screen-xl mx-2 mt-52 sm:mx-auto px-4 sm:px-6 lg:px-0 py-6 pb-20 sm:py-8 rounded-[2.25rem] sm:rounded-xl bg-white shadow-lg sm:shadow-md transform lg:-translate-y-12"
    >
      <ul :class="[open ? 'flex' : 'hidden lg:flex']" class="w-full gap-8 h-auto flex justify-center">
        <a href="#1">1</a>
        <a href="#2">2</a>
        <a href="#3">3</a>
        <a href="#4">4</a>
      </ul>
    </section>

    <!-- Partners section -->
    <div id="2"></div>
    <section class="bg-partner relative max-w-full sm:mx-6 mt-36 shadow sm:rounded-2xl overflow-hidden">
      <div class="w-full px-6 sm:px-0 py-16 flex flex-col items-center justify-center space-y-4 text-center">
        <h3 data-aos="flip-down" class="text-2xl text-neutral-800 font-semibold mb-10">
          Teknoloji Bağımlılığının Tedavi Yöntemleri
        </h3>
        <div data-aos="fade-up" class="flex flex-wrap items-center justify-center gap-28 font-bold">
          <p>Alkol bağımlılığı </p>
          <p>Sigara bağımlılığı</p>
          <p>Esrar bağımlılığı</p>
          <p>Ot bağımlılığı</p>
          <p>Kafein bağımlılığı</p>
          <p>İlaç bağımlılığı</p>
        </div>
      </div>
    </section>

    <!-- Credit card section -->
    <section class="w-full">
      <div id="3"></div>
      <BaseSection data-aos="fade-down">
        <div class="col-span-12 lg:col-span-7">
          <div class="w-full">
            <img :src="require('~/assets/img/MaddeBagimlilik/madde-2.jpg')" class="w-[95%] mt-48" alt="" />
          </div>
        </div>
        <div class="col-span-12 lg:col-span-5 space-y-6 px-4 sm:px-6 mt-20">
          <h2 class="text-4xl font-semibold">
            Madde Bağımlılığı <span class="text-header-gradient"> Belirtileri </span> Nelerdir
          </h2>
          <h2 class="font-bold">Şiddet eğilimindeki artışla birlikte ortaya çıkan saldırgan davranışlar;</h2>
          <h2 class="font-bold">Çevrenizden birinin madde bağımlısı olduğundan şüpheleniyorsanız belirtilere bakarak anlayabilirsiniz, Belirtileri Aşağıdaki gibi Sıralanabilir;</h2>
          <ul class="space-y-4 sm:space-y-2">
            <LandingListItem title="Maddeyi kullanmak için güçlü bir istek ve dürtüye sahip olmak" />
            <LandingListItem title="Madde kullanımını azaltmak ve kontrol altına alamamak" />
            <LandingListItem title="Madde kullanımı nedeniyle sosyal aktivitelerden vazgeçmek" />
            <LandingListItem title="Huzursuzluk ve gerginlik hali" />
            <LandingListItem title="Olumsuz davranışlarda artış" />
            <LandingListItem title="Fiziksel ve ruhsal sıkıntılar yaşamak" />
            <LandingListItem title="Yalnız kalmak istemek ve çevreden uzaklaşmak" />
            <LandingListItem title="Uyku bozukluğu" />
            <LandingListItem title="Mide bulantısı ve kusma" />
          </ul>
        </div>
      </BaseSection>
    </section>

    <!-- Advanced trading tools section -->
    <section class="bg-trading-tools relative max-w-full sm:mx-4 my-20 py-16 shadow rounded-2xl overflow-hidden">
      <div id="4"></div>
      <div class="relative max-w-screen-xl px-4 sm:px-2 mx-auto grid grid-cols-12 gap-x-6">
        <LandingTradingToolImage class="sm:hidden" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 space-y-8 sm:space-y-6 px-4 sm:px-6 mt-8">
          <h2 class="text-3xl font-semibold">Madde Bağımlılığı <span class="text-header-gradient"> Tedavi </span>Yöntemleri Nelerdir?</h2>
          <h2 class="font-bold">Madde bağımlılığı tedavisi olan bir hastalıktır. Madde bağımlılığı tedavisi kişinin kendi çabaları ile geçmesi pek mümkün değildir. Kişinin bir uzman gözetimi altında olması tavsiye edilir Bunlar;</h2>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Detoksifikasyon:</h4>
            <p class="paragraph text-sm xl:text-base">
              Burada kişiden bağımlı olunan madde kullanımı kesilir.
              Yoksunluk belirtilerini azaltmak için daha az bir dozda bağımlılık yapıcı ilaçlar kişiye verilir.
              Bağımlı olan kişinin vücudundan madde tamamen arındırılmaya çalışılır.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Bilişsel ve davranışsal terapi:</h4>
            <p class="paragraph text-sm xl:text-base">
              Psikoterapi ile zihinsel sağlık tedaviye yardımcı olur.
              Terapi sayesinde birey duygu ve düşüncelerini yakından gözlemler.
              Terapi ile olumsuz düşünceleri ve davranışları daha sağlıklı bir yapıya çevirmeyi öğrenilir.
              Değişmeye karşı motivasyonu yükseltmeye çalışılır. Grup terapisi, aile terapisi gibi farklı terapi yöntemleri bulunur.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Rehabilitasyon:</h4>
            <p class="paragraph text-sm xl:text-base">
            Bu en uzun olan süreç olarak da bilinir.
            Diğer yöntemler arasında ise; ayakta tedavi, 
            yatarak tedavi, korunma tedavisi, ilaç tedavisi gibi birçok farklı tedavi yöntemi sayılabilir.
            </p>
          </div>
        </div>
        <LandingMaddeResimImageth data-aos="fade-left" class="hidden sm:block m-auto" />
      </div>
    </section>

    <!-- Industry-leading security section -->

    <section class="bg-trading-tools relative max-w-full sm:mx-4 my-20 py-16 shadow rounded-2xl overflow-hidden">
      <div id="4"></div>
      <div class="relative max-w-screen-xl px-4 sm:px-2 mx-auto grid grid-cols-12 gap-x-6">
        <LandingTradingToolImage class="sm:hidden" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 space-y-8 sm:space-y-6 px-4 sm:px-6 mt-8">
          <h2 class="text-3xl font-semibold">Madde Bağımlılığı Hakkında Sıkça Sorulan Sorular</h2>
          <h2 class="font-bold">Madde bağımlılığı tedavisi olan bir hastalıktır. Madde bağımlılığı tedavisi kişinin kendi çabaları ile geçmesi pek mümkün değildir. Kişinin bir uzman gözetimi altında olması tavsiye edilir Bunlar;</h2>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">MADDE BAĞIMLILIĞI EVDE TEDAVİ EDİLİR Mİ?</h4>
            <p class="paragraph text-sm xl:text-base">
            Madde bağımlılığı kişinin tek başına başa çıkabileceği bir şey değildir.
            Maddeyi bırakmayı denediği zaman bağımlı olunan madde için yoğun istek ve yoksunluk belirtileri gösterir.
            Bunun sonucunda bağımlı olan kişi tekrar madde kulanımına başlayabilir.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">MADDE BAĞIMLILIĞI GENETİK MİDİR?</h4>
            <p class="paragraph text-sm xl:text-base">
            Kişinin madde bağımlısı olma nedenlerinden birisi genetik yatkınlık olabilir.
            Araştırmacıların yaptıkları araştırmalara göre madde bağımlılığında 
            genetik yatkınlık büyük bir role sahiptir. Bireyin anne ya da babası
            bağımlı kişiler ise çocukların da bağımlılık riski vardır.
            Araştırmacılara göre madde bağımlılığının %50’sinin nedeni genetik yatkınlıklardır.
            Bu durum kesinlikle bağımlı olunacağı anlamına gelmez. Sadece riskin yüksek olduğu bilinmesi gerekir.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">MADDE BAĞIMLISI OLAN BİRİNE NASIL DAVRANILMALIDIR?</h4>
            <p class="paragraph text-sm xl:text-base">
            Madde bağımlısı olan kişiye yargılamadan iletişim kurulmaya çalışılmalıdır. Panik yapılmamalıdır.
            Kişi ile iletişim kurulmaya çalışıldığında bağımlı olan kişinin madde etkisinde olması gerekir.
            Destek olunmaya çalışılmalı, samimi ve empatik yaklaşılmalıdır.
            Amacının yardımcı olmak olduğu söylenmelidir. Bağımlı bireyin tedavi için kaygılandırılmaması gerekir.
            Saydığı ve sevdiği kişi ile iletişim kurulmaya çalışılıp yardımcı olunmalıdır.
            </p>
          </div>
        </div>
        <LandingMaddeResimImagefr data-aos="fade-left" class="hidden sm:block m-auto" />
      </div>
    </section>

    <div class="fixed top-[85%] right-10">
      <a
        v-smooth-scroll
        data-aos="flip-down"
        data-aos-delay="150"
        href="#nav"
        class="flex items-center space-x-2 p-3 bg-[#FAFAFA] hover:bg-gray-100 hover:shadow-md border border-[#DDDDDD] rounded-full text-gray-700"
      >
        <ArrowUpIcon :size="20" />
      </a>
    </div>
  </div>
</template>

<script>
import aosMixin from '@/mixins/aos'
export default {
  name: 'SiddetBagimlilik',
  mixins: [aosMixin],
  data() {
    return {
      selected: 0,
      dropdownConcurency: false,
      dropdownCrypto: false,
      currencySelected: {
        img: 'country-icon/eng.png',
        name: 'USD',
      },

      steps: [
        {
          img: 'headache-clipart-men.png',
          title: 'Bilinçlenme ve Kabul',
          description:
            'Bağımlılıkla mücadelede ilk adım, bağımlı kişinin durumunu kabul etmesi ve bağımlılıkla ilgili gerçekleri anlamasıdır. Bağımlı kişi, bağımlılığının kendisine ve çevresine verdiği zararları fark etmeli ve bu durumu değiştirmek istediğini kabul etmelidir.',
        },
        {
          img: 'png-transparent.png',
          title: 'Destek Arama ve Profesyonel Yardım Almak',
          description:
            'Bağımlı kişi, bağımlılıkla mücadelede yalnız değildir ve çeşitli destek kaynaklarından faydalanabilir. Bu kaynaklar arasında aile üyeleri, yakın arkadaşlar, bağımlılıkla ilgilenen kuruluşlar ve profesyonel sağlık uzmanları bulunmaktadır. ',
        },
        {
          img: 'recovery_recuperation.png',
          title: 'Değişim İçin Adım Atma ve Tedaviye Başlama',
          description:
            'Bağımlı kişi, bağımlılığıyla mücadele etmek için somut adımlar atmaya hazır hissediyorsa, bir tedavi programına başlamak önemlidir. Bu programlar genellikle tıbbi tedavi, psikoterapi, grup terapisi, destek grupları gibi çeşitli hizmetlerden oluşur ve bağımlı kişiye bağımlılığıyla başa çıkma becerilerini geliştirmesinde yardımcı olur.',
        },
      ],
    }
  },
}
</script>
<style scoped>
.text-header-gradient {
  background: rgb(0, 253, 8);
  background: linear-gradient(169.4deg, #2bf23c -6.01%, #0cbeff 36.87%, #2ff04c 78.04%, #0e65e8 103.77%);
  background-clip: text;
  -webkit-text-fill-color: transparent;
}
.bg-partner {
  background: url('../assets/img/partner/background.png');
  background-size: cover;
  background-position: center;
}
.bg-trading-tools {
  background: url('../assets/img/bg-trading-tools.webp');
  background-size: cover;
  background-position: center;
}
.max-h-0 {
  max-height: 0;
}
</style>
