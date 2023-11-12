<script>
  import web from './../public/web.svg'
  import left from './../public/left.svg'
  import right from './../public/right.svg'
  import lemon from './../public/lemon.svg'
  import Post from './../components/posts/card.svelte'

  import '../app.css'
</script>

<div class="flex flex-col gap-6 overflow-hidden">
  <div
    class="align-center mb-12 mt-6 flex w-full flex-col justify-center gap-12 pl-6 lg:mt-32 lg:gap-2 lg:pl-12"
  >
    <div class="flex flex-col items-start md:flex-row md:items-center md:gap-4">
      <img src={web} alt="web icon" />
      <h1 class="text-6xl font-extrabold">Allyson Rowe</h1>
    </div>

    <div
      class="flex flex-col items-start justify-start gap-6 pl-0 md:gap-12 md:pl-[111px] lg:flex-row lg:items-center lg:justify-start"
    >
      <div class="w-80 text-base font-bold text-neutral-600">
        Hello! I'm Allyson, I work as a freelance designer with close of two years in the
        programming and design world.
      </div>
      <div class="inline-flex flex-col items-start justify-start gap-2 font-bold">
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
    class="relative -left-4 inline-flex h-16 w-[110vw] -rotate-6 transform items-center justify-start gap-12 overflow-hidden bg-red-200 px-11 py-5 text-3xl font-bold text-red-400 selection:bg-red-700"
  >
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

  <div class="align-center flex justify-center py-24">
    <div class="flex w-[80%] flex-col items-start justify-start gap-2 font-bold lg:w-96">
      <div class="z-10">
        <p class="text-3xl font-extrabold">I’m a alchemist making crazy ideas</p>
        <p class="text-2xl">- Tali</p>
      </div>

      <img src={left} alt="left" class="absolute left-0 z-0 hidden lg:block" />
      <img src={right} alt="right" class="absolute right-0 z-0" />
    </div>
  </div>

  <div class="flex flex-col gap-12 pl-6 lg:pl-[calc(3rem+110px)]">
    <div class="inline-flex h-8 w-full items-center justify-start gap-2.5">
      <div class="text-3xl font-extrabold text-black">Fresh Stuff</div>
      <img class="h-8 w-8" src={lemon} alt="lemon" />
    </div>

    <div class="flex w-full flex-row flex-wrap gap-8 pl-8">
      <Post title="“Make Around”: Brand Identity" />
      <Post title="“Make Around”: Brand Identity" />
      <Post title="“Make Around”: Brand Identity" />
      <Post title="“Make Around”: Brand Identity" />
      <Post title="“Make Around”: Brand Identity" />
      <Post title="“Make Around”: Brand Identity" />
      <Post title="“Make Around”: Brand Identity" />
      <Post title="“Make Around”: Brand Identity" />
    </div>
  </div>
</div>
