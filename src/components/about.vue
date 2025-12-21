<template>
    <v-container class="text-white relative file-content" id="About" >
        <v-row class="align-center justify-space-between absolute fil col-reverse mt-16 mb-16">
            <h1 class="text-h2 text-center my-2 py-16 w-100">About </h1>
            <h1 style="padding: 10px;font-size: 20px;line-height: 1.6;">
                As a performance media buyer, I aim to apply my practical experience in creating data-driven campaigns
                that
                deliver real business results. I aim to support a growth-focused team by managing multi-platform paid
                media,
                enhancing website performance through CRO and accurate tracking (GTM), and building strong landing page
                strategies that improve ROI and drive conversions.
            </h1>
            <!-- <a href="/Khaled Hassan cv.pdf" download
                style="color: white; margin:auto;margin-top:50px"><v-icon>mdi-folder</v-icon> Download CV</a> -->
            <h1 class="text-h2 text-center my-2 py-16 w-100">What I Do?</h1>
            <ol style="padding: 10px;font-size: 18px;line-height:2; " class="mx-4">
                <li v-for="n in IDo" :key="n">{{ n }}</li>
            </ol>
        </v-row>
    </v-container>

</template>
<script>
export default {
    name: 'about',
    data() {
        return {
            IDo: {
                title: "full website Auditing & Conversion Rate Optimization (CRO)",
                title: "Full Website tracking through GTM & other CMS",
                title3: "Landing page structure & design",
                title4: "Create and manage paid media strategies",
                title5: "A/B testing, optimizing, scaling all paid media campaigns Across Multiple Channels",
                title6: "proceed on effective ads to drive better fit branding, Conversions, Revenue for the brand"
            }
        };
    },
}
</script>