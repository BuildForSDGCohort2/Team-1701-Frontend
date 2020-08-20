<template>
  <div class="home">
    <div class="container mx-auto flex flex-col md:flex-row items-center my-12 md:my-24">
      <!-- Left Col -->
      <div class="flex flex-col w-full lg:w-1/2 justify-center items-start pt-12 pb-24 px-6">
          <p class="uppercase tracking-loose">Tag Line</p>
          <h1 class="my-4">Welcome To Pecunia</h1>
          <p class="leading-normal mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam obcaecati sint magnam assumenda voluptates nisi earum aut officiis atque. Ipsam, optio! Repellat velit temporibus nemo doloremque porro quae placeat consectetur!</p>
          <button class="bg-transparent hover:bg-black text-black hover:text-white rounded shadow hover:shadow-lg py-2 px-4 border border-black hover:border-transparent">Create Account</button>
      </div>
      <!-- Right Col -->
      <div class="w-full lg:w-1/2 lg:py-6 text-center">
        <img class="object-contain h-40 w-full" src="undraw_wallet_aym5.svg">
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
  components: {

  }
}
</script>
