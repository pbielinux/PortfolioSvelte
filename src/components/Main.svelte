<script>

</script>

<main class="flex flex-col flex-1 p-4 min-h-screen">
    <section id="introPage" class="h-full grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14">
        <div class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10">
            <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
                Hi! I'm <span class="poppins text-violet-400">Pedro Bielik</span><br/>
                <span class="poppins text-violet-400">Developer</span>, Photographer<br/>
                & <span class="poppins text-violet-400">Video-Maker</span>
            </h2>
            <p class="text-base sm:text-lg md:text-xl">
                My <span class="text-violet-400"> favorite tech</span> includes JavaScript
                (NEXT.JS or SvelteKit), TailwindCSS, Node.js + Express.js & PostgreSQL
                or Firebase/Firestore!
            </p>
            <button
                class="blueShadow mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950"
            >
                <div
                    class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
                />
                <h4 class="relative z-9">Get in touch &rarr;</h4>
            </button>
        </div>
        <div class="relative shadow-2xl grid place-items-center lg:place-items-end">
            <img
                src={"images/profile.png"}
                alt="Pedro inside a toy castel ponting forward"
                class="object-cover z-[2] max-h-[70vh] lg:max-h-full lg:self-end"
            />
        </div>
    </section>
</main>