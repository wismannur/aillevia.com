<template>
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
</template>
