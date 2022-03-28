<template>
    <div>
        <div class="container mx-auto">
            <div class="flex justify-between py-5">
                <div class="flex items-center bg-white p-2 rounded-md">
                    <i class="fas fa-map-marker-alt text-bluee text-xl mx-2"></i>
                    <select name="" id="">
                        <option value="">Алматы</option>
                        <option value="">Астана</option>
                        <option value="">Павлодар</option>
                        <option value="">Актобе</option>
                    </select>
                </div>
                <div class="flex">
                    <div class="bg-orangee p-2 rounded-md flex items-center mr-3">
                        <i class="fas fa-phone text-yellou"></i>
                        <p class="mx-3 text-yellou">Горячая линия с 08:00 до 00:00</p>
                        <a class="text-xl" href="tel:1717">1717</a>
                        <!-- чел сможет позвонить по этой ссылке -->
                    </div>
                    <div class="flex items-center bg-white border border-gray-200 px-2 rounded-md">
                    <select name="" id="">
                        <option value="">РУС</option>
                        <option value="">КАЗ</option>
                    </select>
                </div>
                </div>
            </div> 
        </div>
        <div class="bg-white">
            <div class="w-3/5 flex justify-between mx-auto py-2 items-center">
                <div class="items-center text-center w-1/5">
                    <div class="w-full flex items-center mx-20">
                        <div><i class="fas fa-house text-xl"></i></div>
                        <div><img class="w-full" src="../assets/kz.svg" alt=""></div>
                    </div>
                    <div><a class="text-yellou" href="#">Все делаем с любовью</a></div>
                </div>
                <div class="w-40 bg-orangeee text-white font-bold flex items-center px-6 py-3 rounded-md mx-8">
                    <a class="mr-4" href="#"><i class="fas fa-bars"></i></a>
                    <p class="uppercase">каталог</p>
                </div>
                <div class="w-3/5"><input class="w-full mx-2 p-4 text-xl border border-orangeee rounded-md" type="text" placeholder="Я хочу найти..."></div>
                <i class="fas fa-search text-xl text-yellou relative right-14"></i>
                <div class="flex items-center">
                    <div class="text-center mx-4 ">
                        <a href="#"><i class="fas fa-heart text-black text-xl"></i>
                        <p class="text-yellou font-semibold">Избранное</p></a>
                    </div>
                    <div class="text-center mx-4">
                        <a href="#"><i class="fas fa-balance-scale-left text-black text-xl"></i>
                        <p class="text-yellou font-semibold">Сравнить</p></a>
                    </div>
                    <div class="text-center mx-4">
                        <a href="#"><i class="fas fa-shopping-cart text-black text-xl"></i>
                        <p class="text-yellou font-semibold">Корзина</p></a>
                    </div>
                    <div class="text-center mx-4">
                        <a href="#"><i class="fas fa-user text-black text-xl"></i>
                        <p class="text-yellou font-semibold">Вход</p></a>
                    </div>
                </div>
                <div>
                </div>
            </div> 
        </div>
        <!-- <i><b><s><u>gorilla</u></s></b></i> -->
    </div>
</template>

