<template>
  <div class="main overflow-x-hidden">
    <div class="container">
      <h1
        class="font-butlerregular py-3 text-secondary text-center text-3xl md:text-4xl lg:text-7xl"
      >
        Aillevia Collections
      </h1>

      <!-- BEGIN FILTER -->
      <div class="py-5 flex flex-col sm:flex-row justify-between items-center">
        <div class="flex items-center justify-center sm:justify-start">
          <i class="bx bxs-filter-alt text-primary text-xl"></i>
          <p
            class="font-hkregular text-secondary md:text-lg px-2 leading-none block"
          >
            Filter
          </p>
          <div class="flex items-center border border-grey-darker p-2 rounded">
            <a href="/collection-list"
              ><i
                class="bx bx-menu text-grey-darker hover:text-secondary-light text-xl leading-none block transition-colors"
              ></i
            ></a>
            <div class="w-px h-4 mx-2 bg-grey-darker"></div>
            <a href="/collection-grid"
              ><i
                class="bx bxs-grid text-grey-darker hover:text-secondary-light text-xl leading-none block transition-colors"
              ></i
            ></a>
          </div>
        </div>
        <div
          class="flex items-center justify-center sm:justify-end mt-6 sm:mt-0 w-76"
        >
          <p class="font-hkregular text-secondary md:text-lg mr-2 -mt-2">
            Sort by:
          </p>

          <select class="w-2/3 form-select pl-1 pr-3">
            <option value="0">Best Match</option>
            <option value="1">Price: Low - High</option>
            <option value="2">Price: High - Low</option>
          </select>
        </div>
      </div>
      <!-- END FILTER -->

      <!-- BEGIN LIST COLLECTION -->
      <div
        class="flex flex-wrap justify-between py-5 lg:pb-10 xl:pb-12 sm:-px-3 md:-mx-5"
      >
        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-v-green text-sm uppercase tracking-wide"
              >
                New
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">Cat eye</h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$75.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-v-blue text-sm uppercase tracking-wide"
              >
                trend
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">
                  Floral Chick
                </h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$50.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-primary-light text-sm uppercase tracking-wide"
              >
                25%
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">
                  Coffee Cream
                </h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$65.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-v-red text-sm uppercase tracking-wide"
              >
                Hot
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">
                  Black Blake
                </h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$115.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-v-green text-sm uppercase tracking-wide"
              >
                New
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">
                  Woody Blake
                </h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$110.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-v-blue text-sm uppercase tracking-wide"
              >
                Trend
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">
                  Party Blake
                </h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$130.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-primary-light text-sm uppercase tracking-wide"
              >
                25%
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">
                  Not Ballerina Blake
                </h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$115.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-v-red text-sm uppercase tracking-wide"
              >
                Hot
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">
                  Cocktail Vans
                </h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$33.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-v-green text-sm uppercase tracking-wide"
              >
                New
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">WW Vans</h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$35.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-v-blue text-sm uppercase tracking-wide"
              >
                trend
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">
                  Classic Beige
                </h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$30.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-primary-light text-sm uppercase tracking-wide"
              >
                25%
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">
                  Siberian Boots
                </h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$67.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-v-red text-sm uppercase tracking-wide"
              >
                Hot
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">
                  Submarine Watch
                </h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$120.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-v-green text-sm uppercase tracking-wide"
              >
                New
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">
                  Rose Gold Watch
                </h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$135.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-v-blue text-sm uppercase tracking-wide"
              >
                Trend
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">
                  Silver One Watch
                </h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$137.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-primary-light text-sm uppercase tracking-wide"
              >
                25%
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">
                  Princess
                </h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$145.0</span>
            </div>
          </div>
        </div>

        <div
          class="w-full sm:w-1/2 lg:w-1/3 xl:w-1/4 relative group pb-12 lg:last:hidden xl:last:block"
        >
          <div class="sm:px-3 md:px-5">
            <div class="relative rounded flex justify-center items-center">
              <div
                class="w-full h-68 bg-center bg-no-repeat bg-cover"
                style="background-image: url(/assets/img/backpack-1.png)"
              ></div>
              <span
                class="absolute top-0 right-0 bg-white px-5 py-1 mt-4 mr-4 rounded-full font-hkbold text-v-red text-sm uppercase tracking-wide"
              >
                Hot
              </span>
              <div
                class="absolute inset-0 bg-secondary opacity-0 group-hover:opacity-85 pointer-events-none group-hover:pointer-events-auto transition-all overflow-hidden rounded"
              ></div>
              <div
                class="absolute opacity-0 transition-opacity group-hover:opacity-100 flex justify-center items-center py-28 inset-0 group"
              >
                <a
                  href="/cart"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-cart.svg "
                    class="h-6 w-6"
                    alt="icon cart"
                  />
                </a>
                <a
                  href="/product"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all mr-3"
                >
                  <img
                    src="/assets/img/icons/icon-search.svg"
                    class="h-6 w-6"
                    alt="icon search"
                  />
                </a>
                <a
                  href="/account/wishlist/"
                  class="bg-white hover:bg-primary-light rounded-full px-3 py-3 flex items-center transition-all"
                >
                  <img
                    src="/assets/img/icons/icon-heart.svg"
                    class="h-6 w-6"
                    alt="icon heart"
                  />
                </a>
              </div>
            </div>
            <div class="flex justify-between items-center pt-6">
              <div>
                <h3 class="font-hkregular text-base text-secondary">
                  Silver One for Men
                </h3>
                <div class="flex items-center">
                  <div class="flex items-center">
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                    <i class="bx bxs-star text-primary"></i>
                  </div>
                  <p class="font-hkregular text-sm text-secondary ml-2">(45)</p>
                </div>
              </div>
              <span class="font-hkbold text-primary text-xl">$140.0</span>
            </div>
          </div>
        </div>
      </div>
      <!-- END LIST COLLECTIOn -->

      <div class="pb-16 flex justify-center mx-auto">
        <span
          class="font-hksemibold text-grey-darkest transition-colors hover:text-black pr-5 cursor-pointer"
          >Previous</span
        >
        <span
          class="font-hksemibold text-black transition-colors hover:text-white text-sm hover:bg-primary h-6 w-6 rounded-full flex items-center justify-center mr-3 cursor-pointer"
          >1</span
        >
        <span
          class="font-hksemibold text-black transition-colors hover:text-white text-sm hover:bg-primary h-6 w-6 rounded-full flex items-center justify-center mr-3 cursor-pointer"
          >2</span
        >
        <span
          class="font-hksemibold text-black transition-colors hover:text-white text-sm hover:bg-primary h-6 w-6 rounded-full flex items-center justify-center cursor-pointer"
          >3</span
        >
        <span
          class="font-hksemibold text-grey-darkest transition-colors hover:text-black pl-5 cursor-pointer"
          >Next</span
        >
      </div>
    </div>

    <KeepInTouch />
  </div>
</template>
