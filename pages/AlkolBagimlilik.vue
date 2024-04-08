<template>
  <div class="w-full">
    <div class="w-full py-16 flex flex-col items-center">
      <h2 data-aos="flip-down" class="text-3xl sm:text-4xl font-semibold text-center">Alkol Bağımlılığı</h2>
    </div>

    <section class="w-full my-12">
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
        <LandingBuyTradeImage data-aos="fade-left" class="hidden sm:block" />
      </BaseSection>
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

    <div class="w-full my-10 flex justify-center">
      <a
        v-smooth-scroll
        data-aos="flip-down"
        data-aos-delay="150"
        href="#navbar"
        class="px-6 py-3 flex items-center space-x-2 bg-[#FAFAFA] hover:bg-gray-100 hover:shadow-md border border-[#DDDDDD] rounded-md text-gray-700"
      >
        <span>Back to top</span>
        <ArrowUpIcon :size="20" />
      </a>
    </div>
  </div>
</template>

<script>
import aosMixin from '@/mixins/aos'
export default {
  name: 'AlkolBagimlilik',
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
