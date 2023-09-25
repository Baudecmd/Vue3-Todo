<script setup>
import { useRouter } from 'vue-router';

const router = useRouter()
const goToLoginPage = () => {
    router.push("/login")
}
</script>

<template>
    <div class="bg-light-blue" >
        <div class="flex flex-row justify-between  ">
            <div class="pt-5 pb-5 flex justify-items-center">
                <div>TOGAME LOGO</div>
            </div>
            <button @click="goToLoginPage" class=" mt-5 mb-5 bg-transparent hover:bg-blue-500 text-blue-700 font-semibold hover:text-white py-2 px-4 border border-blue-500 hover:border-transparent rounded">
                Connexion
            </button>
        </div>
    </div>
</template>