<template>
  <header class="header">
    <div class="header-group">
      <div class="flex items-center justify-between py-10">
        <div class="w-28 lg:w-36">
          <img class="w-full" src="../../assets/images/logo_white.png" alt="logo" />
        </div>

        <div class="flex">
          <button
            class="px-6 py-2 font-bold rounded-full text-white focus:outline-none"
          >
            Criar conta
          </button>

          <button
            class="px-6 py-2 font-bold bg-white rounded-full text-brand-main focus:outline-none ml-4"
          >
           Entrar
          </button>
        </div>
      </div>
      <div class="flex flex-col mt-28">
        <h1 class="text-4xl font-blck text-white">
          Tenha um feedback <br/>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed <br class="hidden lg:inline-block"/>
        </h1>
        <p class="text-lg font-medium text-white">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod <br class="hidden lg:inline-block"/>
        </p>
        <div class="mt-10">
          <buttom
           class="px-6 py-2 font-bold bg-white rounded-full text-brand"
          >
            Cria uma conta Grátis
          </buttom>

        </div>
      </div>
    </div>
  </header>
</template>

<style lang="postcss" scoped>
.header {
  @apply bg-brand-main w-full flex justify-center;
  height: 700px;
}

.header-group {
  @apply flex flex-col w-4/5 max-w-6xl;
}

@media (min-width: 640px) {
  .header-group {
    background-image:  url("../../assets/images/blue_ballons.svg");
    background-size:  628px;
    background-position: 90% 100%;
    background-repeat:  no-repeat;
  }
}
</style>
