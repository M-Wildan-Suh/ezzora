<script setup>
import AuthenticatedLayout from '@/layouts/AuthenticatedLayout.vue'
</script>

<template>
    <AuthenticatedLayout>
        <div class=" w-full h-screen bg-amber-200 flex align-middle">
            <div class=" mx-auto w-full max-w-[1120px] relative">
                <div class=" flex flex-col absolute top-1/2 -translate-y-1/2 w-1/2 text-5xl font-thin">
                    <div class=" mb-4" >Natural Cosmetics for gentle skincare</div>
                    <div>
                        <RouterLink class=" text-lg font-medium p-1 px-3 border duration-300 border-neutral-400 hover:border-transparent">
                            shop now
                        </RouterLink>
                    </div>
                </div>
            </div>
        </div>
        <div class=" w-full py-16">
            <div class=" flex flex-row mx-auto w-full max-w-[1120px] relative">
                <div class=" w-1/3 relative">
                    <div class=" absolute top-1/2 -translate-y-1/2">
                        <div class=" text-4xl font-thin mb-5">Best seller</div>
                        <div class=" text-lg mb-5" >A Wide range of face wash body care cosmetics that will not Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit molestiae repudiandae voluptate.</div>
                        <RouterLink class=" text-lg p-1 px-3 border duration-300 border-neutral-400 hover:border-transparent">
                            view all
                        </RouterLink>
                    </div>
                </div>
                <div class=" w-2/3 flex justify-center flex-col p-3">
                    <div class=" w-full flex justify-center flex-row" >
                        <div class=" flex flex-col p-4 border mx-2">
                            <div class="w-48 bg-black h-48">
                                <img src="" alt="" srcset="">
                            </div>
                            <div class=" text-lg font-medium mb-2" >Face Wash</div>
                            <div class=" text-slate-500 text-sm mb-5" >Rp. 200.000</div>
                            <div class=" mb-5">
                                <RouterLink class=" text-base bg-black text-white p-2 px-3 border duration-300 border-neutral-400 hover:border-transparent rounded">
                                    view detail
                                </RouterLink>
                            </div>
                        </div>
                    </div>
                    <div class=" w-full flex justify-center p-3">
                        <button type="button" class=" p-2 bg-black mx-2">
                            <svg height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg"><polygon fill-rule="evenodd" fill="white" points="9.414 12 16.707 19.293 15.293 20.707 6.586 12 15.293 3.293 16.707 4.707"/></svg>
                        </button>
                        <button type="button" class=" p-2 bg-black mx-2">
                            <svg height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg"><polygon fill-rule="evenodd" fill="white" points="14.586 12 7.293 4.707 8.707 3.293 17.414 12 8.707 20.707 7.293 19.293"/></svg>
                        </button>
                    </div>
                </div>
            </div>
        </div>
        <div class=" w-full py-16">
            <div class=" flex flex-col mx-auto w-full max-w-[1120px] relative">
                <div>New Product</div>
                <div class="w-full " ></div>
                <div class=" w-full flex justify-center p-3">
                    <button type="button" class=" p-2 bg-black mx-2">
                        <svg height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg"><polygon fill-rule="evenodd" fill="white" points="9.414 12 16.707 19.293 15.293 20.707 6.586 12 15.293 3.293 16.707 4.707"/></svg>
                    </button>
                    <button type="button" class=" p-2 bg-black mx-2">
                        <svg height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg"><polygon fill-rule="evenodd" fill="white" points="14.586 12 7.293 4.707 8.707 3.293 17.414 12 8.707 20.707 7.293 19.293"/></svg>
                    </button>
                </div>
            </div>
        </div>
    </AuthenticatedLayout>
</template>
