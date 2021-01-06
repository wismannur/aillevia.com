<template>
  <div id="main">
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
  </div>
</template>

<script>
export default {
  data() {
    return {}
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
