<template lang="">
    <div class="flex bg-red-200 font-bold">
        <div class="grow justify-self-start">
            <img class="" src="../assets/images/pcg.png" alt="" width="170">
        </div>
        <div class="grow-0 w-75 text-6xl text-center pt-6 mr-20">
            <p>The Power code girl</p>
        </div>
        <div class="grow text-white text-2xl text-right pt-10 mr-11">
            <p>Home</p>
        </div>
    </div>
    <div class="bg-amber-100 p-20">
        <div class="flow-root text-center">
            <p class="text-2xl font-bold">welcome to our website</p>
            <div class="flow-root text-l pt-5 pb-15">
                <p>This website is created to practice programming for web development.</p>
                <p>Let's get to know our members and can contact us at the contact button.</p>
            </div>
        </div>
    </div>
    <div class="flex">
        <div class="flex-1 text-center bg-sky-200 drop-shadow-2xl transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-105 hover:bg-sky-400 duration-300">
            <div class="inline-block py-10">
                <img class="rounded-full justify-self-center ml-8" src="../assets/images/Fresh.jpg" alt="" width="200">
                <div class="p-5">
                    <p class="text-4xl font-bold">Fresh</p>
                    <p class="p-2 text-xl">Nuttanicha Kaeopholsri</p>
                </div>
                <div class="m-3 p-2 bg-slate-200 rounded-full drop-shadow-2xl transition ease-in-out delay-150 hover:bg-slate-400 duration-300">
                    <router-link to="/profile">Profile</router-link>
                </div>
            </div>
        </div>
        <div class="flex-1 text-center bg-rose-300 drop-shadow-2xl transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-105 hover:bg-rose-400 duration-300">
            <div class="inline-block py-10 ">
                <img class="rounded-full justify-self-center" src="../assets/images/Yuuka.jpg" alt="" width="200">
                <div class="p-5">
                    <p class="text-4xl font-bold">Yuuka</p>
                    <p class="p-2 text-xl">Yuuka Kawai</p>
                </div>
                <div class="m-3 p-2 bg-slate-200 rounded-full drop-shadow-2xl transition ease-in-out delay-150 hover:bg-slate-400 duration-300">
                    <router-link to="/profile">Profile</router-link>
                </div>
            </div>
        </div>
        <div class="flex-1 text-center bg-emerald-300 drop-shadow-2xl transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-105 hover:bg-emerald-400 duration-300">
            <div class="inline-block py-10">
                <img class="rounded-full justify-self-center" src="../assets/images/Yeepoon.jpg" alt="" width="200">
                <div class="p-5">
                    <p class="text-4xl font-bold">Yeepoon</p>
                    <p class="p-2 text-xl">Panisara Poosee</p>
                </div>
                <div class="m-3 p-2 bg-slate-200 rounded-full drop-shadow-2xl transition ease-in-out delay-150 hover:bg-slate-400 duration-300">
                    <router-link to="/profile">Profile</router-link>
                </div>
            </div>
        </div>
    </div>
    <div class="text-center font-bold text-xl bg-amber-100 pt-20 pb-10">
        <p>Female Future Foundation</p>
        <p>@2022</p>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="">
    
</style>