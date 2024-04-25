<template>
  <div class="w-full">
    <!-- Hero section -->
    <section id="hero" class="w-full pb-24">
      <BaseSection>
        <div class="col-span-12 lg:col-span-6 mt-12 xl:mt-10 space-y-4 sm:space-y-6 px-6 text-center sm:text-left">
          <p></p>
          <h1
            data-aos="fade-right"
            data-aos-once="true"
            class="text-[2.5rem] sm:text-5xl xl:text-6xl font-bold leading-tight capitalize sm:pr-8 xl:pr-10"
          >
            Yeşili Koru <span class="text-header-gradient">Sev,Önem ver <br /></span>Doğayı Koru!
          </h1>
          <p data-aos="fade-down" data-aos-once="true" data-aos-delay="300" class="paragraph hidden sm:block">
            Her Birey Değerlidir, Her Hayat Önemlidir!
          </p>
          <div
            data-aos="fade-up"
            data-aos-once="true"
            data-aos-delay="700"
            class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4 mt-2"
          >
            <BaseButton
              class="max-w-full px-8 py-4 bg-gradient-to-r from-[#468ef9] to-[#0c66ee] border border-[#0c66ee] text-white"
            >
              Bizlere Ulaşmak İçin
            </BaseButton>
            <div id="nav"></div>
          </div>
        </div>
        <div class="hidden sm:block col-span-12 lg:col-span-6">
          <div class="w-full">
            <img
              data-aos="fade-up"
              width="596"
              height="579"
              data-aos-once="true"
              :src="require('~/assets/img/doga-home.webp')"
              class="-mt-5"
              alt=""
            />
          </div>
        </div>
        <img
          data-aos="fade-up"
          data-aos-delay="300"
          :src="require('~/assets/img/pattern/ellipse-1.png')"
          class="hidden sm:block absolute bottom-12 xl:bottom-16 left-4 xl:left-0 w-6"
        />
        <img
          data-aos="fade-up"
          data-aos-delay="300"
          :src="require('~/assets/img/pattern/ellipse-2.png')"
          class="hidden sm:block absolute top-4 sm:top-10 right-64 sm:right-96 xl:right-[32rem] w-6"
        />
        <img
          data-aos="fade-up"
          data-aos-delay="300"
          :src="require('~/assets/img/pattern/ellipse-3.png')"
          class="hidden sm:block absolute bottom-56 right-24 w-6"
        />
        <img
          data-aos="fade-up"
          data-aos-delay="300"
          :src="require('~/assets/img/pattern/star.png')"
          class="hidden sm:block absolute top-20 sm:top-28 right-16 lg:right-0 lg:left-[30rem] w-8"
        />
      </BaseSection>
    </section>

    <!-- Crypto statistic section -->
    <section
      class="max-w-screen-xl mx-2 sm:mx-auto px-4 sm:px-6 lg:px-0 py-6 pb-20 sm:py-8 rounded-[2.25rem] sm:rounded-xl bg-white shadow-lg sm:shadow-md transform lg:-translate-y-12"
    >
      <ul :class="[open ? 'flex' : 'hidden lg:flex']" class="w-full gap-8 h-auto flex justify-center">
        <a href="#1">1</a>
        <a href="#2">2</a>
        <a href="#3">3</a>
        <a href="#4">4</a>
        <a href="#5">5</a>
        <a href="#6">6</a>
        <a href="#7">7</a>
        <a href="#8">8</a>
      </ul>
    </section>

    <!-- Buy and trade section -->
    <div id="1"></div>
    <section class="w-full my-24">
      <BaseSection>
        <LandingBuyTradeImage class="sm:hidden mb-8" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 mt-4 xl:mt-20 space-y-6 px-4">
          <h2 class="text-4xl font-semibold sm:pr-8 xl:pr-12">
            Bağımlılıklar İle ilgili <br class="hidden sm:block" />
            Amaçlarımız neler?
          </h2>
          <p class="paragraph">
            amaçlar çeşitli yöntemlerle toplumda farkındalık yaratmayı, önleyici tedbirler geliştirmeyi ve bağımlılıkla
            mücadeleyi desteklemeyi hedefleyebilir. İşte bu Amaçlar Şunlardır.
          </p>
          <p class="font-bold">Farkındalık Oluşturma</p>
          <p class="font-bold">Önleyici Tedbirler</p>
          <p class="font-bold">Mevcut Bağımlılıkla Mücadele Yöntemlerini Desteklemek</p>
          <p class="font-bold">Toplumsal Katılımı Artırmak</p>
          <p class="font-bold">Etkin Değerlendirme ve İzleme</p>
        </div>
        <LandingNoToDrugsImage data-aos="fade-left" class="hidden sm:block" />
      </BaseSection>
      <div id="2"></div>
    </section>

    <!-- Partners section -->

    <section class="bg-partner relative max-w-full sm:mx-6 my-24 shadow sm:rounded-2xl overflow-hidden">
      <div class="w-full px-6 sm:px-0 py-16 flex flex-col items-center justify-center space-y-4 text-center">
        <h3 data-aos="flip-down" class="text-2xl text-neutral-800 font-semibold">
          Sosyal Sorumluluk İle ilgilenen kuruluşlar
        </h3>
        <p data-aos="flip-down" class="paragraph">Kültürel Mirasımızı Koruyalım, Geleceğe Taşıyalım!</p>
        <div data-aos="fade-up" class="flex flex-wrap items-center justify-center">
          <LandingPartnerImage
            v-for="img in ['Greenpeace_logo.png', 'TEGV.png', 'Amnesty-International-Logo.png', 'Logo_of_UNICEF.png']"
            :key="img"
            :img="img"
          />
        </div>
      </div>
    </section>

    <!-- Credit card section -->
    <div id="3"></div>
    <section class="w-full my-36">
      <BaseSection data-aos="fade-down">
        <div class="col-span-12 lg:col-span-7">
          <div class="w-full">
            <img :src="require('~/assets/img/pngtree-drug-prohibition-icon.png')" class="w-[95%]" alt="" />
          </div>
        </div>
        <div class="col-span-12 lg:col-span-5 space-y-6 px-4 sm:px-6 mt-20">
          <h2 class="text-4xl font-semibold">
            Kötü Alışkanlıklar <span class="text-header-gradient">Hayatımızı</span> Nasıl Etkiler
          </h2>
          <p class="paragraph">
            Kötü alışkanlıkların hayatımızı olumsuz yönde etkilemesi birçok şekilde olabilir. İşte bunlardan bazıları
          </p>
          <ul class="space-y-4 sm:space-y-2">
            <LandingListItem title="Sağlık Sorunları" />
            <LandingListItem title="Finansal Zorluklar" />
            <LandingListItem title="Kişisel İlişkilerde Sorunlar" />
            <LandingListItem title="Duygusal ve Psikolojik Sorunlar" />
          </ul>
        </div>
      </BaseSection>
    </section>

    <!-- Advanced trading tools section -->
    <div id="4"></div>
    <section class="bg-trading-tools relative max-w-full sm:mx-4 my-20 py-16 shadow rounded-2xl overflow-hidden">
      <div class="relative max-w-screen-xl px-4 sm:px-2 mx-auto grid grid-cols-12 gap-x-6">
        <LandingTradingToolImage class="sm:hidden" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 space-y-8 sm:space-y-6 px-4 sm:px-6 mt-8">
          <h2 class="text-3xl font-semibold">
            Kötü alışkanlıklardan<span class="text-header-gradient"> Uzak </span>durmak
          </h2>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Hedef Belirleme ve Motivasyon</h4>
            <p class="paragraph text-sm xl:text-base">
              İlk adım olarak, kötü alışkanlıklardan kurtulma isteğinizi netleştirin ve bu konuda kendinize bir hedef
              belirleyin. Bu hedefler sizin için anlamlı olmalı ve sizi motive etmelidir.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Nedenleri Anlama</h4>
            <p class="paragraph text-sm xl:text-base">
              Kötü alışkanlıkların arkasındaki nedenleri anlamak önemlidir. Bu nedenler fiziksel, duygusal veya çevresel
              olabilir. Kendinize neden kötü alışkanlıklara başladığınızı sorun ve bu nedenlerle başa çıkma yolları
              arayın.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Destek Arama</h4>
            <p class="paragraph text-sm xl:text-base">
              Kötü alışkanlıklardan kurtulmak için destek almak önemlidir. Aile üyeleri, arkadaşlar, terapistler veya
              destek grupları gibi kaynaklardan yardım isteyebilirsiniz. Bu destek aynı zamanda size motivasyon ve güç
              verebilir.
            </p>
          </div>
        </div>
        <LandingTradingToolImage data-aos="fade-left" class="hidden sm:block" />
      </div>
    </section>

    <!-- Industry-leading security section -->
    <div id="5"></div>
    <section class="w-full my-24">
      <div class="relative max-w-screen-xl px-8 mx-auto grid grid-cols-12 gap-x-6">
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6">
          <div class="w-full">
            <img
              :src="require('~/assets/img/bağimlilik-696x343-Photoroom.png-Photoroom.png')"
              class="w-full mt-20"
              alt=""
            />
          </div>
        </div>
        <div data-aos="fade-left" class="col-span-12 lg:col-span-5 space-y-8 sm:space-y-6 mt-8 xl:px-8">
          <h2 class="text-4xl font-semibold">
            Türkiye'de bağımlılıklarla ilgilenen ve bağımlıları destekleyen Kuruluşlar
          </h2>
          <ul class="space-y-8 sm:space-y-4">
            <LandingListItemOne title="Yeşilay">
              <p class="text-sm text-gray-700 leading-relaxed">
                Türkiye Yeşilay Cemiyeti, alkol, sigara, madde bağımlılığı gibi zararlı alışkanlıklarla mücadele etmeyi
                ve toplumu bu konuda bilinçlendirmeyi amaçlar. Yeşilay, bağımlıları desteklemek ve bağımlılıkla
                mücadelede toplumsal farkındalığı artırmak için çeşitli etkinlikler ve projeler düzenler.
              </p>
            </LandingListItemOne>
            <LandingListItemOne title="Bir Umut Ol Sun Derneği">
              <p class="text-sm text-gray-700 leading-relaxed">
                Bağımlıları ve ailelerini desteklemek amacıyla kurulan bu dernek, madde bağımlılığıyla mücadelede
                danışmanlık ve rehabilitasyon hizmetleri sunar. Ayrıca, bağımlılıkla ilgili farkındalık oluşturmak ve
                önleme çalışmaları yapmak da derneğin faaliyetleri arasındadır.
              </p>
            </LandingListItemOne>
            <LandingListItemOne title="Huzur Mahallesi">
              <p class="text-sm text-gray-700 leading-relaxed">
                Bağımlılıkla mücadele eden ve bağımlıları destekleyen bir başka Türk kuruluşudur. Huzur Mahallesi, madde
                bağımlılığı ve alkol bağımlılığı gibi konularda danışmanlık, rehabilitasyon ve sosyal destek hizmetleri
                sunar.
              </p>
            </LandingListItemOne>
          </ul>
        </div>
      </div>
    </section>

    <!-- Getting started section -->
    <div id="6"></div>
    <section class="bg-trading-tools relative max-w-full sm:mx-4 xl:mx-10 my-24 shadow sm:rounded-2xl overflow-hidden">
      <div class="w-full py-16 flex flex-col items-center">
        <h2 data-aos="flip-down" class="text-3xl sm:text-4xl font-semibold text-center">
          bağımlı bir insan için başlangıç adımları
        </h2>
        <div
          data-aos="fade-up"
          class="relative w-full flex flex-col lg:flex-row items-center justify-between space-y-12 lg:space-y-0 px-4 xl:px-10 mt-16 sm:mt-8"
        >
          <LandingStep v-for="step in steps" :key="step.title" :step="step" />
          <img
            :src="require('~/assets/img/getting-started/arrow.png')"
            class="hidden lg:inline-block absolute top-32 left-64 xl:left-[22rem] w-24 xl:w-[9.5rem]"
            alt=""
          />
          <img
            :src="require('~/assets/img/getting-started/arrow.png')"
            class="hidden lg:inline-block absolute top-32 right-64 xl:right-[22rem] w-24 xl:w-[9.5rem]"
            alt=""
          />
        </div>
      </div>
      <div id="7"></div>
    </section>

    <!-- FAQ section -->

    <section class="w-full my-24">
      <div class="relative max-w-screen-xl px-4 sm:px-2 mx-auto grid grid-cols-12 gap-x-6">
        <LandingTradingToolImage class="sm:hidden" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 space-y-8 sm:space-y-6 px-4 sm:px-6 mt-8">
          <h2 class="text-3xl font-semibold">Şiddet Bağımlılığı nedir</h2>
          <div class="space-y-2">
            <p class="paragraph text-sm xl:text-base">
              Şiddet, insanlık için ne yazık ki yaygın bir sorun haline gelmiştir. Fiziksel, duygusal veya sözlü olarak,
              şiddet insanların zarar görmesine ve acı çekmesine neden olur. Ancak şiddetin çözüm getirmediği, aksine
              daha fazla zarara yol açtığı bir gerçektir.
            </p>
          </div>
          <div class="space-y-2">
            <p class="paragraph text-sm xl:text-base">
              Şiddet, herkesin hakkına saygı göstermek ve barış içinde bir arada yaşamak için temel bir engeldir.
              Şiddetin olduğu bir toplumda, insanlar korku içinde yaşarlar ve özgürce ifade edemezler. İnsanların temel
              haklarına saygı göstermek, barışçıl çözümler bulmak ve empati kurmak, şiddetin yerine geçebilecek en güçlü
              araçlardır.
            </p>
          </div>
          <div class="space-y-2">
            <p class="paragraph text-sm xl:text-base">
              Şiddetin köklerini kurutmak için toplum olarak çaba göstermeliyiz. Eğitim ve farkındalık artırma
              çalışmalarıyla şiddetin nedenleri üzerinde durarak, insanların şiddete başvurmadan sorunları
              çözebilecekleri beceriler kazanmalarını sağlamalıyız. Ayrıca, şiddetin mağdurlarına destek olmalı, onların
              haklarını korumalı ve toplumda şiddetin kabul edilemez olduğu mesajını güçlendirmeliyiz
            </p>
          </div>
        </div>
        <LandingSiddetImage data-aos="fade-left" class="hidden sm:block" />
      </div>
    </section>

    <div id="8"></div>
    <section class="bg-trading-tools relative max-w-full sm:mx-4 my-20 py-16 shadow rounded-2xl overflow-hidden">
      <div class="relative max-w-screen-xl px-4 sm:px-2 mx-auto grid grid-cols-12 gap-x-6">
        <LandingAlkolImage data-aos="fade-left" class="hidden sm:block" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 space-y-8 sm:space-y-6 px-4 sm:px-6 mt-8">
          <h2 class="text-3xl font-semibold">Alkol Bağımlılığı Nedir?</h2>
          <div class="space-y-2">
            <p class="paragraph text-sm xl:text-base">
              Dünya Sağlık Örgütüne göre, alkol bağımlılığı, alkolün yinelenen bir biçimde veya sürekli kullanımından
              kaynaklanan kullanım bozukluğu olarak tanımlanmaktadır. Amerikan Psikiyatri Birliğinin belirlediği DSM- 5
              tanı ölçütlerine göre alkol bağımlılığı; on iki aylık bir süre içinde, aşağıdakilerden en az ikisi ile
              kendini gösteren, günlük hayatında belirgin bir sıkıntıya ya da işlevsellikte düşmeye yol açan, sorunlu
              bir alkol kullanım örüntüsüdür.
            </p>
          </div>
          <div class="space-y-2">
            <h1 class="text-red-600">Alkol bağımlılığının temel belirtileri arasında şunlar yer almaktadır:</h1>
            <p class="paragraph text-sm xl:text-base">
              <span> 1- Kullanımı kontrol etme kabiliyetinin bozulması</span><br />
              <span>
                2- Alkol kullanmayı bırakmak ya da denetim altında tutmak için sürekli bir istek ya da sonuç vermeyen
                çabalar olmaz</span
              ><br />
              <span> 3- Alkol kullanımına diğer etkinliklere göre daha fazla öncelik verilmesi</span><br />
              <span>4- İşte, okulda ya da evdeki konumunun gereği olan başlıca yükümlülüklerini yerine getirememe</span
              ><br />
              <span>
                5- Zararlarla veya olumsuz sonuçlarla karşılaşılmasına rağmen kullanıma devam edilmesiyle kendini
                gösteren güçlü bir alkol kullanma isteği</span
              ><br />
            </p>
          </div>
          <div class="space-y-2">
            <h1 class="text-red-600">Bırakmak Mümkün!</h1>
            <p class="paragraph text-sm xl:text-base">
              Alkol iyileşebilen bir beyin hastalığıdır. Alkolü bırakmak zor olabilir, ancak bağımlılık üzerine uzman
              bir ekipten destek alarak bırakma sürecini daha detaylı öğrenebilir ve kolaylaştırabilirsiniz. Alkolü
              bıraktığınızda yaşadığınız ve gözlemlediğiniz iyileşmeler, bırakma sürecine bağlı kalmanızdaki
              motivasyonunuzu artıracaktır. Bırakma yöntemleri ve bırakma süreci hakkında bilgi edinmek için YEDAM ile
              iletişime geçebilirsiniz. 115 numaralı YEDAM Danışma Hattı’mız üzerinden, bir arkadaşınıza, aile
              üyelerinize veya bir tanıdığınız için alkolü bırakma konusunda uzman psikologlarımız ve sosyal hizmet
              uzmanlarımızdan ücretsiz destek alabilirsiniz
            </p>
          </div>
        </div>
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
  name: 'IndexPage',
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
