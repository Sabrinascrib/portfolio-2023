<script>
  import sabrinaabroditext from "../images/sabrinaabroditext.png";
  import { append } from "svelte/internal";
</script>

<div class="flex flex-col  place-items-center pt-10">
  <img src={sabrinaabroditext} class="w-96" alt="my name" />

  <nav class="flex flex-row justify-between mt-10 px-20  w-[1000px]">
    <div class="">
      <a href="#">Home</a>
      <a href="#" class="ml-4">About</a>
    </div>

    <div class="">
      <a href="#" class="mr-4">Projects</a>
      <a href="#">Contact</a>
    </div>
  </nav>
</div>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700;800;900&display=swap");
  a {
    font-family: "Poppins", sans-serif;
  }
</style>
