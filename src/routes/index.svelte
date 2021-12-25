<svelte:head>
    <title>Joseph Portfolio</title>
</svelte:head>

<main
    class="dark:bg-gray-800 font-mono bg-white relative overflow-hidden h-screen"
>
    <iframe
        src="https://my.spline.design/untitled-58a290228d86bb7ca90e8ae1618cd39a/"
        frameborder="0"
        width="100%"
        height="100%"
        class="absolute h-full w-full object-cover"
        title="spline"
    />
    <header class="h-24 sm:h-32 flex items-center z-30 w-full">
        <div class="container mx-auto px-6 flex items-center justify-between">
            <div
                class="uppercase text-gray-800 dark:text-white font-black text-3xl flex items-center"
            />
            <div class="flex items-center">
                <nav
                    class="font-sen text-gray-800 dark:text-white uppercase text-lg lg:flex items-center hidden"
                >
                    <button class="lg:hidden flex flex-col ml-4">
                        <span class="w-6 h-1 bg-gray-800 dark:bg-white mb-1" />
                        <span class="w-6 h-1 bg-gray-800 dark:bg-white mb-1" />
                        <span class="w-6 h-1 bg-gray-800 dark:bg-white mb-1" />
                    </button>
                </nav>
            </div>
        </div>
    </header>
    <div class="flex relative z-20 items-center">
        <div
            class="container mx-auto px-6 flex flex-col justify-between items-center relative py-4"
        >
            <div class="flex flex-col">
                <h2
                    class="float-right max-w-5xl text-xl md:text-xl font-bold mx-auto dark:text-white text-white text-center py-2 animate-pulse"
                >
                    Drag to rotate and use mouse wheel to zoom in & out
                </h2>
            </div>
        </div>
    </div>
</main>
