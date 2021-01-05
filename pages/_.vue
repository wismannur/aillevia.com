<template>
  <div id="main">
    <div class="container py-10 relative">
      <div class="flex justify-between items-center">
        <div class="hidden lg:block">
          <div class="flex items-center">
            <a
              href="/"
              class="border-2 transition-all border-transparent hover:border-primary rounded-full px-4 py-4 mr-8 group"
            >
              <img
                src="/assets/img/icons/icon-search.svg"
                class="w-8 h-8 block group-hover:hidden"
                alt="icon search"
              />
              <img
                src="/assets/img/icons/icon-search-hover.svg"
                class="w-8 h-8 hidden group-hover:block"
                alt="icon search hover"
              />
            </a>

            <a
              href="/account/wishlist/"
              class="border-2 transition-all border-transparent hover:border-primary rounded-full px-4 py-4 group"
            >
              <img
                src="/assets/img/icons/icon-heart.svg"
                class="w-8 h-8 block group-hover:hidden"
                alt="icon heart"
              />
              <img
                src="/assets/img/icons/icon-heart-hover.svg"
                class="w-8 h-8 hidden group-hover:block"
                alt="icon heart hover"
              />
            </a>
          </div>
        </div>
        <a href="/">
          <img
            src="/assets/img/logo-elyssi.svg"
            class="w-48 h-auto"
            alt="logo"
          />
        </a>
        <div class="hidden lg:block">
          <div class="flex items-center">
            <a
              href="/account/dashboard"
              class="border-2 transition-all border-transparent hover:border-primary rounded-full px-4 py-4 group"
            >
              <img
                src="/assets/img/icons/icon-user.svg"
                class="w-8 h-8 block group-hover:hidden"
                alt="icon user"
              />
              <img
                src="/assets/img/icons/icon-user-hover.svg"
                class="w-8 h-8 hidden group-hover:block"
                alt="icon user hover"
              />
            </a>

            <a
              href="/cart"
              class="border-2 transition-all border-transparent hover:border-primary rounded-full px-4 py-4 ml-8 group"
            >
              <img
                src="/assets/img/icons/icon-cart.svg"
                class="w-8 h-8 block group-hover:hidden"
                alt="icon cart"
              />
              <img
                src="/assets/img/icons/icon-cart-hover.svg"
                class="w-8 h-8 hidden group-hover:block"
                alt="icon cart hover"
              />
            </a>
          </div>
        </div>
        <div class="block lg:hidden">
          <i
            class="bx bx-menu text-primary text-3xl"
            @click="mobileMenu = true"
          ></i>
        </div>
      </div>
      <div class="flex justify-center lg:pt-8">
        <ul class="list-reset flex items-center">
          <li class="mr-10 hidden lg:block">
            <a
              href="/"
              class="block text-lg font-hkregular hover:font-hkbold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
              >Home</a
            >
          </li>

          <li class="mr-10 hidden lg:block">
            <a
              href="/about"
              class="block text-lg font-hkregular hover:font-hkbold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
              >About</a
            >
          </li>

          <li class="mr-10 hidden lg:block group">
            <div
              class="border-b-2 border-white transition-colors group-hover:border-primary flex items-center"
            >
              <span
                class="cursor-pointer text-lg font-hkregular group-hover:font-hkbold text-secondary group-hover:text-primary px-2 transition-all"
                >Collections</span
              >
              <i
                class="bx bx-chevron-down text-secondary group-hover:text-primary pl-2 px-2 transition-colors"
              ></i>
            </div>
            <div
              class="pt-10 absolute mt-40 top-0 left-0 right-0 -z-1 group-hover:z-50 w-2/3 mx-auto"
            >
              <div
                class="opacity-0 pointer-events-none group-hover:opacity-100 group-hover:pointer-events-auto transition-all flex bg-white shadow-lg p-8 rounded-b relative"
              >
                <div class="flex-1 relative z-20">
                  <h4 class="font-hkbold text-base text-secondary mb-2">Man</h4>
                  <ul>
                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Boots</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Blutcher Boot</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Chelsea Boot</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Chukka Boot</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Dress Boot</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Work Boot</a
                      >
                    </li>
                  </ul>
                </div>

                <div class="flex-1 relative z-20">
                  <h4 class="font-hkbold text-base text-secondary mb-2">
                    Woman
                  </h4>
                  <ul>
                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Accessories</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Belts</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Caps</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Laces</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Socks</a
                      >
                    </li>
                  </ul>
                </div>

                <div class="flex-1 relative z-20">
                  <h4 class="font-hkbold text-base text-secondary mb-2">
                    Kids
                  </h4>
                  <ul>
                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Shoes</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Derby Shoes</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Belts</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Caps</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Laces</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="text-sm font-hkregular text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                        >Socks</a
                      >
                    </li>
                  </ul>
                </div>

                <div class="flex-1">
                  <div
                    class="z-0 bg-contain bg-right-bottom bg-no-repeat absolute inset-0"
                    style="
                      background-image: url(https://source.unsplash.com/1000x640/?enu);
                    "
                  ></div>
                </div>
              </div>
            </div>
          </li>

          <li class="mr-10 hidden lg:block">
            <a
              href="/blog"
              class="block text-lg font-hkregular hover:font-hkbold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
              >Blog</a
            >
          </li>

          <li class="mr-10 hidden lg:block">
            <a
              href="/contact#faq"
              class="block text-lg font-hkregular hover:font-hkbold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
              >FAQ</a
            >
          </li>

          <li class="mr-10 hidden lg:block">
            <a
              href="/contact"
              class="block text-lg font-hkregular hover:font-hkbold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
              >Contact</a
            >
          </li>
        </ul>
      </div>
    </div>

    <div
      class="fixed inset-0 flex z-50 justify-end opacity-0 pointer-events-none transition-all"
      :class="{ 'opacity-100 pointer-events-auto': mobileMenu }"
    >
      <div
        class="bg-black opacity-50 absolute inset-0 z-10"
        @click="mobileMenu = false"
      ></div>
      <div
        class="w-2/3 md:w-1/2 z-20 h-full absolute shadow bg-primary-lightest overflow-auto flex flex-col"
      >
        <span class="ml-auto p-2" @click="mobileMenu = false"
          ><i class="bx bx-x text-secondary text-3xl"></i
        ></span>
        <ul>
          <li>
            <a
              href="/"
              class="p-3 uppercase text-secondary border-t border-grey-darker block"
              >Home</a
            >
          </li>

          <li>
            <a
              href="/about"
              class="p-3 uppercase text-secondary border-t border-grey-darker block"
              >About</a
            >
          </li>

          <li class="flex justify-between flex-col">
            <div class="flex justify-between border-t border-grey-darker">
              <span class="p-3 uppercase text-secondary block">Categories</span>
              <span
                class="p-3 border-l border-grey-darker"
                @click="categories = !categories"
              >
                <i
                  class="mt-1 bx bxs-down-arrow text-secondary text-sm pointer-events-none"
                  :class="{ 'bxs-up-arrow': categories }"
                ></i
              ></span>
            </div>
            <div
              class="bg-primary-lighter overflow-hidden transition-all item-height"
              :class="{ active: categories }"
            >
              <div>
                <div class="flex justify-between border-t border-grey-darker">
                  <span class="p-3 uppercase text-secondary block">Man</span>
                  <span
                    class="p-3 border-l border-grey-darker"
                    @click="subcategory = !subcategory"
                    ><i
                      class="mt-1 bx bxs-down-arrow text-secondary text-sm pointer-events-none"
                    ></i
                  ></span>
                </div>
                <div
                  class="mobile-menu-categories bg-v-v-pink max-h-0 overflow-hidden transition-all item-height"
                  :class="{ active: subcategory }"
                >
                  <ul>
                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Boots</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Blutcher Boot</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Chelsea Boot</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Chukka Boot</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Dress Boot</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Work Boot</a
                      >
                    </li>
                  </ul>
                </div>
              </div>

              <div>
                <div class="flex justify-between border-t border-grey-darker">
                  <span class="p-3 uppercase text-secondary block">Woman</span>
                  <span
                    class="p-3 border-l border-grey-darker"
                    @click="subcategory = !subcategory"
                    ><i
                      class="mt-1 bx bxs-down-arrow text-secondary text-sm pointer-events-none"
                    ></i
                  ></span>
                </div>
                <div
                  class="mobile-menu-categories bg-v-v-pink max-h-0 overflow-hidden transition-all item-height"
                  :class="{ active: subcategory }"
                >
                  <ul>
                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Accessories</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Belts</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Caps</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Laces</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Socks</a
                      >
                    </li>
                  </ul>
                </div>
              </div>

              <div>
                <div class="flex justify-between border-t border-grey-darker">
                  <span class="p-3 uppercase text-secondary block">Kids</span>
                  <span
                    class="p-3 border-l border-grey-darker"
                    @click="subcategory = !subcategory"
                    ><i
                      class="mt-1 bx bxs-down-arrow text-secondary text-sm pointer-events-none"
                    ></i
                  ></span>
                </div>
                <div
                  class="mobile-menu-categories bg-v-v-pink max-h-0 overflow-hidden transition-all item-height"
                  :class="{ active: subcategory }"
                >
                  <ul>
                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Shoes</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Derby Shoes</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Belts</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Caps</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Laces</a
                      >
                    </li>

                    <li>
                      <a
                        href="/collection-grid"
                        class="p-3 uppercase text-secondary border-t border-grey-darker block"
                        >Socks</a
                      >
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </li>

          <li>
            <a
              href="/blog"
              class="p-3 uppercase text-secondary border-t border-grey-darker block"
              >Blog</a
            >
          </li>

          <li>
            <a
              href="/contact#faq"
              class="p-3 uppercase text-secondary border-t border-grey-darker block"
              >FAQ</a
            >
          </li>

          <li>
            <a
              href="/contact"
              class="p-3 uppercase text-secondary border-t border-grey-darker block"
              >Contact</a
            >
          </li>

          <li>
            <a
              href="/account/dashboard"
              class="p-3 uppercase text-secondary border-t border-grey-darker block"
              >Account</a
            >
          </li>
          <li>
            <a
              href="/cart"
              class="p-3 uppercase text-secondary border-t border-b border-grey-darker block"
              >Cart</a
            >
          </li>
        </ul>
      </div>
    </div>

    <div>
      <!-- unibeautify:enable -->

      <div class="bg-grey-light py-40">
        <div class="container">
          <div class="flex items-center justify-center">
            <div
              class="bg-center bg-cover bg-no-repeat h-90 w-96"
              style="background-image: url(/assets/img/404-image.svg)"
            ></div>
            <div class="pl-20">
              <h2
                class="font-butlerbold text-secondary text-6xl md:text-10xl tracking-wide leading-none pb-8"
              >
                404
              </h2>
              <h3
                class="font-butlerbold text-secondary text-6xl md:text-7xl tracking-wide leading-none"
              >
                Oops... Page not found.
              </h3>
              <p
                class="font-hkregular font-bold text-secondary text-xl sm:text-2xl mt-10"
              >
                It looks like this page doesn't exist,
                <br class="hidden sm:block" />
                you can return to the homepage by clicking
                <a href="/" class="border-b-4 border-primary text-primary"
                  >here</a
                >.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div
      class="bg-center bg-no-repeat bg-cover"
      style="background-image: url(/assets/img/bg-footer.png)"
    >
      <div class="container py-16 sm:py-20 md:py-24">
        <div
          class="w-5/6 mx-auto flex flex-col lg:flex-row items-center justify-between"
        >
          <div class="text-center lg:text-left">
            <h4 class="font-hkbold text-white text-xl pb-8">Contact</h4>
            <ul class="list-reset">
              <li class="pb-2 block">
                <a
                  href="mailto:test.email0123@elyssi.com"
                  class="font-hkregular text-white transition-colors hover:text-primary text-base tracking-wide"
                  >test.email0123@elyssi.com</a
                >
              </li>

              <li class="pb-2 block">
                <a
                  href="tel:0123234222"
                  class="font-hkregular text-white transition-colors hover:text-primary text-base tracking-wide"
                  >0123 234 222</a
                >
              </li>

              <li class="pb-2 block">
                <a
                  href="https://elyssi.tailwindmade.com"
                  class="font-hkregular text-white transition-colors hover:text-primary text-base tracking-wide"
                  >Elyssi</a
                >
              </li>
            </ul>
          </div>
          <div class="text-center py-16 lg:py-0">
            <a
              href="/"
              class="font-butlerregular text-white text-4xl uppercase tracking-wider"
              >Elyssi.</a
            >
            <div class="flex items-center justify-center pt-5">
              <a href="https://www.google.com" class="group">
                <span class="sr-only">Social link</span>
                <div
                  class="bg-white group-hover:bg-primary rounded-full px-2 py-2 flex items-center mr-5 transition-colors"
                >
                  <i
                    class="bx bxl-facebook text-secondary transition-colors group-hover:text-white"
                  ></i>
                </div>
              </a>

              <a href="https://www.google.com" class="group">
                <span class="sr-only">Social link</span>
                <div
                  class="bg-white group-hover:bg-primary rounded-full px-2 py-2 flex items-center mr-5 transition-colors"
                >
                  <i
                    class="bx bxl-twitter text-secondary transition-colors group-hover:text-white"
                  ></i>
                </div>
              </a>

              <a href="https://www.google.com" class="group">
                <span class="sr-only">Social link</span>
                <div
                  class="bg-white group-hover:bg-primary rounded-full px-2 py-2 flex items-center mr-5 transition-colors"
                >
                  <i
                    class="bx bxl-instagram text-secondary transition-colors group-hover:text-white"
                  ></i>
                </div>
              </a>

              <a href="https://www.google.com" class="group">
                <span class="sr-only">Social link</span>
                <div
                  class="bg-white group-hover:bg-primary rounded-full px-2 py-2 flex items-center mr-5 transition-colors"
                >
                  <i
                    class="bx bxl-pinterest text-secondary transition-colors group-hover:text-white"
                  ></i>
                </div>
              </a>
            </div>
          </div>
          <div class="text-center lg:text-left">
            <h4 class="font-hkbold text-white text-xl pb-8">Link</h4>
            <ul class="list-reset">
              <li class="pb-2 block">
                <a
                  href="/collection-list"
                  class="font-hkregular transition-colors text-white hover:text-primary text-base tracking-wide"
                  >Shop</a
                >
              </li>

              <li class="pb-2 block">
                <a
                  href="/contact"
                  class="font-hkregular transition-colors text-white hover:text-primary text-base tracking-wide"
                  >Contact Us</a
                >
              </li>

              <li class="pb-2 block">
                <a
                  href="/single"
                  class="font-hkregular transition-colors text-white hover:text-primary text-base tracking-wide"
                  >Terms & Conditions</a
                >
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="container py-8">
      <p class="font-hkregular text-secondary text-base text-center">
        All rights reserved © 2020 Tailwind Made.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      mobileMenu: false,
      subcategory: false,
      categories: false,
    }
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
        {
          rel: 'stylesheet',
          href: '/assets/styles/main.min.css',
          media: 'screen',
          crossorigin: 'anonymous',
        },
        {
          rel: 'stylesheet',
          href:
            'https://cdn.jsdelivr.net/npm/@glidejs/glide@3.4.1/dist/css/glide.core.min.css',
          integrity: 'sha256-Ev8y2mML/gGa4LFVZgNpMTjKwj34q4pC4DcseWeRb9w=',
          crossorigin: 'anonymous',
        },
        {
          rel: 'stylesheet',
          href:
            'https://cdn.jsdelivr.net/npm/@glidejs/glide@3.4.1/dist/css/glide.theme.min.css',
          integrity: 'sha256-sw/JiPOV1ZfcXjqBJT1vqaA4vBGeiqn+b7PDhVv4OA4=',
          crossorigin: 'anonymous',
        },
      ],
      script: [
        {
          src:
            'https://cdn.jsdelivr.net/npm/@glidejs/glide@3.4.1/dist/glide.min.js',
          integrity: 'sha256-CnNQJd80jPuIDyeQRRq7+Wgt+++Kl0dZLt4ETNmxMIw=',
          crossorigin: 'anonymous',
          defer: 'defer',
        },
        // {
        //   src: 'https://cdn.jsdelivr.net/npm/alpinejs@2.3.3/dist/alpine.min.js',
        //   defer: 'defer',
        // },
        // {
        //   src: '/assets/js/main.js',
        // },
      ],
    }
  },
}
</script>
