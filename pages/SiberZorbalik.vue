<template>
  <div class="w-full">
    <div class="w-full flex flex-col items-center">
      <h2 data-aos="flip-down" class="text-3xl sm:text-4xl font-semibold text-center">Siber Zorbalık</h2>
    </div>
    <section class="w-full">
      <div id="1"></div>
      <BaseSection>
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 mt-4 xl:mt-20 space-y-6 px-4">
          <h2 class="text-4xl font-semibold sm:pr-8 xl:pr-12">Siber Zorbalık Nedir?</h2>
          <p class="paragraph">
            Siber zorbalık, dijital teknolojiler kullanılarak gerçekleştirilen zorbalıktır.
            Bu tür zorbalıklar sosyal medyada, mesajlaşma platformlarında, oyun platformlarında ve cep telefonlarında görülebilir.
            Hedef seçilen kişileri korkutmaya, kızdırmaya ya da utandırmaya yönelik olarak tekrarlanan bir davranıştır.
            Buna örnek olarak şu eylemler gösterilebilir: <br />
            <br />
            <ul class="space-y-4 sm:space-y-2">
              <p><strong class="text-2xl">!</strong> Sosyal medyada bir kişi hakkında yalanlar yaymak ya da utandırıcı fotoğraflar yayınlamak</p>
              <p><strong class="text-2xl">!</strong> Mesajlaşma platformlarından incitici mesajlar ya da tehditler yollamak</p>
              <p><strong class="text-2xl">!</strong> Başka birinin kimliğiyle başkalarına kötü mesajlar göndermek</p>
            </ul>
            <div id="nav"></div>
            Yüz yüze zorbalık ve siber zorbalık çoğu kez birlikte gerçekleşir.
            Ancak siber zorbalık geride dijital iz bırakır;
            bu da aslında istismarın durdurulmasını sağlayacak yararlı ip uçları temin edebilir. <br />
            <br />
            <!-- Şiddetin yerine barışı ve hoşgörüyü tercih etmek, her birimizin sorumluluğudur. Küçük çatışmaları bile şiddet yoluyla çözmek yerine, iletişim, anlayış ve uzlaşma yoluyla çözmeliyiz. Bu, daha sağlıklı, daha mutlu ve daha barışçıl bir toplum için adım atmaktır.
          Sonuç olarak, şiddetin hiçbir kazananı yoktur. Şiddet, sadece acıyı ve zararı artırır. Bu nedenle, hepimiz şiddeti reddetmeli ve barış içinde bir arada yaşamanın yollarını bulmalıyız. Her birimiz, küçük adımlarla bile şiddete karşı durabilir ve daha iyi bir dünya için çalışabiliriz. <br> <br> -->
          </p>
        </div>
        <LandingSiberResimImage data-aos="fade-left" class="hidden sm:block py-20" />
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
          Türkiye Siber Zorbalıkta Ne Durumda?
        </h3>
        <div data-aos="fade-up" class="flex flex-wrap items-center justify-center gap-28 font-bold">
          <p>Yaklaşık %12'si sözlü siber zorbalığa maruz kaldığını söylemektedir.
          Öğrencilerin yaklaşık %10.5'i ise sözlü siber zorbalık yaptığını ifade etmektedir</p>
        </div>
      </div>
    </section>

    <!-- Credit card section -->
    <section class="w-full my-36">
      <div id="3"></div>
      <BaseSection data-aos="fade-down">
        <div class="col-span-12 lg:col-span-7">
          <div class="w-full">
            <img :src="require('~/assets/img/SiberZorbalık/Cyber-1.jpeg')" class="w-[95%]" alt="" />
          </div>
        </div>
        <div class="col-span-12 lg:col-span-5 space-y-6 px-4 sm:px-6">
          <h2 class="text-4xl font-semibold">
            <span class="text-header-gradient"> Zorbalık </span> Davranışları
          </h2>
          <h2 class="font-bold">Kişinin fiziksel ve zihinsel bütünlüğüne zarar verme veya kişiyi suistimal etme davranışlarına örnekler:</h2>
            <ul class="space-y-4 sm:space-y-2">
            <LandingListItem title="Aşağılama" />
            <LandingListItem title="İsim takma" />
            <LandingListItem title="Kişiden yararlanma" />
            <LandingListItem title="Güç dengesizliğini hatırlatarak tehdit etme" />
            <LandingListItem title="Dedikodu yaparak sosyal ortamlardan bilinçli olarak dışlama" />
            <LandingListItem title="Dil ve ırk gibi aidiyetlerle dalga geçme" />
            <LandingListItem title="Fiziksel zarar verme niyeti ve tehditleri" />
            <LandingListItem title="Duygusal hasar vermeye yönelik konuşmalar" />
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
          <h2 class="text-3xl font-semibold">Siber Zorbalığı Daha<span class="text-header-gradient"> Tehlikeli </span>Kılan Etkenler?</h2>
          <h2 class="font-bold">Siber zorbalık pek çok kişi tarafından yüz yüze yapılan zorbalıktan farklı ve daha tehlikeli olarak değerlendirilir. Dijital zorbalığı diğer zorbalık türlerinden ayıran nedir?</h2>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Mekansızlık ve Zamansızlık:</h4>
            <p class="paragraph text-sm xl:text-base">
              Öncelikle siber ya da sanal zorbalık diğer tip zorbalıklardan farklı olarak zaman ve mekan fark etmeksizin her an gerçekleşebilir.
              Siber zorbalıktan kaçınmak diğer tip zorbalıklara göre çok daha zor ve mağduru güvenli alanlarında dahi yakalayabilir.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Yayılma Hızı:</h4>
            <p class="paragraph text-sm xl:text-base">
              Bir zorbalık sadece zorba ve mağdur arasında gerçekleşmez. Her zorbalıkta üçüncü bir taraf, yani tanıklar vardır. Mağdur, zorba ve tanıkların ilişkisine zorbalık üçgeni adı verilir. Bu üçgenin bir ucunu oluşturan tanıklar oldukça önemlidir. Tanıkların zorbalığı durdurmak veya devam ettirmek konusunda önemli bir rolü vardır.
              Tanıklar, zorbanın tarafını tuttuğunda zorbalık artarak devam ederken mağdurun tarafını tuttuğunda zorbalık sonlandırılabilir.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Anonimlik:</h4>
            <p class="paragraph text-sm xl:text-base">
              Anonimlik, siber zorbaların uzaktan sergiledikleri zorbaca davranışlardan kopuk hissetmelerinde ve sorumluluk üstlenmemelerinde etkili olur.
              Sosyal normlar, bilgisayar başında daha az etkilidir.
            </p>
          </div>
        </div>
        <LandingSiberResimImageth data-aos="fade-left" class="hidden sm:block py-10" />
      </div>
    </section>

    <section class="bg-trading-tools relative max-w-full sm:mx-4 my-20 py-16 shadow rounded-2xl overflow-hidden">
      <div id="4"></div>
      <div class="relative max-w-screen-xl px-4 sm:px-2 mx-auto grid grid-cols-12 gap-x-6">
        <LandingTradingToolImage class="sm:hidden" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 space-y-8 sm:space-y-6 px-4 sm:px-6 mt-8">
          <h2 class="text-3xl font-semibold">Siber<span class="text-header-gradient"> Zorbalık </span>Karşısında Yapılması Gerekenler</h2>
          <h2 class="font-bold">Siber zorbalığı anonim bir şekilde yapılabildiği için takip etmek ve kontrol etmek zordur.
             Tam da bu sebeple herhangi biri siber zorbalığa maruz kalabilir.
              Siber zorbalık, maruz kalan kişiler üzerinde ciddi bir duygusal yük yaratabilir.
               Siber zorbalığın birçok farklı formu bulunur ve kanıtları toplamak zorbalığın önüne geçme konusunda önem taşır.
                Siber zorbalık karşısında yapabilecekleriniz:</h2>
          <p class="paragraph">
            Durumu güvendiğiniz biriyle paylaşın. Zorbalık davranışlarına maruz kalmak,
            özellikle bu baskı ve yıldırıcı davranışlar uzun süredir devam ediyorsa
            yalnızlaşmanıza sebep olabilir. Güvendiğiniz biriyle konuşarak destek alabilir,
            paylaşımda bulunmanın rahatlığıyla kendinizi daha iyi hissedebilirsiniz.
            Güçlenmelerine engel olmak için zorbaları görmezden gelin. Zorbalar,
            siz onlara cevap verdikçe ve onlar karşısında kendinizi
            ifade etmeye çalıştıkça güçlenirler. Bu sebeple onlarla
            mümkün olduğunca iletişim kurmamaya çalışın.
            Mesajlarına cevap vermeyin veya onlarla herhangi bir etkileşime girmeyin.
            Konuşmaların ekran görüntüsü gibi kanıtları toplayın.
            Siber zorbalığın fark edilmesini belki de en kolaylaştıran
            şeylerden biri internetteki paylaşımların kaydının tutulabiliyor olmasıdır.
            Zorbalığa maruz kaldığınızı düşünüyorsanız söz konusu kişinin paylaşımlarını,
            mesajlarını, size gönderdiği görselleri kayıt altında tutun.
            Sosyal medya platformlarında kişi hakkında şikayet oluşturun. 
            Yaygın kullanılan sosyal medya platformlarında şikayet et/bildir gibi alanlar mevcutur.
            Buralardan faydalanarak veya destek birimlerine mail atarak zorba kişilerin profillerini şikayet edebilirsiniz.
          </p>
        </div>
        <LandingSiberResimImagefr data-aos="fade-left" class="hidden sm:block py-12" />
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
