

<template>
     <div class="grid lg:grid-cols-2 place-items-center py-10"  v-for="block of contentBlocks">
        <div :class="block.reverse == true ? 'p-0 pb-4 md:p-4 md:order-1 ' : 'p-0 pb-4 md:p-4 md:pr-10'">
        <img
            class="rounded hover:opacity-70 transition smooth"
            :src="block.image.src"
            :alt="block.image.alt"
            loading="eager"
            format="jpg"
            width="600"
            height="600"
        />
        </div>

        <div>
        <h1 class="text-3xl md:text-5xl text-sky-800 font-bold lg:tracking-tight">
            {{ block.headline }}
        </h1>
        <p class="text-lg mt-4 text-sky-900 text-slate-600 max-w-xl">
            {{ block.supportText }}
        </p>
        <div class="mt-6 flex flex-col sm:flex-row gap-3">
            <LandingLink
            href="{{ block.button.link }}"
            target="_blank"
            rel="noopener"
            >{{ block.button.text }}</LandingLink
            >
        </div>
        </div>
    </div>
</template>

<script  lang="ts">
export default {
  data() {
    return {
    contentBlocks: [
        {
            headline: "Empowering You to Make Informed Decisions",
            supportText: "With personalized strategies and ongoing support, we empower you to take control of your financial future.",
            image: {
                src: "/img/content-image01.jpg",
                alt: "two men working at a computer"
            },
            reverse: false,
            button: {
                text: "Explore Our Investment Strategies",
                link: "/",
            },
        },
        {
            headline: " Simplify Your Financial Journey",
            supportText: " We take the complexity out of managing your finances, allowing you to focus on what matters most.",
            image: {
                src: "/img/content-image02.jpg",
                alt: "man checking his phone and computers for stock information"
            },
            reverse: true, 
            button: {
                text: "Simplify Your Finances Today!",
                link: "/",
            },
        },
        {
            headline: "Peace of Mind Through Financial Security",
            supportText: " Let our experts manage your finances, so you can focus on achieving your life goals with peace of mind.",
            image: {
                src: "/img/content-image01.jpg",
                alt: ""
            },
            reverse: false, 
            button: {
                text: "Explore Our Services",
                link: "/",
            },
        }
        ]
    }
  }
}
</script>