<script setup>
const features = [
  {
    title: "Gentle & Painless Care",
    description:
      "We prioritize patient comfort with the latest technology and techniques.",
    icon: "bx:bxs-briefcase",
  },
  {
    title: "Experienced & Knowledgeable Team",
    description:
      "Our team of qualified dentists and hygienists are passionate about your oral health.",
    icon: "bx:bxs-window-alt",
  },
  {
    title: "Comprehensive Services",
    description:
      "We offer a wide range of services, from routine cleanings to dental implants. ",
    icon: "bx:bxs-data",
  },
  {
    title: "Convenient Scheduling Options",
    description:
      "We offer flexible appointment times to fit your busy schedule.",
    icon: "bx:bxs-bot",
  },
  {
    title: "Family-Friendly Environment",
    description:
      "We strive to make every visit enjoyable for the whole family.",
    icon: "bx:bxs-file-find",
  },
  {
    title: "Affordable Dental Care",
    description:
      "We work with most insurance plans and offer financing options..",
    icon: "bx:bxs-user",
  },
];
</script>

<template>
  <div class="py-20">
    <div class="mt-4">
    <h2 class="text-4xl lg:text-5xl text-sky-800 font-bold lg:tracking-tight">
      Why Choose [Your Dental Practice Name]?
    </h2>
    <p class="text-lg mt-4 text-sky-900">
      We are dedicated to providing exceptional dental care to patients of all ages. Here's what sets us apart:
    </p>
  </div>

  <div class="grid sm:grid-cols-2 md:grid-cols-3 mt-16 gap-16">
    <div v-for="item of features" class="flex gap-4 items-start">
      <div class="mt-1 bg-sky-400 rounded-full p-2 w-8 h-8 shrink-0">
        <Icon class="text-white" :name="item.icon" />
      </div>
      <div>
        <h3 class="font-semibold text-lg text-sky-800">{{ item.title }}</h3>
        <p class="text-slate-500 mt-2 leading-relaxed text-sky-900">
          {{ item.description }}
        </p>
      </div>
    </div>
  </div>
  </div>
</template>
