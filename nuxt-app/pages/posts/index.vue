<template>
    <div>
        <!-- <p class="dark:md:hover:bg-fuchsia-600">This is posts page</p> -->
        <form class="text-red-600 body-font">
            <div class="container px-5 py-24">
                <div class="lg:w-3/5 md:w-1/2">
                    <h1 class="text-gray-900">
                        Subscribe to my newsletter
                    </h1>
                    <p class="leading-relaxed mt-4">
                        I send out a weekly newsletter with tips and tricks for web
                        development.
                    </p>
                </div>
                <div class=" lg:w-2/6 md:w-1/2 bg-gray-100">
                    <button class="text-gray-900 text-lg font-medium title-font mb-5 rounded">
                        Subscribe
                    </button>

                    <div class="relative mb-4">
                        <label for="email" class="leading-7 text-sm text-gray-600">Email</label>
                        <input type="email" id="email" name="email" class="w-full bg-white " />
                    </div>
                    <button class="text-white p-x-10 py-3 bg-indigo-500 rounded">
                        Subscribe
                    </button>
                </div>
            </div>
        </form>
    </div>
</template>