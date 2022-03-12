<template>
  <div class="flex flex-col min-h-screen overflow-hidden">

    <!-- Site header -->
    <Header />

    <!-- Page content -->
    <main class="flex-grow">

      <!-- Page illustration -->
      <div class="relative max-w-6xl mx-auto h-0 pointer-events-none -z-1" aria-hidden="true">
        <PageIllustration />
      </div>

      <!-- Page sections -->
      <HeroFAQ />
      <section class="relative">

        <div class="relative max-w-6xl mx-auto px-4 sm:px-6 pb-12">
          <div class="pt-4 pb-2 md:pt-3 md:pb-2">

            <div class="max-w-3xl" data-aos="fade-down">
              <h4 class="h4">What is Chimpedia?</h4>
              <p class="text-xl text-gray-600 dark:text-gray-400">
                An app for admirers of Chimpions everywhere. Chimpedia lets you browse and favorite all your Chimpions.
                The home screen widget displays a fresh Chimpion every half hour.
              </p>
            </div>

            <div class="max-w-3xl pt-8 md:pt-6" data-aos="fade-down">
              <h4 class="h4">What exactly are The Chimpions?</h4>
              <p class="text-xl text-gray-600 dark:text-gray-400">
                The Chimpions are an NFT collection of 222 hand-drawn chimps. Learn more at:
              </p>
              <ul>
                <li>🐒 <a href="https://www.chimpions.co/">https://www.chimpions.co/</a></li>
                <li>🐒 <a href="https://twitter.com/TheChimpions">https://twitter.com/TheChimpions</a></li>
              </ul>
            </div>

            <div class="max-w-3xl pt-8 md:pt-6" data-aos="fade-down">
              <h4 class="h4">Is this an official Chimpions app?</h4>
              <p class="text-xl text-gray-600 dark:text-gray-400">
                This is not an official app! The Chimpion team didn't commission this. Nobody paid me to build this. This app is built for the community, by the community.
              </p>
            </div>

            <div class="max-w-3xl pt-8 md:pt-6" data-aos="fade-down">
              <h4 class="h4">Why was this app built?</h4>
              <p class="text-xl text-gray-600 dark:text-gray-400">
                Because I'm a fan and this is fun for me. :)
              </p>
            </div>

            <div class="max-w-3xl pt-8 md:pt-6" data-aos="fade-down">
              <h4 class="h4">Have other questions or comments?</h4>
              <p class="text-xl text-gray-600 dark:text-gray-400">
                Message me on <a href="https://twitter.com/chart_garden">Twitter</a>!
              </p>
            </div>

          </div>
        </div>

      </section>

    </main>

    <!-- Site footer -->
    <Footer />

  </div>
</template>

<script>
import Header from './../partials/Header.vue'
import PageIllustration from './../partials/PageIllustration.vue'
import HeroFAQ from "./../partials/HeroFAQ.vue";
import Footer from './../partials/Footer.vue'

export default {
  name: 'FAQ',
  created () {
    document.title = "FAQ";
  },
  components: {
    Header,
    PageIllustration,
    HeroFAQ,
    Footer,
  },
};
</script>
