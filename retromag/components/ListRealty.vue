<template>
    <section id="carpet__section" class="mt-5">
        <div class="container">
            <div class="row">
                <div class="col-md-12 mb-5" v-for="realty in realtys" :key="realty.id">
                    <div class="card card__carpet">
                        <img class="card-img-top card__cafe-img" :src="realty.img" alt="realty">
                            <div class="card-body mt-5">
                                <NuxtLink :to="'/realty/'">
                                    <h2>{{ realty.name }}</h2>
                                </NuxtLink>
                                <hr />
                                <b>{{ realty.description }}</b>
                            </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import RealtyList from "@/assets/realty.json"

export default {
    data() {
        return RealtyList
    }
}
</script>