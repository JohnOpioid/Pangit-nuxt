<script>

</script>
<template>
    <section>
            <div class="w-full h-full mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">

                <div class="p-5 w-full flex flex-col space-y-2 border-2 border-stone-600 lg:flex-row lg:space-y-0 lg:space-x-5">
                    <a href="https://pangit.netlify.app/_nuxt/assets/img/screen1.webp" class="flex-1 lg:min-w-[600px]" data-fancybox="gallery">
                    <img class="shadow w-full h-full object-cover" src="../assets/img/screen1.webp" />
                    </a> 
                    <div class="flex flex-nowrap space-x-2 lg:space-x-0 lg:grid lg:gap-5 lg:grid-cols-2 lg:grid-cols-2 items-start justify-start overflow-x-auto overflow-y-hidden">
                        <a href="~/assets/img/screen2.webp" class="bg-cover shadow min-w-[140px] h-[70px] md:w-full md:h-full md:max-h-[80px] lg:h-full lg:max-h-none" data-fancybox="gallery"><img class="w-full h-full object-cover" src="../assets/img/screen2.webp" /></a>
                        <a href="https://pangit.netlify.app/_nuxt/assets/img/screen3.webp" class="bg-cover shadow min-w-[140px] h-[70px] md:w-full md:h-full md:max-h-[80px] lg:h-full lg:max-h-none" data-fancybox="gallery"><img class="w-full h-full object-cover" src="../assets/img/screen3.webp" /></a>
                        <a href="https://pangit.netlify.app/_nuxt/assets/img/screen4.webp" class="bg-cover shadow min-w-[140px] h-[70px] md:w-full md:h-full md:max-h-[80px] lg:h-full lg:max-h-none" data-fancybox="gallery"><img class="w-full h-full object-cover" src="../assets/img/screen4.webp" /></a>
                        <a href="https://pangit.netlify.app/_nuxt/assets/img/screen5.webp" class="bg-cover shadow min-w-[140px] h-[70px] md:w-full md:h-full md:max-h-[80px] lg:h-full lg:max-h-none" data-fancybox="gallery"><img class="w-full h-full object-cover" src="../assets/img/screen5.webp" /></a>
                    </div>
                </div> 

                <div class="w-full py-7">
                    <img class="w-full h-full" src="../assets/img/divide.svg" />
                </div>

                <div class="w-full py-5 scroll-mt-11" id="shops">
                    <div class="flex ml-3 items-end uppercase text-xl text-yellow-300 font-bold before:font-black before:inline-block align-bottom before:content-['Платформы'] before:align-baseline  before:absolute before:text-4xl before:text-yellow-600 before:opacity-15 before:-ml-3">Платформы</div>
                    <div class="grid grid-cols-1 gap-5 md:grid-cols-2 mt-5">
                        <div class="flex justify-between items-center border-2 border-stone-600 w-full p-5 before:font-black before:inline-block align-bottom before:content-['Уже'] before:align-baseline  before:absolute before:text-7xl before:text-yellow-600 before:opacity-15 before:ml-10 before:pb-5">
                            <div class="flex flex-1 items-center">
                                <img class="w-10 h-10" src="../assets/img/vkplay.svg" />
                                <div class="text-orange-100 ml-3">
                                    Магазин <div class="text-xl">VKPlay</div>
                                </div>
                            </div>
                            <router-link to="https://vkplay.ru/play/game/pangit/" target="_blank" class="relative flex font-bold items-center uppercase h-[36px] bg-yellow-300 text-yellow-900 text-sm px-5 py-1 hover:bg-yellow-400">
                                Перейти
                            </router-link>
                        </div>
                        <div class="flex justify-between items-center border-2 border-stone-600 w-full p-5 before:font-black before:inline-block align-bottom before:content-['Скоро'] before:align-baseline  before:absolute before:text-7xl before:text-yellow-600 before:opacity-15 before:ml-10 before:pb-5">
                            <div class="flex flex-1 items-center">
                                <img class="w-10 h-10" src="../assets/img/steam.svg" />
                                <div class="text-orange-100 ml-3">
                                    Магазин <div class="text-xl">Steam</div>
                                </div>
                            </div>
                            <router-link to="#" class="relative flex font-bold items-center uppercase h-[36px] bg-yellow-950 text-yellow-900 text-sm px-5 py-1 cursor-not-allowed">
                                Не достуно
                            </router-link>
                        </div>
                    </div>
                    <div class="text-center py-2 text-orange-100 opacity-50">Игра находится в стадии разработки. Вы можете подписаться на новости игры в магазинах</div>
                </div>

                <div class="w-full py-5 scroll-mt-11" id="about">
                    <div class="flex ml-3 items-end uppercase text-xl text-yellow-300 font-bold before:font-black before:inline-block align-bottom before:content-['Об_игре'] before:align-baseline  before:absolute before:text-3xl before:text-yellow-600 before:opacity-15 before:-ml-3">Об игре</div>
                    <p class="leading-tight text-justify text-orange-100 indent-8 py-2 leading-7">
                    В недалеком будущем открытие свойства в минерале <span class="text-yellow-300">Пангит</span> изменило все. Ученые обнаружили, что в нем содержится цифровой код, позволяющий получить ответ на вопрос о происхождении космоса. Многие корпорации заинтересовались этим минералом, и инвестиции в его поиск стали приоритетом. ЧВК занимаются контрабандой, корпорации стремятся к коммерческой выгоде, а научные центры ищут открытия.
                    </p> 
                    <p class="leading-tight text-justify text-orange-100 indent-8 py-2 leading-7">
                    Главный герой представитель корпорации «ИНКОПРОД», которая выкупает базу J147 отвечающая за исследование и добычу <span class="text-yellow-300">Пангита</span>. Наш герой отправляется на остров с проверкой раньше на неделю до своего руководства, с задачей переключить сеть острова на новый сервер корпорации, там он выясняет что на острове полно ЧВК, а база еще не достроена.
                    </p> 
                    <p class="leading-tight text-justify text-orange-100 indent-8 py-2 leading-7">
                    Благодаря своему опыту и знаниям, военной подготовки, главному герою предстоит решить множество различных задач, чтобы помочь местному населению до приезда своего руководства.
                    </p>
                    <p class="leading-tight text-justify text-orange-100 indent-8 py-2 leading-7">
                    В эпоху господствующих в мире корпораций, высшие чины не приемлют провалов и за малейшие проступки увольняют, а это означает гибель человека без средств существования. Главный герой проникается симпатией к местному населению и пытается помочь решить множество задач до приезда руководства, которое пока по неизвестным причинам задерживается.
                    </p>
                </div>

                <div class="w-full py-5">
                    <div class="flex ml-3 items-end uppercase text-xl text-yellow-300 font-bold before:font-black before:inline-block align-bottom before:content-['Особенности'] before:align-baseline  before:absolute before:text-3xl before:text-yellow-600 before:opacity-15 before:-ml-3">Особенности</div>
                    <div class="grid grid-cols-1 gap-5 md:grid-cols-2 xl:grid-cols-4 mt-5">
                        <div class="bg-stone-800/30 border-2 border-stone-600 p-5 flex flex-col items-center text-center">
                        <img class="w-[48px] h-[48px]" src="../assets/img/1.svg" />
                        <p class="text-orange-100 mt-3">Поручите жителям вашего поселения добывать ресурсы</p> 
                        </div>

                        <div class="bg-stone-800/30 border-2 border-stone-600 p-5 flex flex-col items-center text-center">
                        <img class="w-[48px] h-[48px]" src="../assets/img/2.svg" />
                        <p class="text-orange-100 mt-3">Захват контрольных точек для получения ресурсов</p> 
                        </div>
                        
                        <div class="bg-stone-800/30 border-2 border-stone-600 p-5 flex flex-col items-center text-center">
                        <img class="w-[48px] h-[48px]" src="../assets/img/3.svg" />
                        <p class="text-orange-100 mt-3">Увеличивайте количество работников в вашем поселении, помогая мирному населению острова</p> 
                        </div>

                        <div class="bg-stone-800/30 border-2 border-stone-600 p-5 flex flex-col items-center text-center">
                        <img class="w-[48px] h-[48px]" src="../assets/img/4.svg" />
                        <p class="text-orange-100 mt-3">Исследуйте местность, решайте задачи, открывайте секреты и помогите вашему поселению выжить в нестабильное время</p> 
                        </div>
                    </div>  
                </div>

                <div class="w-full py-5">
                    <div class="flex ml-3 items-end uppercase text-xl text-yellow-300 font-bold before:font-black before:inline-block align-bottom before:content-['Дорожная_карта'] before:align-baseline  before:absolute before:text-3xl before:text-yellow-600 before:opacity-15 before:-ml-3">Дорожная карта</div>
                    <div class="grid grid-cols-1 gap-5 md:grid-cols-3 mt-5">
                        <div class="bg-stone-800/30 border-2 border-stone-600 p-5 flex flex-col">
                        <h3 class="text-sm text-orange-200/25 font-bold">2024</h3>
                        <h2 class="text-xl text-orange-50 font-bold -mt-2">Сентябрь</h2>
                        <ul class="list-disc text-orange-100 mt-3 px-5">
                            <li>Начальное введение в игровой процесс. Сюжетные задания, второстепенные задания</li>
                            <li>Проработка точек интересов. Причал, маяк, заброшенный бункер</li>
                            <li>Создание базовых интерфейсов</li>
                            <li>Игровые механики</li>
                        </ul>
                        </div>

                        <div class="bg-stone-800/30 border-2 border-stone-600 p-5 flex flex-col">
                        <h3 class="text-sm text-orange-200/25 font-bold">2024</h3>
                        <h2 class="text-xl text-orange-50 font-bold -mt-2">Октябрь</h2>
                        <ul class="list-disc text-orange-100 mt-3 px-5">
                            <li>Новые сюжетные и второстепенные задания</li>
                            <li>Проработка и наполнение поселения местных жителей</li>
                            <li>Разработка неигровых персонажей для поселения</li>
                            <li>Новые контрольные точки сети острова</li>
                            <li>Инвентарь, карта острова, карта сети, журнал заданий</li>
                            <li>Система сохранения и точки сохранения</li>
                        </ul>
                        </div>

                        <div class="bg-stone-800/30 border-2 border-stone-600 p-5 flex flex-col">
                        <h3 class="text-sm text-orange-200/25 font-bold">2024</h3>
                        <h2 class="text-xl text-orange-50 font-bold -mt-2">Ноябрь</h2>
                        <ul class="list-disc text-orange-100 mt-3 px-5">
                            <li>База J147: Восстановление базы и производство</li>
                            <li>Управление персоналом базы</li>
                            <li>Интерфейсы</li>
                            <li>Новые и второстепенные квесты</li>
                            <li>Расширение карты сети острова</li>
                        </ul>
                        </div>
                    </div>  
                </div>

                <div class="w-full py-7">
                    <img class="w-full h-full" src="../assets/img/divide.svg" />
                </div>

                <div class="w-full py-4 scroll-mt-11" id="dev">
                    <div class="flex ml-3 items-end uppercase text-xl text-yellow-300 font-bold before:font-black before:inline-block align-bottom before:content-['Социальные_сети'] before:align-baseline  before:absolute before:text-3xl before:text-yellow-600 before:opacity-15 before:-ml-3 before:truncate">Социальные сети</div>
                        
                    <div class="overflow-x-auto">
                            <div class="grid gap-5 grid-cols-1 lg:grid-cols-3 mt-5">
                            <router-link to="https://t.me/pangit_community" target="_blank" class="min-w-[280px] bg-stone-800 hover:bg-stone-800/75 border-2 border-stone-600 p-5 flex">
                                <div class="bg-stone-500/50 w-[48px] h-[48px] rounded-full flex items-center justify-center text-4xl overflow-hidden"><img src="../assets/img/telegram.svg" alt="" class="w-[48px] h-[48px]"></div>
                                <div class="text-orange-100 ml-3 flex flex-col">Телеграм
                                <span class="text-orange-100/70 text-sm">@pangit_community</span>
                                </div>
                            </router-link>
                            <router-link to="https://discord.gg/vzaxrs24Jj" target="_blank" class="min-w-[280px] bg-stone-800 hover:bg-stone-800/75 border-2 border-stone-600 p-5 flex">
                                <div class="bg-stone-500/50 w-[48px] h-[48px] rounded-full flex items-center justify-center text-4xl overflow-hidden"><img src="../assets/img/discord.svg" alt="" class="w-[48px] h-[48px]"></div>
                                <div class="text-orange-100 ml-3 flex flex-col">Discord
                                <span class="text-orange-100/70 text-sm">@pangit_community</span>
                                </div>
                            </router-link>
                            <router-link to="https://vk.com/pangit" target="_blank" class="min-w-[280px] bg-stone-800 hover:bg-stone-800/75 border-2 border-stone-600 p-5 flex">
                                <div class="bg-stone-500/50 w-[48px] h-[48px] rounded-full flex items-center justify-center text-4xl overflow-hidden"><img src="../assets/img/vk.svg" alt="" class="w-[48px] h-[48px]"></div>
                                <div class="text-orange-100 ml-3 flex flex-col">Вконтакте
                                <span class="text-orange-100/70 text-sm">@pangit</span>
                                </div>
                            </router-link>
                            
                            <router-link to="https://rutube.ru/channel/37244245/" target="_blank" class="min-w-[280px] bg-stone-800 hover:bg-stone-800/75 border-2 border-stone-600 p-5 flex">
                                <div class="bg-stone-500/50 w-[48px] h-[48px] rounded-full flex items-center justify-center text-4xl overflow-hidden"><img src="../assets/img/rutube.svg" alt="" class="w-[28px] h-[28px]"></div>
                                <div class="text-orange-100 ml-3 flex flex-col">Rutube
                                <span class="text-orange-100/70 text-sm">@DiezLife</span>
                                </div>
                            </router-link>
                            <router-link to="https://vk.com/video/@pangit" target="_blank" class="min-w-[280px] bg-stone-800 hover:bg-stone-800/75 border-2 border-stone-600 p-5 flex">
                                <div class="bg-stone-500/50 w-[48px] h-[48px] rounded-full flex items-center justify-center text-4xl overflow-hidden"><img src="../assets/img/vkvideo.svg" alt="" class="w-[28px] h-[28px]"></div>
                                <div class="text-orange-100 ml-3 flex flex-col text-nowrap">VK Видео
                                <span class="text-orange-100/70 text-sm">@pangit</span>
                                </div>
                            </router-link>
                            <router-link to="https://www.youtube.com/@DiezLife" target="_blank" class="min-w-[280px] bg-stone-800 hover:bg-stone-800/75 border-2 border-stone-600 p-5 flex">
                                <div class="bg-stone-500/50 w-[48px] h-[48px] rounded-full flex items-center justify-center text-4xl overflow-hidden"><img src="../assets/img/youtube.svg" alt="" class="w-[28px] h-[28px]"></div>
                                <div class="text-orange-100 ml-3 flex flex-col">YouTube
                                <span class="text-orange-100/70 text-sm">@DiezLife</span>
                                </div>
                            </router-link>
                        </div> 
                            
                            
                    </div>
                </div>
            </div>
    </section>
</template>

<style scoped>

</style>