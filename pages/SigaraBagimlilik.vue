<template>
  <div class="w-full">
    <div class="w-full flex flex-col items-center">
      <h2 data-aos="flip-down" class="text-3xl sm:text-4xl font-semibold text-center">Sigara Bağımlılığı</h2>
    </div>

    <section class="w-full">
      <div id="1"></div>
      <BaseSection>
        <LandingBuyTradeImage class="sm:hidden mb-8 rounded-2xl border" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 mt-4 xl:mt-20 space-y-6 px-4">
          <h2 class="text-4xl font-semibold sm:pr-8 xl:pr-12">Tütün bağımlılığı nedir?</h2>
          <p class="paragraph">
            Dünya Sağlık Örgütüne göre nikotin kullanım bozukluğu olarak da isimlendirilen tütün bağımlılığının temel
            belirtileri şunlardır:
          </p>
          <p class="font-bold">Kullanımı kontrol etme kabiliyetinin bozulması</p>
          <p class="font-bold">Tütün kullanımına diğer etkinliklere göre daha fazla öncelik verilmesi,</p>
          <p class="font-bold">
            - Zararlarla veya olumsuz sonuçlarla karşılaşılmasına rağmen kullanıma devam edilmesi ile kendini gösteren
            güçlü bir nikotin kullanma isteği,
          </p>
          <p class="font-bold">Nikotinin gitgide eski etkisini kaybetmesi (tolerans geliştirilmesi),</p>
          <p class="font-bold">
            Nikotin kullanımının kesilmesi veya azaltılması sonrasında yoksunluk belirtilerinin görülmesi
          </p>
          <p class="paragraph">
            Dünya Sağlık Örgütünün kriterlerine göre bir kişiye “tütün kullanım bozukluğu tanısı” konulabilmesi için,
            bireylerin en az bir aydır, düzenli olarak sigara kullanması ve diğer belirtileri taşıması gerekmektedir.
          </p>
        </div>
        <LandingSigaraResimImage data-aos="fade-left" class="hidden sm:block mt-32" />
        <div id="nav"></div>
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
        <a href="#5">5</a>
        <a href="#6">6</a>
        <a href="#7">7</a>
      </ul>
    </section>
    <div id="2"></div>
    <!-- Partners section -->
    <section class="bg-partner relative max-w-full sm:mx-6 mt-36 shadow sm:rounded-2xl overflow-hidden">
      <div class="w-full px-6 sm:px-0 py-16 flex flex-col items-center justify-center space-y-4 text-center">
        <h3 data-aos="flip-down" class="text-2xl text-neutral-800 font-semibold mb-10">
          En yaygın tütün ürünleri Şunlardır
        </h3>
        <div data-aos="fade-up" class="flex flex-wrap items-center justify-center gap-28 font-bold">
          <p>Sigara</p>
          <p>Sarmalık Kıyılmış tütün mamulü</p>
          <p>Pipo</p>
          <p>Puro</p>
          <p>Nargilelik tütün mamulü</p>
          <p>Enfiye</p>
        </div>
      </div>
    </section>

    <!-- Credit card section -->
    <section class="w-full my-36">
      <div id="3"></div>
      <BaseSection data-aos="fade-down">
        <div class="col-span-12 lg:col-span-7">
          <div class="w-full mt-36">
            <img
              :src="require('~/assets/img/SigaraBagimlilik/psikoterapi-ile-sigarayi-birakmak_767.jpg')"
              class="w-[95%] rounded-2xl border"
              alt=""
            />
          </div>
        </div>
        <div class="col-span-12 lg:col-span-5 space-y-6 px-4 sm:px-6 mt-20">
          <h2 class="text-4xl font-semibold text-red-600">
            Tütün <span class="text-header-gradient"> Yoksunluğu </span>Nedir?
          </h2>
          <p class="paragraph">
            Tütünün özgün maddesi koyu renkli bir sıvıdır ve bahsedilen bu zehirli sıvıya nikotin adı verilmektedir.
            Nikotinin şiddetli bağımlılık yapıcı etkisi vardır. 90-120 dakika boyunca alınmadığında, yoksunluk
            belirtileri ortaya çıkmaya başlar. Bu belirtiler tütünün bırakıldığı ilk gün en üst düzeyde hissedilebilir;
            ancak yoksunluk belirtileri zamanla azalarak yok olmaktadır.
          </p>
          <p class="paragraph">
            Yoksunluk belirtileriyle baş etmek ve istekle başa çıkmak gibi, bırakma sürecinde kişiyi zorlayabilecek bazı
            durumlar ortaya çıkabilir. Bu süreci bir uzman desteği alarak kendiniz için kolaylaştırabilirsiniz
          </p>
          <ul class="space-y-4 sm:space-y-2">
            <LandingListItem title="Kolay kızma ya da öfkelenme" />
            <LandingListItem title="Baş dönmesi" />
            <LandingListItem title="İştah artışı" />
            <LandingListItem title="Kas kasılmaları" />
            <LandingListItem title="Tansiyon düşmesi" />
            <LandingListItem title="Uykusuzluk gibi belirtiler sayılabilir." />
            <LandingListItem title="Şiddetli nikotin alma isteği gibi belirtiler sayılabilir." />
          </ul>
        </div>
      </BaseSection>
    </section>
    <section class="bg-trading-tools relative max-w-full sm:mx-4 my-20 py-16 shadow rounded-2xl overflow-hidden">
      <div id="4"></div>
      <div class="relative max-w-screen-xl px-4 sm:px-2 mx-auto grid grid-cols-12 gap-x-6">
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 space-y-8 sm:space-y-6 px-4 sm:px-6 mt-8">
          <h2 class="text-3xl font-semibold">Pasif İçicilik ya da İkinci El Tütün Dumanına Maruz Kalma Nedir?</h2>
          <div class="space-y-2">
            <p class="paragraph text-sm xl:text-base">
              Tütün, yalnızca kullanıcı olanlarda değil, doğrudan kullanıcısı olmayanlarda da sağlık sorunlarıyla
              birlikte ciddi sonuçlara yol açabilmektedir. Tütün ürünlerinin içindeki toksin (zehir) ve kansere neden
              olabilecek diğer maddeler yanan sigaradan havaya yayılarak, içen kişinin yakınındakiler için zehirli bir
              ortam oluşturur. Bu sebeple tütün kullanmadığı halde tütüne maruz kalanların durumu da büyük bir önem arz
              etmektedir. Bu durum pasif içicilik ya da ikinci el tütün dumanına maruz kalma olarak ele alınmaktadır.
              İkinci el tütün dumanı, sigara ve nargile gibi tütün ürünlerinin kullanıldığı durumlarda kapalı alanları
              dolduran dumandır. Bu dumanın solunması pasif içicilik olarak adlandırılmaktadır.
            </p>
          </div>
          <div class="space-y-2">
            <p class="paragraph text-sm xl:text-base">
              Dünya Sağlık Örgütü 2020 yılı açıklamasına göre; ikinci el tütün dumanına maruz kalma, özellikle erken
              yaşta çok daha kritik sonuçlara sebep olmaktadır. Dünya genelindeki çocuk nüfusunun yaklaşık yarısı tütün
              dumanının kirlettiği havayı solumakta ve bu durum ciddi sağlık sorunlarını ortaya çıkarmaktadır.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">PASİF İÇİCİLİĞİN TEHLİKELERİ ŞU ŞEKİLDEDİR:</h4>
            <ul class="space-y-4 sm:space-y-2">
              <LandingListItem
                title="Yanan bir sigaradan çevreye yayılan duman 50 adeti kanser yapıcı olan 4.000 kimyasal madde ve toksin içermektedir"
              />
              <LandingListItem
                title="Bir sigaranın yaklaşık 12 dakikada yandığını ancak sigara içen bir kişinin sigarayı yalnızca 30 saniye içine çektiğini söyleyebiliriz. Geri kalan dumanı çevredekiler içine çekmektedir."
              />
              <LandingListItem
                title="Çevreye yayılan sigara dumanı içilenden daha zararlıdır. Çünkü sigara içildiği zaman ısı daha yüksektir; ancak çevreye yayılan duman daha düşük ısıdan yayılmaktadır"
              />
              <LandingListItem
                title="Çevreye yayılan sigara dumanı normal olarak içilen sigaradan 3 kat daha fazla nikotin, yüzde 70 oranında daha fazla katran ve 2,5 kat fazla karbon monoksit içermektedir."
              />
            </ul>
          </div>
        </div>
        <LandingPasifIcicilikImage data-aos="fade-left" class="hidden sm:block rounded-2xl lg:mt-56 mt-24" />
      </div>
    </section>

    <section class="w-full my-36">
      <div id="5"></div>
      <BaseSection data-aos="fade-down">
        <div class="col-span-12 lg:col-span-7">
          <div class="w-full mt-36">
            <img
              :src="require('~/assets/img/SigaraBagimlilik/tutun-bagimliligi.png')"
              class="w-[95%] rounded-2xl border"
              alt=""
            />
          </div>
        </div>
        <div class="col-span-12 lg:col-span-5 space-y-6 px-4 sm:px-6 mt-20">
          <h2 class="text-4xl font-semibold text-red-600">
            Tütün Bağımlılığının Yol Açtığı <span class="text-header-gradient"> Sağlık </span>Sorunları Nelerdir?
          </h2>
          <h1 class="font-bold">Tütün kullanımı aşağıdaki hastalıkların oluşmasında etkilidir</h1>
          <ul class="space-y-4 sm:space-y-2">
            <LandingListItem title="Kanser türleri (akciğer, mide, cilt, rahim ağzı vs.)" />
            <LandingListItem title="Kalp ve damar hastalıkları" />
            <LandingListItem title="Diyabet" />
            <LandingListItem title="Solunum hastalıkları" />
            <LandingListItem title="Gastrit, Ülser gibi mide hastalıkları" />
            <LandingListItem
              title="Diş ve diş eti hastalıkları Gebelikte erken doğum, düşük doğum, çocukta gelişim bozuklukları, sütün kesilmesi"
            />
          </ul>
          <p class="paragraph">
            Tütün kullanımı, halk sağlığı açısından kritik bir sorundur ve toplumun genel hastalık riskini ve yükünü
            artırmaktadır. Dünya Sağlık Örgütünün 2019 yılı Avrupa Tütün Kullanım Trendleri Raporuna göre; sigara
            kullanımı erken ölüm riskini artırmaktadır. Aynı raporda tütün kullanımı dünyadaki erken ölümlerin önde
            gelen nedenlerinden biri olarak bildirilmektedir ve tüm ölümlerin yaklaşık yüzde 18 üzerinde etkili olduğu
            belirtilmektedir
          </p>
        </div>
      </BaseSection>
    </section>

    <section class="bg-trading-tools relative max-w-full sm:mx-4 my-20 py-16 shadow rounded-2xl overflow-hidden">
      <div id="6"></div>
      <div class="relative max-w-screen-xl px-4 sm:px-2 mx-auto grid grid-cols-12 gap-x-6">
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 space-y-8 sm:space-y-6 px-4 sm:px-6 mt-8">
          <h2 class="text-3xl font-semibold">Tütün Kullanımının Çocuk ve Ergenler Üzerindeki Etkileri Nelerdir?</h2>
          <div class="space-y-2">
            <p class="paragraph text-sm xl:text-base">
              Şüphesiz ki tütün kullanımı toplumun tamamını ilgilendiren bir sorun olarak görülmektedir. Öte yandan
              gelişme çağındaki çocuk ve ergenler üzerinde daha kalıcı etkiler bırakmaktadır. Bu dönemlerdeki etkileri
              değerlendirdiğimizde şunları söyleyebiliriz:
            </p>
            <ul class="space-y-4 sm:space-y-2 mt-4">
              <LandingListItem
                title="Çocukluk ve ergenlik dönemleri, gerek tütün tüketimi gerekse yasa dışı uyuşturucu madde kullanımı da dâhil olmak üzere birçok sağlığa zararlı davranışta bulunma eğiliminin ortaya çıkabildiği bir tür deneme dönemidir"
              />
              <LandingListItem
                title="Tütün kullanan çocuk ve ergenlerin yetişkinlik döneminde düzenli tütün kullanıcısı olma olasılığı daha yüksektir"
              />
              <LandingListItem
                title="Çocukluk ve ergenlik döneminde tütün içmek kısa vadede astım uzun vadede kalp-damar, solunum ve kanser gibi hastalıkların riskini artırmaktadır"
              />
              <LandingListItem
                title="Tütün kullanımı bireyin psikolojik, fiziksel ve sosyal yaşamını olumsuz etkilemekte; erken ölüm riskini artırmaktadır."
              />
              <LandingListItem
                title="Tütün kullanımından dolayı ortaya çıkan duman, kullanmayan kişiler için de ciddi sonuçlar doğurmaktadır. İkinci el tütün dumanı; kalp hastalığına, kansere ve diğer kronik hastalıklara sebep olabilmektedir"
              />
            </ul>
          </div>
        </div>
        <LandingTütünKullanimiImage data-aos="fade-left" class="hidden sm:block rounded-2xl lg:mt-56 mt-24" />
      </div>
    </section>
    <section class="bg-partner relative max-w-full sm:mx-6 mt-36 shadow sm:rounded-2xl overflow-hidden">
      <div id="7"></div>
      <div class="w-full px-6 sm:px-0 py-16 flex flex-col items-center justify-center space-y-4 text-center">
        <div data-aos="fade-up" class="flex flex-wrap items-center justify-center gap-28 font-bold">
          <video width="320" height="240" controls preload="none">
            <source src="public/videos/SigaraveSağlığaZararları.mp4" type="video/mp4" />
            Tarayıcınız video etiketini desteklemiyor.
          </video>
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
  name: 'SigaraBagimlilik',
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
