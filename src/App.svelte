<h1 class="text-red-500 text-3xl text-center my-10 font-bold">Welcome!!</h1>
    <p class="text-center text-custom1 text-xl">Hello World custom color from tailwind.config.js</p>
    <button class="m-10 bg-blue-500 px-4 py-2 text-white rounded font-semibold hover:bg-blue-600 transition-colors duration-200 ease-in-out">Primary Button</button>
    <button class="my-btn">Primary Button</button>

    <!-- Grid layout -->
    <div class="container mx-auto mt-10">
        <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-4 text-center">
            <div class="bg-blue-300 py-4 text-white text-lg">01</div>
            <div class="bg-blue-300 py-4 text-white text-lg">02</div>
            <div class="bg-blue-300 py-4 text-white text-lg">03</div>
            <div class="bg-blue-300 py-4 text-white text-lg">04</div>
        </div>
    </div>

    <div class="grid grid-rows-4 gap-4 text-center mt-[100px]">
        <div class="bg-blue-300 py-4 text-white text-lg">01</div>
        <div class="bg-blue-300 py-4 text-white text-lg">02</div>
        <div class="bg-blue-300 py-4 text-white text-lg">03</div>
        <div class="bg-blue-300 py-4 text-white text-lg">04</div>
    </div>

    <div class="bg-blue-200 p-16 grid grid-cols-2 lg:grid-cols-4 grid-rows-4 gap-6">
        <div class="bg-blue-500 text-white text-center text-5xl py-4 rounded-lg">1</div>
        <div class="bg-blue-500 text-white text-center text-5xl py-4 rounded-lg">2</div>
        <div class="bg-blue-500 text-white text-center text-5xl py-4 rounded-lg">3</div>
        <div class="bg-blue-500 text-white text-center text-5xl py-4 rounded-lg">4</div>
        <div class="bg-blue-500 text-white text-center text-5xl py-4 rounded-lg">5</div>
        <div class="bg-blue-500 text-white text-center text-5xl py-4 rounded-lg">6</div>
        <div class="bg-blue-500 text-white text-center text-5xl py-4 rounded-lg">7</div>
        <div class="bg-blue-500 text-white text-center text-5xl py-4 rounded-lg">8</div>
        <div class="bg-blue-500 text-white text-center text-5xl py-4 rounded-lg">9</div>
        <div class="bg-blue-500 text-white text-center text-5xl py-4 rounded-lg">10</div>
        <div class="bg-blue-500 text-white text-center text-5xl py-4 rounded-lg col-span-2">11</div>
    </div>

    <!-- Grid auto columns -->
    <div class="grid grid-flow-col auto-cols mt-[100px] text-center">
        <div class="bg-blue-300 py-4 text-white text-lg">01</div>
        <div class="bg-blue-300 py-4 text-white text-lg">02</div>
        <div class="bg-blue-300 py-4 text-white text-lg">03</div>
    </div>