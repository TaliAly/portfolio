<script lang="ts">
  import Navbar from "../components/navbar/navbar.svelte";
  import "../app.css";
  import web from "./../public/web.svg";
  import left from "./../public/left.svg"
  import right from "./../public/right.svg"
</script>

<Navbar />

<div class="flex flex-col gap-6">
  <div class="flex flex-col pl-12 gap-2 my-32">
    <div class="flex items-center gap-4">
      <img src={web} alt="web icon" />
      <h1 class="text-6xl font-extrabold">Allyson Rowe</h1>
    </div>

    <div class="justify-start items-center gap-12 inline-flex pl-[111px] ">
      <div class="w-80 text-neutral-600 text-base font-bold">
        Hello! I'm Allyson, I work as a freelance designer with close of two years
        in the programming and design world.
      </div>
      <div class="flex-col justify-start items-start gap-2 inline-flex font-bold ">

        <div class="flex gap-2">
          <a class="underline" href="/about"> Wanna learn about me? </a>
          <p class="text-zinc-400">About me</p>
        </div>
        <div class="flex gap-2">
          <a class="underline" href="/about"> Explore my portfolio </a>
          <p class="text-zinc-400">Projects</p>
        </div>
        <div class="flex gap-2">
          <a class="underline" href="/about"> I want to create something</a>
          <p class="text-zinc-400">Services</p>
        </div>
      </div>
    </div>
  </div>

  <div
    class="w-full h-16 mt-6 px-11 py-5 bg-red-200 justify-start items-center gap-12 inline-flex text-red-400 font-bold  text-3xl overflow-hidden selection:bg-red-700">
    <p>Designer</p>
    <p>Developer</p>
    <p>Writter</p>
    <p>Designer</p>
    <p>Developer</p>
    <p>Writter</p>
    <p>Designer</p>
    <p>Developer</p>
    <p>Writter</p>
  </div>

  <div class="flex align-center justify-center py-24">
    <div class="flex w-96 flex-col justify-start items-start gap-2 font-bold ">

      <div class="z-10">
        <p class="text-3xl font-extrabold">I’m a alchemist making crazy ideas</p>
        <p class="text-2xl">- Tali</p>
      </div>

      <img src={left} alt="left" class="absolute left-0 z-0"/>
      <img src={right} alt="right" class="absolute right-0 z-0" />
    </div>
  </div>

</div>