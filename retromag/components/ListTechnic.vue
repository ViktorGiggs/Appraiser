<template>
    <section id="carpet__section" class="mt-5">
        <div class="container">
            <div class="row">
                <div class="col-md-12 mb-5" v-for="technic in technics" :key="technic.id">
                    <div class="card card__carpet">
                        <img class="card-img-top card__cafe-img" :src="technic.img" alt="technic">
                            <div class="card-body mt-5">
                                <NuxtLink :to="'/technic/'">
                                    <h2>{{ technic.name }}</h2>
                                </NuxtLink>
                                <hr />
                                <b>{{ technic.description }}</b>
                            </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import TechnicList from "@/assets/technic.json"

export default {
    data() {
        return TechnicList
    }
}
</script>