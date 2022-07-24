<template>
<div>
  <div class="flex justify-between w-10/12 h-16 mx-auto my-10 border border-black">
    <nav class="self-center w-5/12">
      <ul class="flex">
        <li class="mr-8 text-white cursor-pointer">Portfolio</li>
        <li class="mr-8 text-white cursor-pointer">About Me</li>
        <li class="mr-8 text-white cursor-pointer">Get In Touch</li>
      </ul>
    </nav>
    <img src="./assets/hello-logo.png" class="self-center mx-auto w-14 h-14" />
    <div class="flex justify-end w-5/12 h-16">
      <div class="my-auto cursor-pointer ml-7">
        <img src="./assets/github.png" />
      </div>
      <div class="my-auto cursor-pointer ml-7">
        <img src="./assets/insta.png" />
      </div>
      <div class="my-auto cursor-pointer ml-7">
        <img src="./assets/twitter.png" />
      </div>
      <div class="my-auto cursor-pointer ml-7">
        <img src="./assets/linkedin.png" />
      </div>
    </div>
  </div>
  <header>
    <div class="w-10/12 mx-auto my-24 text-center">
      <h1 class="text-[3rem] font-medium text-white">Shred Flanders</h1>
      <h2 class="text-[3rem] text-green-400">Guitar Shredder</h2>
      <h3 class="text-[3rem] text-white">Web Developer</h3>
      <div class="mx-auto my-12">
        <img src="./assets/Shred Flanders.png" class="mx-auto border-4 border-green-400 w-6/6 h-96" />
      </div>
    </div>
  </header>
</div>
</template>

<script>

export default {
  name: 'App',
}

</script>


