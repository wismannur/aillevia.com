<template>
  <div class="shadow-xs">
    <div class="container relative">
      <div class="py-6 lg:py-8 z-50 relative">
        <div class="flex justify-between items-center">
          <div class="flex items-center lg:hidden">
            <div class="block lg:hidden">
              <i
                class="bx bx-menu text-primary text-4xl"
                @click="
                  mobileMenu = !mobileMenu
                  setHeaderTopFixed()
                "
              ></i>
            </div>

            <!-- <span
              class="cursor-pointer border-2 transition-all border-transparent hover:border-primary rounded-full p-2 sm:p-4 ml-2 sm:ml-3 md:ml-5 lg:mr-8 group"
              @click="mobileSearch = !mobileSearch"
            >
              <img
                src="https://d33wubrfki0l68.cloudfront.net/56f050a65973a419ab0f192614c9a3c7232604d1/4b447/assets/img/icons/icon-search.svg"
                class="w-5 sm:w-6 md:w-8 h-5 sm:h-6 md:h-8 block group-hover:hidden"
                alt="icon search"
              />
              <img
                src="https://d33wubrfki0l68.cloudfront.net/c129f8a9d735731b185257f43eb3fe5307d04286/e2915/assets/img/icons/icon-search-hover.svg"
                class="w-5 sm:w-6 md:w-8 h-5 sm:h-6 md:h-8 hidden group-hover:block"
                alt="icon search hover"
              />
            </span> -->

            <!-- <a
              href="/account/wishlist"
              class="border-2 transition-all border-transparent hover:border-primary rounded-full p-2 sm:p-4 group hidden lg:block"
            >
              <img
                src="https://d33wubrfki0l68.cloudfront.net/f7c995473e0c29c1578cd00a2b7baa1562456ad9/b584a/assets/img/icons/icon-heart.svg"
                class="w-5 sm:w-6 md:w-8 h-5 sm:h-6 md:h-8 block group-hover:hidden"
                alt="icon heart"
              />
              <img
                src="https://d33wubrfki0l68.cloudfront.net/4e661f3e86fa0f4bfaa2c1e10374406c8e048056/e025f/assets/img/icons/icon-heart-hover.svg"
                class="w-5 sm:w-6 md:w-8 h-5 sm:h-6 md:h-8 hidden group-hover:block"
                alt="icon heart hover"
              />
            </a> -->
          </div>
          <a class="text-base font-large text-lg px-3" href="/">
            AILLEVIA
            <!-- <img
              src="https://d33wubrfki0l68.cloudfront.net/23b5f665f19d2465fb9751d325b522bda9614e53/c3543/assets/img/logo-aillevia.svg"
              class="w-28 sm:w-48 h-auto"
              alt="logo"
            /> -->
          </a>
          <div class="flex items-center">
            <!-- <a
              href="/account/dashboard"
              class="border-2 transition-all border-transparent hover:border-primary rounded-full p-2 sm:p-4 group"
            >
              <img
                src="https://d33wubrfki0l68.cloudfront.net/f7d761469bf66852487412569632673f9d21d1f8/5e821/assets/img/icons/icon-user.svg"
                class="w-5 sm:w-6 md:w-8 h-5 sm:h-6 md:h-8 block group-hover:hidden"
                alt="icon user"
              />
              <img
                src="https://d33wubrfki0l68.cloudfront.net/813133414c7aa22b471f0e3efbe3ddfc3600d77e/3dc2c/assets/img/icons/icon-user-hover.svg"
                class="w-5 sm:w-6 md:w-8 h-5 sm:h-6 md:h-8 hidden group-hover:block"
                alt="icon user hover"
              />
            </a>

            <a
              href="/cart/index"
              class="hidden lg:block border-2 transition-all border-transparent hover:border-primary rounded-full p-2 sm:p-4 ml-2 sm:ml-3 md:ml-5 lg:ml-8 group"
            >
              <img
                src="https://d33wubrfki0l68.cloudfront.net/16f4de05841e1eea2fbe536d4053b73f0ad85baf/77013/assets/img/icons/icon-cart.svg"
                class="w-5 sm:w-6 md:w-8 h-5 sm:h-6 md:h-8 block group-hover:hidden"
                alt="icon cart"
              />
              <img
                src="https://d33wubrfki0l68.cloudfront.net/bcbeda5344e5934d7eaa7a3e7f6e86b78d79755b/6df24/assets/img/icons/icon-cart-hover.svg"
                class="w-5 sm:w-6 md:w-8 h-5 sm:h-6 md:h-8 hidden group-hover:block"
                alt="icon cart hover"
              />
            </a> -->

            <span
              class="block lg:hidden border-2 transition-all border-transparent hover:border-primary rounded-full p-2 sm:p-4 ml-2 sm:ml-3 md:ml-5 lg:ml-8 group"
              @click="
                mobileCart = !mobileCart
                setHeaderTopFixedCart()
              "
            >
              <img
                src="https://d33wubrfki0l68.cloudfront.net/16f4de05841e1eea2fbe536d4053b73f0ad85baf/77013/assets/img/icons/icon-cart.svg"
                class="w-5 sm:w-6 md:w-8 h-5 sm:h-6 md:h-8 block group-hover:hidden"
                alt="icon cart"
              />
              <img
                src="https://d33wubrfki0l68.cloudfront.net/bcbeda5344e5934d7eaa7a3e7f6e86b78d79755b/6df24/assets/img/icons/icon-cart-hover.svg"
                class="w-5 sm:w-6 md:w-8 h-5 sm:h-6 md:h-8 hidden group-hover:block"
                alt="icon cart hover"
              />
            </span>
          </div>
          <div class="justify-center hidden lg:flex">
            <ul class="list-reset flex items-center">
              <li class="mr-10">
                <a
                  href="/"
                  class="block text-lg font-hk hover:font-bold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
                  >Home</a
                >
              </li>

              <li class="mr-10">
                <a
                  href="/about"
                  class="block text-lg font-hk hover:font-bold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
                  >About</a
                >
              </li>

              <li class="mr-10 hidden lg:block group">
                <div
                  class="border-b-2 border-white transition-colors group-hover:border-primary flex items-center"
                >
                  <span
                    class="cursor-pointer text-lg font-hk group-hover:font-bold text-secondary group-hover:text-primary px-2 transition-all"
                    >Collections</span
                  >
                  <i
                    class="bx bx-chevron-down text-secondary group-hover:text-primary pl-2 px-2 transition-colors"
                  ></i>
                </div>
                <div
                  class="pt-10 absolute mt-10 top-0 left-0 right-0 z-50 w-3/5 mx-auto opacity-0 pointer-events-none group-hover:opacity-100 group-hover:pointer-events-auto"
                >
                  <div
                    class="transition-all flex bg-white shadow-lg p-8 rounded-b relative"
                  >
                    <div class="flex-1 relative z-20">
                      <h4 class="font-hkbold text-base text-secondary mb-2">
                        Man
                      </h4>
                      <ul>
                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Boots</a
                          >
                        </li>

                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Blutcher Boot</a
                          >
                        </li>

                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Chelsea Boot</a
                          >
                        </li>

                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Chukka Boot</a
                          >
                        </li>

                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Dress Boot</a
                          >
                        </li>

                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
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
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Accessories</a
                          >
                        </li>

                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Belts</a
                          >
                        </li>

                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Caps</a
                          >
                        </li>

                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Laces</a
                          >
                        </li>

                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
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
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Shoes</a
                          >
                        </li>

                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Derby Shoes</a
                          >
                        </li>

                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Belts</a
                          >
                        </li>

                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Caps</a
                          >
                        </li>

                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Laces</a
                          >
                        </li>

                        <li>
                          <a
                            href="/collections"
                            class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                            >Socks</a
                          >
                        </li>
                      </ul>
                    </div>

                    <!-- <div class="flex-1">
                      <div
                        class="z-0 bg-contain bg-right-bottom bg-no-repeat absolute inset-0"
                        :style="{
                          'background-image':
                            'url(/assets/img/bg-mega-menu.png)',
                        }"
                      ></div>
                    </div> -->
                  </div>
                </div>
              </li>

              <li class="mr-10">
                <a
                  href="/blog"
                  class="block text-lg font-hk hover:font-bold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
                  >Blog</a
                >
              </li>

              <li class="mr-10">
                <a
                  href="/contact#faq"
                  class="block text-lg font-hk hover:font-bold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
                  >FAQ</a
                >
              </li>

              <li class="mr-10">
                <a
                  href="/contact"
                  class="block text-lg font-hk hover:font-bold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
                  >Contact</a
                >
              </li>
            </ul>
          </div>
          <div class="hidden">
            <i
              class="bx bx-menu text-primary text-3xl"
              @click="mobileMenu = true"
            ></i>
          </div>
        </div>
        <!-- <div class="justify-center lg:pt-8 hidden lg:flex">
          <ul class="list-reset flex items-center">
            <li class="mr-10">
              <a
                href="/"
                class="block text-lg font-hk hover:font-bold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
                >Home</a
              >
            </li>

            <li class="mr-10">
              <a
                href="/about"
                class="block text-lg font-hk hover:font-bold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
                >About</a
              >
            </li>

            <li class="mr-10 hidden lg:block group">
              <div
                class="border-b-2 border-white transition-colors group-hover:border-primary flex items-center"
              >
                <span
                  class="cursor-pointer text-lg font-hk group-hover:font-bold text-secondary group-hover:text-primary px-2 transition-all"
                  >Collections</span
                >
                <i
                  class="bx bx-chevron-down text-secondary group-hover:text-primary pl-2 px-2 transition-colors"
                ></i>
              </div>
              <div
                class="pt-10 absolute mt-40 top-0 left-0 right-0 z-50 w-2/3 mx-auto opacity-0 pointer-events-none group-hover:opacity-100 group-hover:pointer-events-auto"
              >
                <div
                  class="transition-all flex bg-white shadow-lg p-8 rounded-b relative"
                >
                  <div class="flex-1 relative z-20">
                    <h4 class="font-hkbold text-base text-secondary mb-2">
                      Man
                    </h4>
                    <ul>
                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Boots</a
                        >
                      </li>

                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Blutcher Boot</a
                        >
                      </li>

                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Chelsea Boot</a
                        >
                      </li>

                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Chukka Boot</a
                        >
                      </li>

                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Dress Boot</a
                        >
                      </li>

                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
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
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Accessories</a
                        >
                      </li>

                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Belts</a
                        >
                      </li>

                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Caps</a
                        >
                      </li>

                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Laces</a
                        >
                      </li>

                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
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
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Shoes</a
                        >
                      </li>

                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Derby Shoes</a
                        >
                      </li>

                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Belts</a
                        >
                      </li>

                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Caps</a
                        >
                      </li>

                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Laces</a
                        >
                      </li>

                      <li>
                        <a
                          href="/collections"
                          class="text-sm font-hk text-secondary-lighter leading-loose border-b border-transparent hover:border-secondary-lighter"
                          >Socks</a
                        >
                      </li>
                    </ul>
                  </div>

                  <div class="flex-1">
                    <div
                      class="z-0 bg-contain bg-right-bottom bg-no-repeat absolute inset-0"
                      style="
                        background-image: url(/assets/img/bg-mega-menu.png);
                      "
                    ></div>
                  </div>
                </div>
              </div>
            </li>

            <li class="mr-10">
              <a
                href="/blog"
                class="block text-lg font-hk hover:font-bold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
                >Blog</a
              >
            </li>

            <li class="mr-10">
              <a
                href="/contact#faq"
                class="block text-lg font-hk hover:font-bold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
                >FAQ</a
              >
            </li>

            <li class="mr-10">
              <a
                href="/contact"
                class="block text-lg font-hk hover:font-bold transition-all text-secondary hover:text-primary border-b-2 border-white hover:border-primary px-2"
                >Contact</a
              >
            </li>
          </ul>
        </div> -->
      </div>
    </div>
    <div
      class="fixed inset-x-0 pt-20 md:top-28 z-50 transition-all lg:hidden overflow-y-auto h-full"
      :class="
        mobileMenu
          ? 'opacity-100 pointer-events-auto'
          : 'opacity-0 pointer-events-none'
      "
    >
      <div
        class="w-full pb-20 sm:w-1/2 absolute left-0 top-0 px-6 z-40 bg-white shadow-sm"
      >
        <a
          href="/"
          class="w-full py-3 cursor-pointer font-hk font-medium text-secondary border-b border-grey-dark block"
          >Home
        </a>
        <a
          href="/account/wishlist"
          class="w-full py-3 cursor-pointer font-hk font-medium text-secondary border-b border-grey-dark block"
          >Wishlist
        </a>
        <div
          class="w-full py-3 border-b border-grey-dark block"
          x-data="{
          isParentAccordionOpen: false
      }"
        >
          <div
            class="flex items-center justify-between"
            @click="isParentAccordionOpen = !isParentAccordionOpen"
          >
            <span
              class="font-hk font-medium block transition-colors"
              :class="isParentAccordionOpen ? 'text-primary' : 'text-secondary'"
              >Collections</span
            >
            <i
              class="bx text-secondary text-xl"
              :class="
                isParentAccordionOpen ? 'bx-chevron-down' : 'bx-chevron-left'
              "
            ></i>
          </div>
          <div
            class="transition-all"
            :class="
              isParentAccordionOpen
                ? 'max-h-infinite'
                : 'max-h-0 overflow-hidden'
            "
          >
            <div
              x-data="{
              isAccordionOpen: false
          }"
            >
              <div
                class="flex items-center pt-3"
                @click="isAccordionOpen = !isAccordionOpen"
              >
                <i
                  class="bx text-xl pr-3 transition-colors"
                  :class="
                    isAccordionOpen
                      ? 'bx-chevron-down text-secondary'
                      : 'bx-chevron-right text-grey-darkest'
                  "
                ></i>
                <a
                  href="/collections.html"
                  class="font-hk font-medium transition-colors"
                  :class="
                    isAccordionOpen ? 'text-primary' : 'text-grey-darkest'
                  "
                  >Men's Fashion</a
                >
              </div>
              <div
                class="pl-12 transition-all"
                :class="
                  isAccordionOpen ? 'max-h-infinite' : 'max-h-0 overflow-hidden'
                "
              >
                <a
                  href="/collections"
                  class="font-hk font-medium text-secondary block mt-2"
                  >T-Shirts</a
                >
                <a
                  href="/collections"
                  class="font-hk font-medium text-secondary block mt-2"
                  >Shirts</a
                >
                <a
                  href="/collections"
                  class="font-hk font-medium text-secondary block mt-2"
                  >Men’s Bags</a
                >
                <a
                  href="/collections"
                  class="font-hk font-medium text-secondary block mt-2"
                  >Travel Essentials</a
                >
              </div>
            </div>
            <div class="flex items-center pt-3">
              <i class="bx bx-chevron-right text-grey-darkest text-xl pr-3"></i>
              <a
                href="/collections"
                class="font-hk font-medium text-grey-darkest"
                >Women's Fashion</a
              >
            </div>
            <div class="flex items-center pt-3">
              <i class="bx bx-chevron-right text-grey-darkest text-xl pr-3"></i>
              <a
                href="/collections"
                class="font-hk font-medium text-grey-darkest"
                >Baggage</a
              >
            </div>
            <div class="flex items-center pt-3">
              <i class="bx bx-chevron-right text-grey-darkest text-xl pr-3"></i>
              <a
                href="/collections"
                class="font-hk font-medium text-grey-darkest"
                >Camp</a
              >
            </div>
            <div class="flex items-center pt-3">
              <i class="bx bx-chevron-right text-grey-darkest text-xl pr-3"></i>
              <a
                href="/collections"
                class="font-hk font-medium text-grey-darkest"
                >Personal Care</a
              >
            </div>
            <div class="flex items-center pt-3">
              <i class="bx bx-chevron-right text-grey-darkest text-xl pr-3"></i>
              <a
                href="/collections"
                class="font-hk font-medium text-grey-darkest"
                >Backpacks</a
              >
            </div>
            <div class="flex items-center pt-3">
              <i class="bx bx-chevron-right text-grey-darkest text-xl pr-3"></i>
              <a
                href="/collections"
                class="font-hk font-medium text-grey-darkest"
                >Pullovers</a
              >
            </div>
          </div>
        </div>
        <a
          href="/about"
          class="w-full py-3 cursor-pointer font-hk font-medium text-secondary border-b border-grey-dark block"
          >About
        </a>
        <a
          href="/contact#faq"
          class="w-full py-3 cursor-pointer font-hk font-medium text-secondary border-b border-grey-dark block"
          >FAQ
        </a>
        <a
          href="/contact"
          class="w-full py-3 cursor-pointer font-hk font-medium text-secondary border-b border-grey-dark block"
          >Contact
        </a>
        <div class="mt-5 mb-8 h-auto flex flex-col">
          <a
            href="/login"
            aria-label="Login button"
            class="button button-primary bg-primary text-white w-full mb-4"
            >Login Account</a
          >
          <a
            href="/register"
            class="font-hk text-secondary md:text-lg pl-3 underline text-center block"
            >Create your account</a
          >
        </div>
      </div>
    </div>
    <div
      class="block lg:hidden absolute inset-x-0 z-50"
      :class="
        mobileSearch
          ? 'opacity-100 pointer-events-auto'
          : 'opacity-0 pointer-events-none'
      "
    >
      <div
        class="w-full sm:w-1/2 absolute left-0 top-0 px-6 py-6 z-10 bg-white shadow-sm rounded"
      >
        <form
          class="border border-grey-dark px-4 py-3 rounded-md flex items-center"
        >
          <button class="flex items-center">
            <i
              class="bx bx-search text-grey-darker text-xl pr-4 focus:outline-none"
            ></i>
          </button>
          <input
            type="text"
            name="search"
            class="font-hk font-medium text-secondary outline-none border-grey-dark w-full placeholder-grey-darkest"
            placeholder="Search for Products"
          />
        </form>
      </div>
    </div>
    <div
      class="absolute inset-x-0 z-50 transition-all h-full overflow-y-auto"
      :class="
        mobileCart
          ? 'opacity-100 pointer-events-auto'
          : 'opacity-0 pointer-events-none'
      "
    >
      <div
        class="w-full sm:w-1/2 absolute right-0 top-0 px-6 pt-6 pb-40 z-10 bg-white shadow-sm rounded"
      >
        <div
          class="flex justify-between items-center border-b border-grey-dark pb-2"
        >
          <div class="flex items-center">
            <i
              class="bx bx-x text-grey-darkest text-2xl sm:text-3xl mr-2 cursor-pointer"
            ></i>
            <div
              class="w-20 mx-0 h-20 rounded flex items-center justify-center"
            >
              <div
                class="w-16 h-16 mx-auto bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
            </div>
            <div class="pl-2">
              <span class="font-hk text-grey-darkest text-base block"
                >Winter Bag</span
              >
              <span class="font-hk text-secondary text-base mt-2">$19</span>
            </div>
          </div>
          <div class="flex pl-3 items-center">
            <span
              class="border border-primary rounded-full h-6 w-6 flex items-center justify-center"
              ><i class="bx bx-minus text-primary"></i
            ></span>
            <span class="font-hkbold text-primary text-lg block px-2">1</span>
            <span
              class="border border-primary rounded-full h-6 w-6 flex items-center justify-center"
              ><i class="bx bx-plus text-primary"></i
            ></span>
          </div>
        </div>
        <div
          class="flex justify-between items-center border-b border-grey-dark pb-2"
        >
          <div class="flex items-center">
            <i
              class="bx bx-x text-grey-darkest text-2xl sm:text-3xl mr-2 cursor-pointer"
            ></i>
            <div
              class="w-20 mx-0 h-20 rounded flex items-center justify-center"
            >
              <div
                class="w-16 h-16 mx-auto bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
            </div>
            <div class="pl-2">
              <span class="font-hk text-grey-darkest text-base block"
                >Winter Bag</span
              >
              <span class="font-hk text-secondary text-base mt-2">$19</span>
            </div>
          </div>
          <div class="flex pl-3 items-center">
            <span
              class="border border-primary rounded-full h-6 w-6 flex items-center justify-center"
              ><i class="bx bx-minus text-primary"></i
            ></span>
            <span class="font-hkbold text-primary text-lg block px-2">1</span>
            <span
              class="border border-primary rounded-full h-6 w-6 flex items-center justify-center"
              ><i class="bx bx-plus text-primary"></i
            ></span>
          </div>
        </div>
        <div class="flex justify-between pt-4">
          <span class="font-hkbold text-secondary text-lg">Total</span>
          <span class="font-hkbold text-secondary text-lg">$38</span>
        </div>
        <button
          type="submit"
          class="button button-primary bg-primary text-white w-full mt-5"
          aria-label="Checkout button"
        >
          Checkout
        </button>
        <a
          href="/cart"
          class="font-hk text-secondary md:text-lg pl-3 underline text-center block mt-4"
          >Go to cart page</a
        >
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      modal: false,
      mobileMenu: false,
      categories: false,
      subcategory: false,
      mobileCart: false,
      mobileSearch: false,
      isAccordionOpen: false,
      isParentAccordionOpen: false,
    }
  },
  methods: {
    setHeaderTopFixed() {
      this.mobileMenu
        ? this.setHeaderTopFixedAdd()
        : this.setHeaderTopFixedRemove()
    },
    setHeaderTopFixedCart() {
      this.mobileCart
        ? this.setHeaderTopFixedAdd()
        : this.setHeaderTopFixedRemove()
    },
    setHeaderTopFixedAdd() {
      document.getElementsByTagName('body')[0].classList.add('overflow-hidden')
      document.getElementsByTagName('body')[0].classList.add('max-h-screen')
    },
    setHeaderTopFixedRemove() {
      document
        .getElementsByTagName('body')[0]
        .classList.remove('overflow-hidden')
      document.getElementsByTagName('body')[0].classList.remove('max-h-screen')
    },
  },
}
</script>
