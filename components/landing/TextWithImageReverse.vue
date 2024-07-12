<template>
    <div class="grid lg:grid-cols-2 place-items-center py-10">
       <div class="ml-8 pb-4 md:p-4 block">
       <img
           class="rounded hover:opacity-70 transition smooth"
           src="~/assets/img/dentist-content02.jpg"
           alt="Starship starts the engine"
           loading="eager"
           format="jpg"
           width="600"
           height="600"
       />
       </div>

       <div>
       <h1 class="text-3xl md:text-5xl text-sky-800 font-bold lg:tracking-tight">
           Our Experts
       </h1>
       <p class="text-lg mt-4 text-sky-900 text-slate-600 max-w-xl">
            We understand that a healthy smile is essential for both your physical and emotional well-being. At [Your Dental Practice Name], we offer a comprehensive range of dental services in a comfortable and welcoming environment.
       </p>
       <div class="mt-6 flex flex-col sm:flex-row gap-3">
           <LandingLink
           href="#"
           target="_blank"
           rel="noopener"
           >Meet the Team</LandingLink
           >
       </div>
       </div>
   </div>
</template>