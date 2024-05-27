<template>
  <div class="w-full">
    <div class="w-full flex flex-col items-center">
      <h2 data-aos="flip-down" class="text-3xl sm:text-4xl font-semibold text-center">Alkol Bağımlılığı</h2>
    </div>
    <section class="w-full">
      <div id="1"></div>
      <BaseSection>
        <LandingBuyTradeImage class="sm:hidden mb-8" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 mt-4 xl:mt-20 space-y-6 px-4">
          <h2 class="text-4xl font-semibold sm:pr-8 xl:pr-12">Alkol Bağımlılığı Nedir?</h2>
          <p class="paragraph">
            Dünya Sağlık Örgütüne göre, alkol bağımlılığı, alkolün yinelenen bir biçimde veya sürekli kullanımından
            kaynaklanan kullanım bozukluğu olarak tanımlanmaktadır. Amerikan Psikiyatri Birliğinin belirlediği DSM- 5
            tanı ölçütlerine göre alkol bağımlılığı; on iki aylık bir süre içinde, aşağıdakilerden en az ikisi ile
            kendini gösteren, günlük hayatında belirgin bir sıkıntıya ya da işlevsellikte düşmeye yol açan, sorunlu bir
            alkol kullanım örüntüsüdür. <br />
            <strong class="text-2xl">!</strong> Alkol bağımlılığının temel belirtileri arasında şunlar yer almaktadır:
          </p>
          <div id="nav"></div>
          <p class="font-bold">Kullanımı kontrol etme kabiliyetinin bozulması</p>
          <p class="font-bold">
            Alkol kullanmayı bırakmak ya da denetim altında tutmak için sürekli bir istek ya da sonuç vermeyen çabalar
            olması
          </p>
          <p class="font-bold">Alkol kullanımına diğer etkinliklere göre daha fazla öncelik verilmesi</p>
          <p class="font-bold">
            İşte, okulda ya da evdeki konumunun gereği olan başlıca yükümlülüklerini yerine getirememe
          </p>
          <p class="font-bold">Alkolün gitgide eski etkisini kaybetmesi (tolerans geliştirilmesi)</p>
          <!-- <p class="font-bold">Zararlarla veya olumsuz sonuçlarla karşılaşılmasına rağmen kullanıma devam edilmesiyle kendini gösteren güçlü bir alkol kullanma isteği</p>
          <p class="font-bold">Çoğu kez, istendiğinden daha fazla ya da daha uzun süreli olarak alkol alınması</p>
          <p class="font-bold">Alkolün etkilerinin neden olduğu ya da alevlendirdiği, sürekli ya da yineleyici toplumsal ya da kişiler arası sorunlar olmasına karşın alkol kullanımını sürdürme</p>
          <p class="font-bold">Yineleyici bir biçimde, tehlikeli olabilecek durumlarda alkol kullanma</p>
          <p class="font-bold">Alkol kullanımının kesilmesi veya azaltılması sonrasında yoksunluk belirtilerinin görülmesi.</p> -->
        </div>
        <LandingAlkolResimImage data-aos="fade-left" class="hidden sm:block" />
      </BaseSection>
    </section>

    <section
      class="max-w-screen-xl mx-2 mt-52 sm:mx-auto px-4 sm:px-6 lg:px-0 py-6 pb-20 sm:py-8 rounded-[2.25rem] sm:rounded-xl bg-white shadow-lg sm:shadow-md transform lg:-translate-y-12"
    >
      <ul :class="[open ? 'flex' : 'hidden lg:flex']" class="w-full gap-8 h-auto flex justify-center">
        <a href="#1">Alkol Bağımlılığı</a>
        <a href="#2">İlaçlar</a>
        <a href="#3">Alkol Yoksunluğu</a>
        <a href="#4">Sağlık Sorunları</a>
        <a href="#5">Ergenler Üzerindeki Etkileri</a>
      </ul>
    </section>

    <!-- Partners section -->
    <div id="2"></div>
    <section class="bg-partner relative max-w-full sm:mx-6 mt-36 shadow sm:rounded-2xl overflow-hidden">
      <div class="w-full px-6 sm:px-0 py-16 flex flex-col items-center justify-center space-y-4 text-center">
        <h3 data-aos="flip-down" class="text-2xl text-neutral-800 font-semibold mb-10">
          Alkolü bırakmak için hangi ilaç kullanılır?
        </h3>
        <div data-aos="fade-up" class="flex flex-wrap items-center justify-center gap-28 font-bold">
          <p>Disülfiram</p>
          <p>Naltrexone</p>
          <p>Akamprosat</p>
          <p>Antidepresan ilaçlar</p>
          <p>Nargilelik tütün mamulü</p>
        </div>
      </div>
    </section>

    <!-- Credit card section -->
    <div id="3"></div>
    <section class="w-full">
      <BaseSection data-aos="fade-down">
        <div class="col-span-12 lg:col-span-7">
          <div class="w-full">
            <img :src="require('~/assets/img/AlkolBagimlilik/1866385-0MeqkT.jpg')" class="w-[90%] py-64" alt="" />
          </div>
        </div>
        <div class="col-span-12 lg:col-span-5 space-y-6 px-4 sm:px-6 mt-20">
          <h2 class="text-4xl font-semibold">Alkol <span class="text-header-gradient">Yoksunluğu</span> Nedir?</h2>
          <p class="paragraph">
            Alkol kullanım bozukluğu ile ilgili sıkça karşılaşılan durumlardan biri, alkol yoksunluğudur. Uzun süre
            yüksek miktarda alkol kullanımının bırakılmasından ya da azaltılmasından sonra kandaki alkol düzeyinin
            azalmaya başlamasından 6-8 saat sonra, genellikle ilk 24 saat içinde ortaya çıkmaktadır. İki hafta kadar
            aşağıdaki belirtilerin hepsi veya en az ikisinin gelişmesine alkol yoksunluğu denir. Kısaca yoksunluk; alkol
            kullanılmadığı zaman dilimlerinde ruhsal ve fiziksel sorunların ortaya çıkmasıdır. Belirtiler hafif şekilde
            seyredebileceği gibi ölüm riski taşıyan tablolara da dönüşebilmektedir. <br />
            <br />
            Alkol yoksunluk belirtilerinin şiddet düzeyinin değerlendirilmesi ve bireyin risk taşıyan olası zararlardan
            korunması için bırakma sürecinde bir uzman desteği alması önem arz etmektedir. <br />
            <br />
            Bireyde alkol yoksunluğu sürecinde aşağıdaki belirtiler görülmektedir:
          </p>
          <ul class="space-y-4 sm:space-y-2">
            <LandingListItem title="Sağlık Isı artışı (hipertermi)" />
            <LandingListItem title="Finansal Kalp ritminde değişiklikler (aritmi)" />
            <LandingListItem title="Baş ağrısı" />
            <LandingListItem title="Uykusuzluk" />
            <LandingListItem title="Kaygı, huzursuzluk vb" />
            <LandingListItem title="Bunaltı (iç sıkıntısı)" />
            <LandingListItem title="Sara nöbetleri" />
            <LandingListItem title="Tansiyon yüksekliği (hipertansiyon)" />
            <LandingListItem title="Dikkat bozukluğu halüsinasyonlar" />
          </ul>
        </div>
      </BaseSection>
    </section>

    <!-- Advanced trading tools section -->
    <section class="bg-trading-tools relative max-w-full sm:mx-4 my-20 py-16 shadow rounded-2xl overflow-hidden">
      <div id="4"></div>
      <div class="relative max-w-screen-xl px-4 sm:px-2 mx-auto grid grid-cols-12 gap-x-6">
        <LandingBuyTradeImage class="sm:hidden" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 space-y-8 sm:space-y-6 px-4 sm:px-6 mt-8">
          <h2 class="text-3xl font-semibold">
            Alkol Bağımlılığının Yol Açtığı<span class="text-header-gradient"> Sağlık </span> Sorunları Nelerdir?
          </h2>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Alkolün Riskli Kullanımı</h4>
            <p class="paragraph text-sm xl:text-base">
              Dünya nüfusunun sağlığı konusunda önde gelen risk faktörlerinden biridir ve birçok hastalığa yol
              açmaktadır, toplumlar üzerinde sosyal ve ekonomik açıdan pek çok yük oluşturmaktadır. Alkol bağımlılığı
              sıklıkla farklı psikolojik veya bedensel sorunlarla birlikte görülür. Alkol bağımlılığı tanısı alan
              kişilerde farklı maddelere bağımlılık riski, duygu durum bozuklukları, depresyon, kaygı sorunları
              şizofreni, kişilik bozuklukları gibi ruhsal problemler görülürken aynı zamanda bedensel olarak da
              karaciğerde büyüme, yağlanma, sarılık, kanser ve siroz, yüksek tansiyon, kalpte büyüme ve ani kriz, damar
              tıkanıkları görülmektedir.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Beyin üzerinde Etkisi</h4>
            <p class="paragraph text-sm xl:text-base">
              beyin işlevlerinde bozulmalara neden olmaktadır ve buna bağlı olarak dengede bozulma, beceri isteyen
              uğraşları gerçekleştirmede zorlanma, alkole bağlı bunama, hafızada bozulma gibi süreçlerde çok sık
              görülmektedir.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Hormonsal Azalma</h4>
            <p class="paragraph text-sm xl:text-base">
              Alkol testosteron (erkeklik) hormonunu azaltırken, östrojen (kadınlık) hormonunu yükseltmektedir. Vücutta
              vitamin dengesini bozar. Susuzluğa yol açar. Yağ depolanmasını arttırdığı için kilo problemine ve ayrıca
              kas erimesi ve kaslarda zayıflığa neden olur.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Sinir Sistemi Üzerinde Etkileri</h4>
            <p class="paragraph text-sm xl:text-base">
              Riskli alkol kullanımı sinir sistemine zarar vermektedir, ellerde titreme ve bacaklarda karıncalanma,
              uyuşma hissine neden olabilir.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Bebek Sağlığı</h4>
            <p class="paragraph text-sm xl:text-base">
              Hamilelikte alkol kullanımı bebekte büyüme ve gelişme sürecinde geriliğe neden olur.
            </p>
          </div>
        </div>
        <LandingAlkolSaglikImage data-aos="fade-left" class="hidden sm:block" width="200" height="200" />
      </div>
    </section>

    <section class="w-full">
      <div id="5"></div>
      <BaseSection>
        <LandingBuyTradeImage class="sm:hidden mb-8" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 mt-4 xl:mt-20 space-y-6 px-4 mb-10">
          <h2 class="text-4xl font-semibold sm:pr-8 xl:pr-12">
            Alkol Kullanımının Çocuk ve Ergenler Üzerindeki Etkileri Nelerdir?
          </h2>
          <p class="paragraph">
            Bireylerin gelişim süreçlerinde belirli aşamalar mevcuttur. Sosyal, fiziksel ve bilişsel gelişim
            süreçlerinde belirli görevler vardır ve birey bu görevleri tamamlayarak bir sonraki aşamaya geçer. Çocuk ve
            ergenlik döneminde de benzeri süreçler söz konusudur. Çocukluk ve ergenlik dönemi keşifler, denemeler ve
            davranışsal değişimler dönemidir. Özellikle ergenlik, özerkliğin arttığı, akran etkisinin önem kazandığı ve
            ebeveynlerin doğrudan etkilerinin azaldığı bir yaşam evresidir. Ergen için bireysel kimliğini oluşturma
            çabası gündemdedir. Alkole başlama açısından da kritik bir dönemdir. Ergenlik döneminde düşünme, planlama,
            karar alma becerilerinden ve sosyal/duygusal gelişimden sorumlu beyin devrelerinin hızlı bir şekilde
            değişmeye devam ettiği görülmektedir. Alkol kullanımı ile beraber çocuk ve gençlerde, bu gelişimsel
            değişimleri olumsuz etkilemektedir.
          </p>
          <div class="space-y-2">
            <h2 class="text-red-600">Biliyor Musunuz?</h2>
            <p class="font-bold">
              Dünya Sağlık Örgütünün 2018 yılı Küresel Alkol ve Sağlık Durum Raporu’na göre 2016 yılında;
            </p>
            <p class="paragraph text-sm xl:text-base">
              <span>
                <strong>1-</strong> Yaklaşık 3 milyon ölümün, alkolün zararlı kullanımından kaynaklandığı ve bu ölüm
                oranının, tüm ölümlerin yüzde 5.3'ünü temsil ettiği tahmin edilmektedir.</span
              ><br />
              <span>
                <strong>3-</strong> Dünya genelindeki 69 yaş ve altındakiler arasındaki erken ölümlerin yüzde 7.2’sinin
                alkole bağlı olarak ortaya çıktığı öngörülmektedir. 20-39 yaş arasındaki ölümlerin yüzde 13.5’inden
                alkolün sorumlu olduğu düşünülmektedir.</span
              ><br />
              <span><strong>4-</strong> Alkolün zararlı kullanımı, 200'den fazla sağlık sorunuyla ilişkilidir.</span
              ><br />
              <span
                ><strong>5-</strong> Sadece yüksek düzeylerde alkol alımı değil düşük ve orta düzeyde alkol alımı da
                kalp hastalıkları ve felç, karaciğer sirozu ve bazı kanser türlerinin gelişimi açısından önemli bir risk
                faktörüdür. </span
              ><br />
            </p>
          </div>
        </div>
        <LandingAlkolEbeveynImage data-aos="fade-left" class="hidden sm:block" />
      </BaseSection>
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
