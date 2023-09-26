<template>
    <header class="bg-[#000000] px-[30px]">
        <nav class="flex justify-between items-center min-h-[74px]">
            <a class="block max-w-[100px]" href="#">
                <img src="/logo.png" alt="" class="w-full h-full object-cover">
            </a>
            <ul class="lg:flex hidden items-center space-x-14 text-white">
                <li class="group" :class="{ 'text-hover': activeLink == link }" v-for="(link, i) in links"
                    :key="`navLink${i}`">
                    <NuxtLink to="#" class="font-normal text-sm group-hover:text-hover transition-all duration-300">
                        {{ link }}
                    </NuxtLink>
                    <div :class="{ 'bg-black scale-y-100': activeLink == link }"
                        class="h-0.5 mt-0.5 group-hover:scale-y-100 group-hover:bg-black group-hover:block w-[80%] transition-all duration-300">
                    </div>
                </li>
            </ul>
            <ul class="flex items-center gap-x-6">
                <li>
                    <NuxtLink to="/">
                        <div class="w-10 h-10 p-[6px] group rounded-sm relative 
                        hover:bg-[#343a40] transition-colors">
                            <ShoppingBagIcon 
                            class="w-full h-full mx-auto text-white
                            group-hover:text-hover cursor-pointer transition-colors"/>
                            <span
                                class="absolute top-0 right-0 text-center w-[13px] h-[13px] leading-[14px] rounded-full bg-[#d92727] text-white text-[9px]">3</span>
                        </div>
                    </NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/">
                        <div class="w-10 h-10 p-[6px] group rounded-sm relative 
                        hover:bg-[#343a40] transition-colors">
                            <MagnifyingGlassIcon
                            class="w-full h-full mx-auto text-white
                          group-hover:text-hover cursor-pointer transition-colors" />
                        </div>
                    </NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/">
                        <div class="w-10 h-10 p-[6px] group rounded-sm relative 
                        hover:bg-[#343a40] transition-colors">
                        <UserCircleIcon
                            class="w-full h-full mx-auto text-white
                          group-hover:text-hover cursor-pointer transition-colors" />
                        </div>
                    </NuxtLink>
                </li>
            </ul>
        </nav>
    </header>
</template>
<script setup>

import { ShoppingBagIcon, MagnifyingGlassIcon, UserCircleIcon } from '@heroicons/vue/24/solid'

const links = ['Trang chủ', 'Sản phẩm mới', 'Product Views', 'Blog', 'Giới thiệu', 'Liên hệ'];

const activeLink = useState('activeLink', () => "Trang chủ");
</script>
<style></style>