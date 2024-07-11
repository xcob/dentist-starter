<template>
     <div class="grid lg:grid-cols-2 place-items-center py-20">
        <div class="p-0 pb-4 md:p-4 md:order-1 block">
        <img
            class="rounded"
            src="~/assets/img/dentist-content01.jpg"
            alt="Starship starts the engine"
            loading="eager"
            format="avif"
            width="512"
            height="512"
        />
        </div>

        <div>
        <h1 class="text-3xl md:text-6xl font-bold lg:tracking-tight">
            Marketing website done with Nuxt
        </h1>
        <p class="text-lg mt-4 text-slate-600 max-w-xl">
            Nuxtship is a starter template for startups, marketing websites &
            landing pages.<wbr /> Built with Nuxt & TailwindCSS. You can quickly
            create any website with this starter.
        </p>
        <div class="mt-6 flex flex-col sm:flex-row gap-3">
            <LandingLink
            href="#"
            target="_blank"
            rel="noopener"
            >Learn More</LandingLink
            >
        </div>
        </div>
    </div>
</template>