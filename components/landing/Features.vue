<script setup>
const features = [
  {
    title: "Retirement Planning",
    description:
      " Chart your course for a comfortable and fulfilling retirement.",
    icon: "bx:bxs-briefcase",
  },
  {
    title: "Investment Strategies",
    description:
      "Grow your wealth with diversified investment solutions.",
    icon: "bx:bxs-window-alt",
  },
  {
    title: "Risk Management",
    description:
      "Protect your financial security from unforeseen events.",
    icon: "bx:bxs-data",
  },
  {
    title: "Tax Planning",
    description:
      "Minimize your tax burden and maximize your returns.",
    icon: "bx:bxs-bot",
  },
  {
    title: "Estate Planning",
    description:
      "Safeguard your legacy for generations to come.",
    icon: "bx:bxs-file-find",
  },
  {
    title: "Education Funding",
    description:
      "Invest in your child's future with a customized education plan.",
    icon: "bx:bxs-user",
  },
];
</script>

<template>
  <div class="py-20">
    <div class="mt-4">
    <h2 class="text-4xl lg:text-5xl text-sky-800 font-bold lg:tracking-tight">
      Why Choose Us?
    </h2>
    <p class="text-lg mt-4 text-sky-900">
      We are dedicated to providing exceptional financial services. Here's what sets us apart:
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
