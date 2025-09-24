<script setup>
import UserIcon from './icons/IconUser.vue';
import SearchIcon from './icons/IconSearch.vue';
import CartIcon from './icons/IconShoppingCart.vue';
</script>


<template>
    <nav class="lg:px-25 box-border text-white w-full h-16 flex items-center justify-between">
        <a href="/" class="text-2xl font-bold">
            <img src="/logo.png" alt="Larq Logo" class="w-20 h-auto" />
        </a>

        <ul style="margin-left: 24px;" class="flex items-center gap-14">
            <li>
                <a href="/" class="text-white">
                    Home
                </a>
            </li>

            <li>
                <a href="/" class="text-white">
                    Blog
                </a>
            </li>

            <li>
                <a href="/" class="text-white">
                    About Us
                </a>
            </li>
            <li>
                <a href="/" class="text-white">
                    Affiliates
                </a>
            </li>
            <li>
                <a href="/" class="text-white">
                    Contact
                </a>
            </li>
        </ul>

        <div class="flex items-center gap-10">
            <button class="text-white">
                <SearchIcon />
            </button>

            <button class="text-white">
                <CartIcon />
            </button>
            <button class="text-white">
                <UserIcon />
            </button>
        </div>
    </nav>
</template>