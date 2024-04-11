<template>
  <div class="w-full">
    <div class="w-full flex flex-col items-center">
      <h2 data-aos="flip-down" class="text-3xl sm:text-4xl font-semibold text-center">Şiddet Bağımlılığı</h2>
    </div>
    <section class="w-full">
      <BaseSection>
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 mt-4 xl:mt-20 space-y-6 px-4">
          <h2 class="text-4xl font-semibold sm:pr-8 xl:pr-12">Şiddet Bağımlılığı Nedir?</h2>
          <p class="paragraph">
            Şiddet, insanlık için ne yazık ki yaygın bir sorun haline gelmiştir. Fiziksel, duygusal veya sözlü olarak,
            şiddet insanların zarar görmesine ve acı çekmesine neden olur. Ancak şiddetin çözüm getirmediği, aksine daha
            fazla zarara yol açtığı bir gerçektir. <br />
            <br />
            Şiddet, herkesin hakkına saygı göstermek ve barış içinde bir arada yaşamak için temel bir engeldir. Şiddetin
            olduğu bir toplumda, insanlar korku içinde yaşarlar ve özgürce ifade edemezler. İnsanların temel haklarına
            saygı göstermek, barışçıl çözümler bulmak ve empati kurmak, şiddetin yerine geçebilecek en güçlü araçlardır.
            <br />
            <br />
            Şiddetin köklerini kurutmak için toplum olarak çaba göstermeliyiz. Eğitim ve farkındalık artırma
            çalışmalarıyla şiddetin nedenleri üzerinde durarak, insanların şiddete başvurmadan sorunları çözebilecekleri
            beceriler kazanmalarını sağlamalıyız. Ayrıca, şiddetin mağdurlarına destek olmalı, onların haklarını
            korumalı ve toplumda şiddetin kabul edilemez olduğu mesajını güçlendirmeliyiz. <br />
            <br />
            <!-- Şiddetin yerine barışı ve hoşgörüyü tercih etmek, her birimizin sorumluluğudur. Küçük çatışmaları bile şiddet yoluyla çözmek yerine, iletişim, anlayış ve uzlaşma yoluyla çözmeliyiz. Bu, daha sağlıklı, daha mutlu ve daha barışçıl bir toplum için adım atmaktır.
          Sonuç olarak, şiddetin hiçbir kazananı yoktur. Şiddet, sadece acıyı ve zararı artırır. Bu nedenle, hepimiz şiddeti reddetmeli ve barış içinde bir arada yaşamanın yollarını bulmalıyız. Her birimiz, küçük adımlarla bile şiddete karşı durabilir ve daha iyi bir dünya için çalışabiliriz. <br> <br> -->
          </p>
        </div>
        <LandingSiddetImage data-aos="fade-left" class="hidden sm:block py-24" />
      </BaseSection>
    </section>

    <!-- Partners section -->
    <section class="bg-partner relative max-w-full sm:mx-6 my-24 shadow sm:rounded-2xl overflow-hidden">
      <div class="w-full px-6 sm:px-0 py-16 flex flex-col items-center justify-center space-y-4 text-center">
        <h3 data-aos="flip-down" class="text-2xl text-neutral-800 font-semibold">
          Kadına Yönelik Şiddet Konusunda Hizmet Veren Kuruluşlar
        </h3>
        <p data-aos="flip-down" class="paragraph">Kadına Şiddete Hayır!</p>
        <div data-aos="fade-up" class="flex flex-wrap items-center justify-center gap-10">
          <LandingPartnerImage
            v-for="img in ['TC-aile.png', 'mor-cati-vakif.png', 'sosyal-politika.png']"
            :key="img"
            :img="img"
            class="w-56"
          />
        </div>
      </div>
    </section>

    <!-- Credit card section -->
    <section class="w-full my-36">
      <BaseSection data-aos="fade-down">
        <div class="col-span-12 lg:col-span-7">
          <div class="w-full">
            <img :src="require('~/assets/img/SiddetBagimlilik/siddet.jpg')" class="w-[95%] mt-44" alt="" />
          </div>
        </div>
        <div class="col-span-12 lg:col-span-5 space-y-6 px-4 sm:px-6 mt-20">
          <h2 class="text-4xl font-semibold">
            Saldırgan Davranışlar Hangi <span class="text-header-gradient"> Durumlarda </span> Ortaya Çıkar?
          </h2>
          <h2 class="font-bold">Şiddet eğilimindeki artışla birlikte ortaya çıkan saldırgan davranışlar;</h2>
          <p class="paragraph">
            <strong class="text-2xl">!</strong> Genellikle evli kadın ve erkekler arasında görülür ve bu durum aile içi
            şiddetin yaygınlaşmasında büyük rol oynar. <br />
            <br />
            <strong class="text-2xl">!</strong> Bireyin hayatında yakın zamanda meydana gelen büyük değişikler strese ve
            iç gerilime neden olabilir. Bu doğrultuda gelişen içsel baskı hissi, öfke ve dürtüsellik gibi durumlar
            şiddet içeren davranışların ortaya çıkma riskini artırır. <br />
            <br />
            <strong class="text-2xl">!</strong> 16-25 yaş arası erkek bireylerin fazlaca bulunduğu ortamlarda saldırgan
            davranışların ve şiddet olaylarının gelişme riski daha yüksektir. <br />
            <br />
            <strong class="text-2xl">!</strong> Bireyin ruhsal gerilimini artıran olay ve kişiler, tehdit veya baskı
            altında olma durumu, can güvenliğinin tehlikede olması gibi koşullar da şiddet eğilimini artıran önemli
            noktalar arasında yer alır. <br />
            <br />
          </p>
        </div>
      </BaseSection>
    </section>

    <!-- Advanced trading tools section -->
    <section class="bg-trading-tools relative max-w-full sm:mx-4 my-20 py-16 shadow rounded-2xl overflow-hidden">
      <div class="relative max-w-screen-xl px-4 sm:px-2 mx-auto grid grid-cols-12 gap-x-6">
        <LandingTradingToolImage class="sm:hidden" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 space-y-8 sm:space-y-6 px-4 sm:px-6 mt-8">
          <h2 class="text-3xl font-semibold">Şiddetin<span class="text-header-gradient"> Nedenleri </span>Nelerdir?</h2>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Psikososyal Faktörler:</h4>
            <p class="paragraph text-sm xl:text-base">
              Gelişimsel Faktörler: Gelişim döneminde şiddete tanık olan veya maruz kalan çocukların yetişkinlik
              döneminde şiddet uygulayan bireyler olma olasılığı çok daha yüksektir. <br />
              Çevresel Faktörler: Yapılan araştırmalar doğrultusunda kalabalık yaşam ortamlarının şiddet eğilimini
              artırdığı, hava durumunun (örneğin rahatsızlık yaratacak düzeyde artan ortam sıcaklığının) şiddet üzerinde
              etkili olduğu söylenebilir.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Sosyoekonomik Faktörler:</h4>
            <p class="paragraph text-sm xl:text-base">
              Bu alanda yapılmış olan niteliksel çalışmaların sonuçlarında ırk ve ekonomik eşitsizlik gibi faktörlerden
              bağımsız olarak ağır yoksulluk durumunun ve evlilik hayatında yaşanan sorunların şiddet ile ilişkili
              olduğu ortaya konmuştur. <br />
              Aile yapısında bozulmaya neden olan sosyoekonomik faktörler de bu ailelerde yetişen çocukların saldırgan
              davranışlarında artışa neden olur.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Psikiyatrik Faktörler:</h4>
            <p class="paragraph text-sm xl:text-base">
              Psikotik bozukluk olarak tanımlanan hastalıklardan manik tipteki bipolar bozukluk, şizofreni ve paranoid
              bozukluklar saldırgan davranışlarda artışa neden olabilir. Bu psikiyatrik rahatsızlığa sahip olan
              kişilerde hem çevreye hem kendilerine yönelik şiddet uygulama eğilimi gözlenir. <br />
              Psikotik olmayan bozukluklardan ise travma sonrası stres bozukluğu yaşayan kişilerde; borderline, paranoid
              ve antisosyal kişilik bozukluklarında şiddet eğiliminde artış meydana gelir ve bu kişilerde saldırgan
              içerikli davranışlarla son derece sık karşılaşılır.
            </p>
          </div>
        </div>
        <LandingSiddetDongüImage data-aos="fade-left" class="hidden sm:block" />
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
