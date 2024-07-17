<template>
    <div class="grid lg:grid-cols-2 place-items-center py-10">
       <div class="pb-4 md:p-4 block">
       <img
           class="rounded hover:opacity-70 transition smooth"
           src="~/assets/img/content-image02.jpg"
           alt="Starship starts the engine"
           loading="eager"
           format="jpg"
           width="600"
           height="600"
       />
       </div>

       <div>
       <h1 class="text-3xl md:text-5xl text-sky-800 font-bold lg:tracking-tight">
        Simplify Your Financial Journey
       </h1>
       <p class="text-lg mt-4 text-sky-900  max-w-xl">
        We take the complexity out of managing your finances, allowing you to focus on what matters most.
       </p>
       <div class="mt-6 flex flex-col sm:flex-row gap-3">
           <LandingLink
           href="#"
           target="_blank"
           rel="noopener"
           >Simplify Your Finances Today!</LandingLink
           >
       </div>
       </div>
   </div>
</template>