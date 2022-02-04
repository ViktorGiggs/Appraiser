<template>
    <div class="container text-over mt-5">
        <div class="row">
            <div class="col-md-4 mt-5" v-for="(technic, index) in technics" :key="'technic-' + index">
                <div class="card mb-3">
                    <img :src="technic.img" class="card-img-top card__carpet-img" alt="technic">
                    <div class="card-body">
                        <h5 class="card-title">
                            {{ technic.title }}
                        </h5>
                        <p class="card-text">
                            {{ technic.price }} &#11088;
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

export default {
    layout: 'firstpage',
    data() {
        return {
            technics: [
                {
                    "id": "0",
                    "title": "Mark 600. The best device for you and your home.",
                    "img": "https://64.media.tumblr.com/e9c3777e67a723895fbfdc010c90d60e/tumblr_pjdp4ioVhR1wcjtbio1_1280.jpg",
                    "price": "4.1/5"
                },
                {
                    "id": "1",
                    "title": "Sonic Blast 2000. The best device for you and your home.",
                    "img": "https://64.media.tumblr.com/ce825c0746c99d12e41505e1bb4bc7f8/tumblr_pgl0uqtIkn1uu4f9zo1_640.jpg",
                    "price": "4.3/5"
                },
                {
                    "id": "2",
                    "title": "Pioneer pr 7820. The best device for you and your home.",
                    "img": "https://64.media.tumblr.com/e7d3b572b053dd0c8f6ed77abf99d1ba/a3dcb313d6b66033-a0/s1280x1920/67366840796264bcc575fa44bf5a7d36ceedab74.jpg",
                    "price": "4.5/5"
                },
                {
                    "id": "3",
                    "title": "Sony FD-10 Watchman. The best device for you and home.",
                    "img": "https://64.media.tumblr.com/85d72394cd03def90fa9ca3d34db9491/8c425838911a7aeb-99/s640x960/54917e8d42ef3ba294f779da40bcbb7e658e5bad.jpg",
                    "price": "3.2/5"
                },
                {
                    "id": "4",
                    "title": "Toshiba ur-fo. The best device for you and your home.",
                    "img": "https://64.media.tumblr.com/a2aa8b37dc6efa346e7a718ae3e65b49/ddfc511c64bbc6a7-08/s1280x1920/9c2157c2a5231e262df6acddb35a1c1df256c156.jpg",
                    "price": "3.5/5"
                },
                {
                    "id": "5",
                    "title": "Sharp mz-5500. The best device for you and your home.",
                    "img": "https://64.media.tumblr.com/bf7f96f97fd86563452c9987f7e2bf0d/0945170aa08a9a37-be/s1280x1920/882e8034aaa37efafe6701cbb7971762e8be310e.png",
                    "price": "3.8/5"
                },
                {
                    "id": "6",
                    "title": "Tatung Einstein TC-01. The best device for you and home.",
                    "img": "https://64.media.tumblr.com/5b5c2e06118b90b74bc2f9b6952ce338/b4654261db0ef362-51/s640x960/08723a478a8b0e2a0e304dcf404179de766d5770.jpg",
                    "price": "3.2/5"
                },
                {
                    "id": "7",
                    "title": "Hitachi vm c30. The best device for you and your home.",
                    "img": "https://64.media.tumblr.com/1ea3b2898806f6aee6057da30cc38ff7/36a60f0ad4bc4f16-aa/s2048x3072/0df69a1d234d601b8176c217f965dc893c1ff277.png",
                    "price": "4.3/5"
                },
                {
                    "id": "8",
                    "title": "Technics 5. The best device for you and your home.",
                    "img": "https://64.media.tumblr.com/8e22f44acea81b55300e9b9c384e5f59/4c9100f78f87d72b-35/s1280x1920/7ad19cb37d644cfcfbffd666816ec937fa4a3357.jpg",
                    "price": "4.8/5"
                },
                {
                    "id": "9",
                    "title": "Mitsubishi LT 5V. The best device for you and your home.",
                    "img": "https://64.media.tumblr.com/c26a356d9fcfbaa0eb7e51d4f9e29c32/44d360849bc98049-5f/s1280x1920/eccef57c02ae6b69c947af9ed5c37b4274dbce36.jpg",
                    "price": "4.8/5"
                },
                {
                    "id": "10",
                    "title": "Elwro 801 AT. The best device for you and your home.",
                    "img": "https://64.media.tumblr.com/d450a6a43c4476db98be5df6a9192b2d/738709b10d8966bb-a3/s1280x1920/063b0408158bb91ed830cee6fc31a68310dc4ffb.png",
                    "price": "4.7/5"
                },
                {
                    "id": "11",
                    "title": "Saba hi-fi system. The best device for you and your home.",
                    "img": "https://64.media.tumblr.com/148bc7f4d128937397df532d7966fd6f/93192511eb3075c5-f9/s1280x1920/54fc27e2542aac0f240de655b684f9e75ab5eb0b.jpg",
                    "price": "5/5"
                }
            ]
        }
    },
    head: {
    title: 'Technic'
    }
}
</script>
