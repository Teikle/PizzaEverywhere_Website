<template>
    <footer>
        <section class="bg-[#000000] py-10">
            <div class="max-w-[1200px] w-full mx-auto px-[15px]">
                <div class="flex items-center justify-between">
                    <div class="text-white basis-1/2">
                        <h2 class="text-[31px] text-white font-lobster mb-[15px]">Đăng ký nhận tin</h2>
                        <p class="m-0 text-white">
                            Đăng ký email để nhận tin khuyến mãi mới nhất
                        </p>
                    </div>
                    <div class="basis-1/2">
                        <form action="/">
                            <div class="relative flex flex-wrap w-full mt-5">
                                <input type="text" placeholder="Vui lòng nhập email của bạn"
                                    class="appearance-none outline-none rounded-[30px] m-0 h-[45px] w-full text-[13px] border-none float-right py-[10px] pr-[110px] pl-[20px]">
                                <button
                                    class="absolute top-0 right-0 h-full float-left py-[10px] px-5 border-none bg-hover text-black text-[13px] rounded-tr-[30px] rounded-br-[30px]">Đăng
                                    ký</button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </section>
        <div class="bg-footer-img pt-10 pb-[30px]">
            <div class="max-w-[1200px] mx-auto px-[15px]">
                <div class="flex text-white">
                    <div class="mb-5 px-[15px] basis-1/3 max-w-[33.333%]">
                        <h4 class="font-lobster text-xl mb-5 leading-[30px] ">Giới thiệu</h4>
                        <div>
                            <p class="mb-[10px] leading-6">Thứ 3 hàng tuần - Ưu đãi Mua 1 Tặng 1 - ÁP DỤNG cho các dòng bánh
                                Pizza.</p>
                            <div class="mb-5">
                                <a href="/">
                                    <img src="/footer/logo_bct.webp" alt="" class="w-[150px]">
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="mb-5 px-[15px] basis-1/6">
                        <h4 class="font-lobster text-xl mb-5 leading-[30px] ">Liên kết</h4>
                        <div>
                            <ul>
                                <li class="block leading-7 pl-0">
                                    <a href="/" title="Tìm kiếm">Tìm kiếm</a>
                                </li>
                                <li class="block leading-7 pl-0">
                                    <a href="/" title="Tìm kiếm">Giới thiệu</a>
                                </li>
                                <li class="block leading-7 pl-0">
                                    <a href="/" title="Tìm kiếm">Chính sách đổi trả</a>
                                </li>
                                <li class="block leading-7 pl-0">
                                    <a href="/" title="Tìm kiếm">Chính sách bảo mật</a>
                                </li>
                                <li class="block leading-7 pl-0">
                                    <a href="/" title="Tìm kiếm">Điều khoản dịch vụ</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="mb-5 px-[15px] basis-1/4">
                        <h4 class="font-lobster text-xl mb-5 leading-[30px] ">Thông tin liên hệ</h4>
                        <div>
                            <ul class="mb-[15px] p-0">
                                <li class="flex items-center leading-[22px] pb-[5px]">
                                    <MapPinIcon class="mx-[10px] w-[45px]"/>
                                    <span>Tầng 4, tòa nhà Flemington, số 182, đường Lê Đại Hành, phường 15, quận 11, Tp. Hồ Chí Minh.</span>
                                </li>
                                <li class="flex items-center leading-[22px] pb-[5px]">
                                    <PhoneIcon class="mx-[10px] h-[17px]"/>
                                    <span>1900.636.099</span>
                                </li>
                                <li class="flex items-center leading-[22px] pb-[5px]">
                                    <DevicePhoneMobileIcon class="mx-[10px] h-[17px]"/>
                                    <span>1900.636.099</span>
                                </li>
                                <li class="flex items-center leading-[22px] pb-[5px]">
                                    <EnvelopeIcon class="mx-[10px] h-[17px]"/>
                                    <span>hi@haravan.com</span>
                                </li> 
                            </ul>
                        </div>
                    </div>
                    <div class="mb-5 px-[15px] basis-1/4">
                        <h4 class="font-lobster text-xl mb-5 leading-[30px] ">Fanpage</h4>
                        <div>
                            <div></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="py-5">
            <div class="max-w-[1200px] mx-auto">
                <p class="text-center">
                    Copyright © 2023 
                    <a href="#" class="hover:text-[#ffd661] transition-colors">
                        Pizza Everywhere
                    </a>
                    .
                    <a href="#" class="hover:text-[#ffd661] transition-colors">
                        Powered By Nhóm 3
                    </a>
                </p>
            </div>
        </div>
    </footer>
</template>
<script setup>
import { MapPinIcon, PhoneIcon, DevicePhoneMobileIcon, EnvelopeIcon } from '@heroicons/vue/24/outline'
</script>
<style></style>