<template>
    <div class="flex items-center sticky pin-t py-3 px-6 w-full bg-gray-900">
        <div class="flex">
            <div class="flex items-center mr-6">
                <a href="#" @click.prevent="$router.go(-1)" class="mr-6 text-gray-200 no-underline hover:text-white">
                    <i class="fas fa-chevron-left"></i>
                </a>

                <a href="#" @click.prevent="$router.go(1)" class="mr-6 text-gray-200 no-underline hover:text-white">
                    <i class="fas fa-chevron-right"></i>
                </a>
            </div>

            <div class="bg-white rounded-full px-2 flex items-center overflow-hidden">
                <i class="fas fa-search mr-2 text-gray-800"></i>

                <input type="text" class="py-1 text-sm text-black outline-none" placeholder="Search">
            </div>
        </div>
    </div>
</template>