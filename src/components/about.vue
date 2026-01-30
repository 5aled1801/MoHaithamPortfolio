<template>
    <v-container class="text-white relative file-content" id="About">
        <v-row class="align-center justify-space-between absolute fil col-reverse mt-16 mb-16">
            <h1 class="text-h2 text-center my-2 py-16 w-100">About </h1>
            <h1 style="padding: 10px;font-size: 20px;line-height: 1.6;">
                Performance Marketing Specialist with 3 years of experience driving scalable growth across B2C and B2B
                businesses. Specialized in full-funnel performance plan, combining paid media, CRO, tracking, and
                analytics.
                Proven ability to scale high-budget campaigns a paid social and paid search. while optimizing ROAS, CAC,
                and customer LTV.
            </h1>
            <!-- <a href="/Khaled Hassan cv.pdf" download
                style="color: white; margin:auto;margin-top:50px"><v-icon>mdi-folder</v-icon> Download CV</a> -->
                
                <h1 class="text-h2 text-center my-2 py-16 w-100 ">What I Do?</h1>
                <div class="images-wrapper d-flex flex-wrap justify-center align-center">
                    <img v-for="(img, index) in iDoImages" :key="index" :src="getImage(img)"
                        class="what-i-do-img w-50 px-4 bg-white mx-2 my-4 rounded"
                        style="height:190px;object-fit:contain; max-width:350px;  "
                        alt="what i do" />
                </div>
        </v-row>
    </v-container>

</template>
<script>
export default {
    name: 'about',
    data() {
        return {
            IDo: {
                title: "../assets/images/whatIDo/1.png",
                title2: "../assets/images/whatIDo/2.png",
                title3: "../assets/images/whatIDo/3.png",
                title4: "../assets/images/whatIDo/4.png",
                title5: "../assets/images/whatIDo/5.jpg",
                title6: "../assets/images/whatIDo/6.png",
                title7: "../assets/images/whatIDo/7.png",
                title8: "../assets/images/whatIDo/8.png",
                title9: "../assets/images/whatIDo/9.jpg",
                title10: "../assets/images/whatIDo/10.png",
                title11: "../assets/images/whatIDo/11.png",
                title12: "../assets/images/whatIDo/12.jpg",
                title13: "../assets/images/whatIDo/13.jpg",
                title14: "../assets/images/whatIDo/14.png",
                title15: "../assets/images/whatIDo/15.png",
            },
        };
    },
    computed: {
        iDoImages() {
            return Object.values(this.IDo);
        },
    },
    methods: {
        getImage(path) {
            return new URL(path, import.meta.url).href;
        },
    },
}
</script>