<template>
  <div class="w-full">
    <div class="w-full flex flex-col items-center">
      <h2 data-aos="flip-down" class="text-3xl sm:text-4xl font-semibold text-center">Teknoloji Bağımlılığı</h2>
    </div>
    <section class="w-full">
      <div id="1"></div>
      <BaseSection>
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 mt-4 xl:mt-20 space-y-6 px-4">
          <h2 class="text-4xl font-semibold sm:pr-8 xl:pr-12">Teknoloji Bağımlılığı Nedir?</h2>
          <p class="paragraph">
            Teknoloji bağımlılığı, akıllı telefonun ortaya çıkışıyla kişinin sosyal medyada, oyunlarda, online alışveris sitelerinde ve uygulamalarda bilinçsiz,
            kontrolsüz ve takıntılı bir şekilde zaman harcamasıdır.
             Bu zaman harcama kişiyi aynı zamanda sosyal hayattan da soyutlar. <br />
            <br />
            Teknoloji bağımlılığı ile mücadele eden insan sayısında özellikle internet ve akıllı telefonların ortaya çıkışı ile birlikte ciddi bir artış yaşanmıştır.
             Bireyler çevrimiçi iken beyinlerinde gelişen nörolojik değişiklikler göz önüne alındığında teknoloji bağımlılığı davranışsal bağımlılıklar başlığı altında incelenir.
            <br />
            <div id="nav"></div>
            <br />
            Teknoloji bağımlılığı aynı zamanda dijital bağımlılık, internet bağımlılığı ya da internet kullanım bozukluğu olarak da adlandırılır.
             Teknoloji bağımlılığının, çocukların gelişimine zarar vermemesi adına profesyonel bir destek alınarak gelişim sürecinde dengeli bir role sahip olmalıdır. <br />
            <br />
          </p>
        </div>
        <LandingTeknolojResimImage data-aos="fade-left" class="hidden sm:block py-20 mx-3" />
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
          <p>Hipoterapi</p>
          <p>Sanat terapisi</p>
          <p>Rekreasyon tedavisi</p>
          <p>Gerçeklik terapisi</p>
          <p>Bilişsel davranışçı terapi</p>
          <p>Aile Terapisi</p>
        </div>
      </div>
    </section>

    <!-- Credit card section -->
    <section class="w-full">
      <div id="3"></div>
      <BaseSection data-aos="fade-down">
        <div class="col-span-12 lg:col-span-7">
          <div class="w-full">
            <img :src="require('~/assets/img/TeknolojiBagimlilik/techn-2.jpeg')" class="w-[90%] py-10" alt="" />
          </div>
        </div>
        <div class="col-span-12 lg:col-span-5 space-y-6 px-4 sm:px-6 mt-20">
          <h2 class="text-4xl font-semibold">
            Teknoloji Bağımlılığı <span class="text-header-gradient"> Belirtileri </span> Nedir
          </h2>
          <h2 class="font-bold">Zamanın geçtiğini fark etmemek, agresif davranışlar, sosyal hayattan soyutlanmak gibi durumlar teknoloji bağımlılığı belirtileri arasında gösterilir bunlar;</h2>
          <ul class="space-y-4 sm:space-y-2">
            <LandingListItem title="Çevrimiçi olunduğunda zamanın nasıl geçtiğinin farkında olamamak" />
            <LandingListItem title="Çevrimiçi olunmadığında sinirli ya da öfkeli olmak" />
            <LandingListItem title="İş ya da okul vb. sorumluklar için ayrılması gereken zamanı internette tüketmek" />
            <LandingListItem title="Çevrimiçi iken coşku hissetmek" />
            <LandingListItem title="Sosyal hayattan soyutlanmak" />
            <LandingListItem title="Gün içinde teknolojik cihazları zorunlu olarak kontrol etmeyi istemek" />
            <LandingListItem title="Çevrimiçi olunan süre konusunda yalan söylemek" />
            <LandingListItem title="Çevrimiçi faaliyetlere çok fazla para harcamak" />
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
          <h2 class="text-3xl font-semibold">Teknoloji Bağımlılığının <span class="text-header-gradient"> Zararları </span>Nelerdir?</h2>
          <ul class="space-y-4 sm:space-y-2">
            <LandingListItem title="Çevrimiçi olunduğunda zamanın nasıl geçtiğinin farkında olamamak" />
            <LandingListItem title="Çevrimiçi olunmadığında sinirli ya da öfkeli olmak" />
            <LandingListItem title="İş ya da okul vb. sorumluklar için ayrılması gereken zamanı internette tüketmek" />
            <LandingListItem title="Çevrimiçi iken coşku hissetmek" />
            <LandingListItem title="Sosyal hayattan soyutlanmak" />
            <LandingListItem title="Gün içinde teknolojik cihazları zorunlu olarak kontrol etmeyi istemek" />
            <LandingListItem title="Çevrimiçi olunan süre konusunda yalan söylemek" />
            <LandingListItem title="Çevrimiçi faaliyetlere çok fazla para harcamak" />
          </ul>
        </div>
        <LandingTeknolojiResimAlt data-aos="fade-left" class="hidden sm:block mt-8" />
      </div>
    </section>

    <!-- Industry-leading security section -->

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
