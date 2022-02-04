<template>
    <section id="carpets__section" class="mt-5">
        <div class="container">
            <div class="row">
                <div class="col-md-12 mb-5" v-for="carpet in carpets" :key="carpet.id">
                    <div class="card card__carpet">
                        <img class="card-img-top card__cafe-img" :src="carpet.img" alt="carpet">
                            <div class="card-body mt-5">
                                <NuxtLink :to="'/carpet/'">
                                    <h2>{{ carpet.name }}</h2>
                                </NuxtLink>
                                <hr />
                                <b>{{ carpet.description }}</b>
                            </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import CarpetList from "@/assets/carpets.json"

export default {
    data() {
        return CarpetList
    }
}
</script>