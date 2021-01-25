<template>
  <div class="main">
    <div>
      <div class="container">
        <div class="hero-slider relative" x-data>
          <div class="glide__track" data-glide-el="track">
            <div class="glide__slides">
              <div class="glide__slide">
                <div
                  class="bg-left sm:bg-center bg-no-repeat bg-cover"
                  style="background-image: url(/assets/img/hero-slide-01.jpg)"
                >
                  <div
                    class="py-48 px-6 sm:px-10 md:px-12 xl:px-24 text-center sm:text-left sm:w-5/6 lg:w-3/4 xl:w-2/3"
                  >
                    <h3
                      class="font-butlermedium text-secondary text-3xl sm:text-4xl md:text-5xl lg:text-6xl"
                    >
                      Aillevia New Men’s Outdoor Collection
                    </h3>
                    <a
                      href="/collection-grid"
                      class="btn btn-primary btn-lg mt-8"
                      >Know more</a
                    >
                  </div>
                </div>
              </div>

              <div class="glide__slide">
                <div
                  class="bg-left sm:bg-center bg-no-repeat bg-cover"
                  style="background-image: url(/assets/img/hero-slide-02.jpg)"
                >
                  <div
                    class="py-48 px-6 sm:px-10 md:px-12 xl:px-24 text-center sm:text-left sm:w-5/6 lg:w-3/4 xl:w-2/3"
                  >
                    <h3
                      class="font-butlermedium text-secondary text-3xl sm:text-4xl md:text-5xl lg:text-6xl"
                    >
                      Blake by Aillevia <br />
                      30% off
                    </h3>
                    <a
                      href="/collection-grid"
                      class="btn btn-primary btn-lg mt-8"
                      >Know more</a
                    >
                  </div>
                </div>
              </div>

              <div class="glide__slide">
                <div
                  class="bg-left sm:bg-center bg-no-repeat bg-cover"
                  style="background-image: url(/assets/img/hero-slide-03.jpg)"
                >
                  <div
                    class="py-48 px-6 sm:px-10 md:px-12 xl:px-24 text-center sm:text-left sm:w-5/6 lg:w-3/4 xl:w-2/3"
                  >
                    <h3
                      class="font-butlermedium text-secondary text-3xl sm:text-4xl md:text-5xl lg:text-6xl"
                    >
                      Hoodie your way! <br />
                      For Men
                    </h3>
                    <a
                      href="/collection-grid"
                      class="btn btn-primary btn-lg mt-8"
                      >Know more</a
                    >
                  </div>
                </div>
              </div>

              <div class="glide__slide">
                <div
                  class="bg-left sm:bg-center bg-no-repeat bg-cover"
                  style="background-image: url(/assets/img/hero-slide-04.jpg)"
                >
                  <div
                    class="py-48 px-6 sm:px-10 md:px-12 xl:px-24 text-center sm:text-left sm:w-5/6 lg:w-3/4 xl:w-2/3"
                  >
                    <h3
                      class="font-butlermedium text-secondary text-3xl sm:text-4xl md:text-5xl lg:text-6xl"
                    >
                      Match and play Women’s Dresses
                    </h3>
                    <a
                      href="/collection-grid"
                      class="btn btn-primary btn-lg mt-8"
                      >Know more</a
                    >
                  </div>
                </div>
              </div>

              <div class="glide__slide">
                <div
                  class="bg-left sm:bg-center bg-no-repeat bg-cover"
                  style="background-image: url(/assets/img/hero-slide-05.jpg)"
                >
                  <div
                    class="py-48 px-6 sm:px-10 md:px-12 xl:px-24 text-center sm:text-left sm:w-5/6 lg:w-3/4 xl:w-2/3"
                  >
                    <h3
                      class="font-butlermedium text-secondary text-3xl sm:text-4xl md:text-5xl lg:text-6xl"
                    >
                      Back to school, <br />
                      the stylish way
                    </h3>
                    <a
                      href="/collection-grid"
                      class="btn btn-primary btn-lg mt-8"
                      >Know more</a
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div
            class="absolute bottom-0 inset-x-0 mb-6 z-30 text-center"
            data-glide-el="controls[nav]"
          >
            <span
              class="inline-block border border-primary transition-colors hover:bg-secondary-lighter p-1 rounded-full mr-1 focus:outline-none cursor-pointer"
              data-glide-dir="=0"
            ></span>
            <span
              class="inline-block border border-primary transition-colors hover:bg-secondary-lighter p-1 rounded-full mr-1 focus:outline-none cursor-pointer"
              data-glide-dir="=1"
            ></span>
            <span
              class="inline-block border border-primary transition-colors hover:bg-secondary-lighter p-1 rounded-full mr-1 focus:outline-none cursor-pointer"
              data-glide-dir="=2"
            ></span>
            <span
              class="inline-block border border-primary transition-colors hover:bg-secondary-lighter p-1 rounded-full mr-1 focus:outline-none cursor-pointer"
              data-glide-dir="=3"
            ></span>
            <span
              class="inline-block border border-primary transition-colors hover:bg-secondary-lighter p-1 rounded-full focus:outline-none cursor-pointer"
              data-glide-dir="=4"
            ></span>
          </div>
        </div>

        <div class="flex flex-col md:flex-row py-20 md:py-24">
          <div
            class="sm:w-1/2 md:w-2/5 lg:w-1/3 mx-auto lg:mx-0 flex md:flex-col lg:flex-row items-center justify-center md:text-center lg:text-left md:border-r-2 last:border-r-0 md:border-primary-lighter pb-3 md:pb-0"
          >
            <div>
              <img
                src="/assets/img/icons/icon-shipping.svg"
                class="w-auto h-12"
                alt="icon"
              />
            </div>
            <div class="ml-6 mt-3 lg:mt-0">
              <h3 class="font-hksemibold text-primary text-xl tracking-wide">
                Free shipping
              </h3>
              <p
                class="font-hkregular text-secondary-lighter text-base tracking-wide"
              >
                On all orders over $30
              </p>
            </div>
          </div>

          <div
            class="sm:w-1/2 md:w-2/5 lg:w-1/3 mx-auto lg:mx-0 flex md:flex-col lg:flex-row items-center justify-center md:text-center lg:text-left md:border-r-2 last:border-r-0 md:border-primary-lighter pb-3 md:pb-0"
          >
            <div>
              <img
                src="/assets/img/icons/icon-support.svg"
                class="w-auto h-12"
                alt="icon"
              />
            </div>
            <div class="ml-6 mt-3 lg:mt-0">
              <h3 class="font-hksemibold text-primary text-xl tracking-wide">
                Always available
              </h3>
              <p
                class="font-hkregular text-secondary-lighter text-base tracking-wide"
              >
                24/7 call center available
              </p>
            </div>
          </div>

          <div
            class="sm:w-1/2 md:w-2/5 lg:w-1/3 mx-auto lg:mx-0 flex md:flex-col lg:flex-row items-center justify-center md:text-center lg:text-left md:border-r-2 last:border-r-0 md:border-primary-lighter pb-3 md:pb-0"
          >
            <div>
              <img
                src="/assets/img/icons/icon-return.svg"
                class="w-auto h-12"
                alt="icon"
              />
            </div>
            <div class="ml-6 mt-3 lg:mt-0">
              <h3 class="font-hksemibold text-primary text-xl tracking-wide">
                Free returns
              </h3>
              <p
                class="font-hkregular text-secondary-lighter text-base tracking-wide"
              >
                30 days free return policy
              </p>
            </div>
          </div>
        </div>

        <div class="pb-20 md:pb-24 lg:pb-32 flex flex-wrap justify-between">
          <div class="lg:w-1/2 px-10 mx-auto lg:mx-0 text-center lg:text-left">
            <div class="lg:w-3/4 xl:w-2/3 lg:pt-10 pb-4 md:pb-10">
              <h1
                class="font-butlerregular text-secondary text-3xl md:text-4xl lg:text-7xl"
              >
                Trending Aillevia Collections
              </h1>
              <p class="font-hkregular text-secondary-lighter text-lg pt-4">
                Checkout our newest trends this coming season
              </p>
            </div>
          </div>
          <div class="w-full lg:w-1/2 mt-6 sm:mt-10 lg:mt-0">
            <div
              class="px-10 h-56 sm:h-76 bg-left sm:bg-center bg-no-repeat bg-cover relative"
              style="background-image: url(/assets/img/collection-01.jpg)"
            >
              <div class="w-2/3 absolute inset-0 px-6 md:px-10 py-14">
                <h3
                  class="font-hksemibold text-secondary text-xl sm:text-2xl md:text-3xl"
                >
                  Passion Pearl <br />
                  Collection
                </h3>
                <a href="/collection-list" class="flex items-center pt-5 group">
                  <div
                    class="bg-white rounded-full h-8 w-8 flex items-center justify-center"
                  >
                    <i
                      class="bx bx-chevron-right text-xl text-primary group-hover:text-v-red transition-colors"
                    ></i>
                  </div>
                  <span>
                    <p
                      class="font-hksemibold transition-colors text-primary group-hover:text-v-red sm:text-lg pl-3 sm:pl-5 leading-none -mt-1"
                    >
                      Get it now
                    </p>
                  </span>
                </a>
              </div>
            </div>
          </div>
          <div class="w-full lg:w-1/2 lg:px-10 mt-8 sm:mt-10">
            <div
              class="bg-left sm:bg-center bg-no-repeat bg-cover relative h-56 sm:h-76 lg:h-68"
              style="background-image: url(/assets/img/collection-02.jpg)"
            >
              <div class="md:w-2/3 absolute inset-0 px-6 md:px-10 py-14">
                <h3
                  class="font-hksemibold text-secondary text-xl sm:text-2xl md:text-3xl"
                >
                  Hoodie your way! For Men
                </h3>
                <a href="/collection-list" class="flex items-center pt-5 group">
                  <div
                    class="bg-white rounded-full p-2 h-8 w-8 flex items-center justify-center"
                  >
                    <i
                      class="bx bx-chevron-right text-xl text-primary group-hover:text-v-red transition-colors"
                    ></i>
                  </div>
                  <p
                    class="font-hksemibold text-primary transition-colors group-hover:text-v-red sm:text-lg pl-3 sm:pl-5 leading-none -mt-1"
                  >
                    Get it now
                  </p>
                </a>
              </div>
            </div>
            <div
              class="bg-left sm:bg-center bg-no-repeat bg-cover relative h-56 sm:h-76 lg:h-68 mt-8 sm:mt-10"
              style="background-image: url(/assets/img/collection-03.jpg)"
            >
              <div class="w-2/3 absolute inset-0 px-6 md:px-10 py-14">
                <h3
                  class="font-hksemibold text-secondary text-xl sm:text-2xl md:text-3xl"
                >
                  Anabelle Purses by Aillevia
                </h3>
                <a href="/collection-list" class="flex items-center pt-5 group">
                  <div
                    class="bg-white rounded-full p-2 h-8 w-8 flex items-center justify-center"
                  >
                    <i
                      class="bx bx-chevron-right text-xl text-primary group-hover:text-v-red transition-colors"
                    ></i>
                  </div>
                  <p
                    class="font-hksemibold text-primary transition-colors group-hover:text-v-red sm:text-lg pl-3 sm:pl-5 leading-none -mt-1"
                  >
                    Get it now
                  </p>
                </a>
              </div>
            </div>
          </div>
          <div
            class="w-full lg:w-1/2 px-10 h-82 sm:h-94 lg:h-96 bg-left sm:bg-center bg-no-repeat bg-cover relative mt-8 sm:mt-10"
            style="background-image: url(/assets/img/collection-shoes.jpg)"
          >
            <div class="w-2/3 absolute inset-0 px-6 md:px-10 py-14 sm:py-16">
              <h3
                class="font-hksemibold text-secondary text-xl sm:text-2xl md:text-3xl"
              >
                W.W. Shoes <br />
                by Aillevia
              </h3>
              <a href="/collection-list" class="flex items-center pt-5 group">
                <div
                  class="bg-white rounded-full p-2 h-8 w-8 flex items-center justify-center"
                >
                  <i
                    class="bx bx-chevron-right text-xl text-primary group-hover:text-v-red transition-colors"
                  ></i>
                </div>
                <p
                  class="font-hksemibold text-primary transition-colors group-hover:text-v-red sm:text-lg pl-3 sm:pl-5 leading-none -mt-1"
                >
                  Get it now
                </p>
              </a>
            </div>
          </div>
        </div>
      </div>

      <div class="container mb-28">
        <div
          class="bg-center bg-no-repeat bg-cover"
          style="background-image: url(/assets/img/bg-cta.png)"
        >
          <div class="py-16 md:py-20 text-center">
            <h3
              class="font-butlerregular text-white text-3xl sm:text-4xl tracking-wide"
            >
              Let's keep in touch
            </h3>
            <p
              class="font-hkregular font-bold text-white text-lg sm:text-xl pt-3 px-6"
            >
              Join our list and save 15% off your first order.
            </p>
            <form class="pt-10 sm:pt-12">
              <div
                class="w-5/6 sm:w-3/4 lg:w-3/5 xl:w-1/2 mx-auto flex flex-col sm:flex-row justify-center items-center"
              >
                <label
                  for="cta_email"
                  class="block relative h-0 w-0 overflow-hidden"
                  >Email</label
                >
                <input
                  id="cta_email"
                  type="email"
                  name="cta_email"
                  placeholder="ENTER YOUR EMAIL"
                  class="form-input bg-transparent text-sm text-white border-white"
                />
                <button
                  type="button"
                  class="button bg-primary sm:ml-5 mt-4 sm:mt-0 w-full sm:w-auto text-white"
                  aria-label="Subscribe button"
                >
                  SUBSCRIBE
                </button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
    <div>
      <!-- <h1 class="title">Aillevia.com</h1> -->
      <!-- <Logo />
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a>
      </div> -->

      <!-- <nuxt-link :to="localePath('index')">{{ $t('welcome') }}</nuxt-link>
      <nuxt-link :to="localePath('/')">{{ $t('welcome') }}</nuxt-link>
      <nuxt-link :to="localePath('index', 'en')">Homepage in English</nuxt-link>
      <nuxt-link :to="switchLocalePath('en')">English</nuxt-link>
      <nuxt-link :to="switchLocalePath('fr')">Français</nuxt-link> -->
    </div>
  </div>
</template>

<script>
import Glide from '@glidejs/glide'

export default {
  data() {
    return {}
  },
  mounted() {
    new Glide('.hero-slider', { autoplay: 3000, type: 'carousel' }).mount()
    this.collectionSliders()
    this.productSlider()
    this.postSlider()
    // console.log('this locale default ', this.$i18n.locale)
  },
  methods: {
    collectionSliders() {
      document.querySelectorAll('.collection-slider').forEach(slider => {
        new Glide(slider, {
          autoplay: 2000,
          type: 'carousel',
          perView: 3,
          gap: 30,
          breakpoints: {
            1024: {
              perView: 2,
            },
          },
        }).mount()
      })
    },
    productSlider() {
      document.querySelectorAll('.product-slider').forEach(slider => {
        new Glide(slider, {
          type: 'carousel',
          startAt: 1,
          perView: 4,
          gap: 0,
          peek: {
            before: 50,
            after: 50,
          },
          breakpoints: {
            1024: {
              perView: 3,
              peek: {
                before: 20,
                after: 20,
              },
            },
            768: {
              perView: 2,
              peek: {
                before: 10,
                after: 10,
              },
            },
            600: {
              perView: 1,
              peek: {
                before: 0,
                after: 0,
              },
            },
          },
        }).mount()
      })
    },
    postSlider() {
      document.querySelectorAll('.posts-slider').forEach(slider => {
        new Glide(slider, {
          type: 'carousel',
          startAt: 1,
          perView: 3,
          gap: 0,
          peek: {
            before: 50,
            after: 50,
          },
          breakpoints: {
            1024: {
              perView: 3,
              peek: {
                before: 20,
                after: 20,
              },
            },
            768: {
              perView: 2,
              peek: {
                before: 10,
                after: 10,
              },
            },
            600: {
              perView: 1,
              peek: {
                before: 0,
                after: 0,
              },
            },
          },
        }).mount()
      })
    },
  },
  head() {
    return {
      link: [
        {
          rel: 'stylesheet',
          href:
            'https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css',
          integrity: 'sha256-imWjOiEEAcjWdL1+inhBu1dWYFyXuiO9vpJVEQd3y/c=',
          crossorigin: 'anonymous',
        },
        {
          rel: 'stylesheet',
          href: '/assets/styles/fonts.css',
          media: 'screen',
          crossorigin: 'anonymous',
        },
      ],
      script: [],
    }
  },
}
</script>

<style>
/* .container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
} */
</style>
