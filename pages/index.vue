<template>
  <div>
    <!-- Landing page -->
    <section class="">
      <div class="container px-6 py-16 mx-auto">
        <div class="sm:items-center lg:items-start lg:flex">
          <div class="w-full lg:w-1/2">
            <div class="lg:max-w-lg pt-4">
              <h1
                class="text-3xl font-semibold text-gray-800 dark:text-white lg:text-4xl"
              >
                Platforma pro modely
              </h1>

              <p class="mt-3 text-gray-600 dark:text-gray-400">
                Tato stránka obsahuje projekty tří studentů, kteří společně vytvářejí <strong>3D modely bitevních lodí</strong>, které následně jsou tištěny na 3D tiskárnách.
              </p>
            </div>
          </div>

          <div
            class="flex items-center justify-center w-full mt-6 lg:mt-0 lg:w-1/2"
          >
            <img
              class="max-h-1/3"
              src="/img/landing_chart.svg"
              alt="World Network Ilustration"
            />
          </div>
        </div>
      </div>
    </section>

    <!-- HMS King George V -->
    <section class="" id="king-george">
      <h2
        class="text-center text-3xl font-semibold text-cyan-300 lg:text-4xl"
        id="kurzy"
      >
        HMS King George V
      </h2>
      <div class="container mx-auto">
        <div class="w-full  mt-6 lg:mt-0 flex justify-center items-center">
        <img
          class="w-3/4 h-auto max-w-3xl lg:w-full lg:h-auto lg:max-w-5xl"
          src="/img/king_george.png"
          alt="HMS King George V"
        />
      </div>
      </div>
    </section>

    <!-- About HMS King George V -->
    <section class="">
      <div class="container px-6 py-16 mx-auto">
        <div class="items-center lg:flex dark:bg-blue-800 p-6 rounded-lg">
          <div class="w-full lg:w-1/2 p-3">
            <div class="lg:max-w-lg">
              <h2
                class="text-3xl font-semibold text-gray-800 dark:text-white lg:text-4xl"
              >
                O projektu
              </h2>

              <p class="mt-3 text-gray-600 dark:text-gray-400">
                Tento model lodi byl tvořen v rámci Studentského projektu ve
                třetím ročníku. Nejprve jsme si zpracovali z dostupných náčrtů
                na internetu 2D nákresy. Na základě vlastních úprav jsme s
                využitím programu Fusion 360 přešli do 3D prostoru. Zde bylo
                nutné celý model připravit tak, aby byl tisknutelný na FDM
                tiskárně.
              </p>
              <p class="mt-3 text-gray-600 dark:text-gray-400">
                Celý model je složen z <strong>65 dílků</strong>, které jsou k sobě přilepeny.
                Nejdelší tisky trvaly okolo jednoho celého dne a bylo
                spotřebována přes <strong>500m</strong> PLA kabelu.
              </p>
            </div>
          </div>

          <div
            class="flex items-center justify-center w-full mt-6 lg:mt-0 lg:w-1/2"
          >
            <img
              class="w-full h-full lg:max-w-3xl"
              src="/img/learning_team.svg"
              alt="World Network Ilustration"
            />
          </div>
        </div>
      </div>
    </section>

    <!-- HMS Ark Royal -->
    <section class="" id="ark-royal">
      <h2
        class="text-center text-3xl font-semibold text-cyan-300 lg:text-4xl"
        id="kurzy"
      >
        HMS Ark Royal
      </h2>
      <!-- HSM Ark Royal GIF -->
      <div class="container mx-auto p-10 m-5">
        <div style="width:100%;height:0;padding-bottom:56%;position:relative;"><iframe src="https://giphy.com/embed/dLmEzHozhc9WbTkwPa" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
useSeoMeta({
  title: 'Sketchub.eu',
  ogTitle: 'Sketchub.eu',
  description: 'This site is about 3D models of historic battleships. We use Fusion 360 and Autodesk to create them.',
  ogDescription: 'This site is about 3D models of historic battleships. We use Fusion 360 and Autodesk to create them.',
})
</script>

D