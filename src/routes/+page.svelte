<script lang="ts">
  import "../app.css";
  import web from "./../public/web.svg";
  import left from "./../public/left.svg";
  import right from "./../public/right.svg";
  import lemon from "./../public/lemon.svg";

  import Post from "./../components/posts/card.svelte";
</script>

<div class="flex flex-col gap-6 overflow-hidden">

  <div class="w-full flex flex-col pl-6 lg:pl-12 gap-12 lg:gap-2 mt-6 lg:mt-32 mb-12 justify-center align-center">
    <div class="flex flex-col items-start md:flex-row md:items-center md:gap-4">
      <img src={web} alt="web icon" />
      <h1 class="text-6xl font-extrabold">Allyson Rowe</h1>
    </div>

    <div class="flex flex-col pl-0 justify-start items-start gap-6 md:gap-12 lg:justify-start lg:items-center lg:flex-row md:pl-[111px]">
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
    class="w-[110vw] h-16 px-11 py-5 bg-red-200 justify-start items-center gap-12 inline-flex text-red-400 font-bold text-3xl overflow-hidden selection:bg-red-700 transform -rotate-6 -left-4 relative">
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
    <div class="flex w-[80%] lg:w-96 flex-col justify-start items-start gap-2 font-bold ">

      <div class="z-10">
        <p class="text-3xl font-extrabold">I’m a alchemist making crazy ideas</p>
        <p class="text-2xl">- Tali</p>
      </div>

      <img src={left} alt="left" class="absolute left-0 z-0 hidden lg:block"/>
      <img src={right} alt="right" class="absolute right-0 z-0" />
    </div>
  </div>

  <div class="pl-6 lg:pl-[calc(3rem+110px)] flex flex-col gap-12">
    <div class="w-full h-8 justify-start items-center gap-2.5 inline-flex">
      <div class="text-black text-3xl font-extrabold">Fresh Stuff</div>
      <img class="w-8 h-8" src={lemon} alt="lemon" />
    </div>

    <div class="flex pl-8 flex-row w-full flex-wrap gap-8">
      <Post title="“Make Around”: Brand Identity"/>
      <Post title="“Make Around”: Brand Identity"/>
      <Post title="“Make Around”: Brand Identity"/>
      <Post title="“Make Around”: Brand Identity"/>
      <Post title="“Make Around”: Brand Identity"/>
      <Post title="“Make Around”: Brand Identity"/>
      <Post title="“Make Around”: Brand Identity"/>
      <Post title="“Make Around”: Brand Identity"/>
    </div>
  </div>

</div>