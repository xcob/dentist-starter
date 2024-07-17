<script setup lang="ts">
interface Props {
  augments: string;
  augmentName: "reverse" | "normal"
}

const augments = {
    reverse: "md:order-1",
    normal: ""
}
</script>

<template>
     <div class="grid lg:grid-cols-2 place-items-center py-10">
        <div :class="[
            'p-0 pb-4 md:p-4 block md:order-1',
           // augments[augmentName]
            ]">
        <img
            class="rounded hover:opacity-70 transition smooth"
            src="~/assets/img/content-image01.jpg"
            alt="Dentist Office Layout"
            loading="eager"
            format="jpg"
           width="600"
           height="600"
        />
        </div>

        <div>
        <h1 class="text-3xl md:text-5xl text-sky-800 font-bold lg:tracking-tight">
            Empowering You to Make Informed Decisions
        </h1>
        <p class="text-lg mt-4 text-sky-900 text-slate-600 max-w-xl">
            With personalized strategies and ongoing support, we empower you to take control of your financial future.
        </p>
        <div class="mt-6 flex flex-col sm:flex-row gap-3">
            <LandingLink
            href="#"
            target="_blank"
            rel="noopener"
            >Explore Our Investment Strategies</LandingLink
            >
        </div>
        </div>
    </div>
</template>