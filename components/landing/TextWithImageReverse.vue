<template>
    <div class="grid lg:grid-cols-2 place-items-center py-10">
       <div class="p-0 pb-4 md:p-4 block">
       <img
           class="rounded"
           src="~/assets/img/dentist-content02.jpg"
           alt="Starship starts the engine"
           loading="eager"
           format="avif"
           width="512"
           height="512"
       />
       </div>

       <div>
       <h1 class="text-3xl md:text-5xl text-sky-800 font-bold lg:tracking-tight">
           Our Dental Practice
       </h1>
       <p class="text-lg mt-4 text-sky-900 text-slate-600 max-w-xl">
            We understand that a healthy smile is essential for both your physical and emotional well-being. At [Your Dental Practice Name], we offer a comprehensive range of dental services in a comfortable and welcoming environment.
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