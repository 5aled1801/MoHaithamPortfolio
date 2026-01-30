<template>
    <v-container class="text-white relative mt-16 pt-16" id="Projects">
        <v-row>
            <h1 class="text-h2 text-center mt-16 py-16 w-100">Projects</h1>
        </v-row>
        <v-row>
            <v-tabs v-model="tab" align-tabs="center" grow>
                <v-tab value="1">
                    Services
                </v-tab>
                <v-tab value="2">
                    E-Commerce
                </v-tab>

                <v-tab value="3">
                    Saas
                </v-tab>
                <!-- <v-tab value="4">
                    Other Fields
                </v-tab> -->
            </v-tabs>
        </v-row>
        <v-window v-model="tab" class="my-8 w-100">
            <v-window-item value="1">
                <h1 class="text-h5 text-center py-4 ">Performance "Service Results"</h1>
                <v-row>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>1st project</v-card-title>

                            <img src="../assets/images/leads/Leads campaigns-1st image.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>1st project</v-card-title>
                            <img src="../assets/images/leads/Cleo - branding-2nd image .png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>1st project</v-card-title>
                            <img src="../assets/images/leads/Google - total conversions-3rd client.png" alt=""
                                width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>1st project</v-card-title>
                            <img src="../assets/images/leads/Google medical - UAE-4th image.png" alt="" width="100%">
                        </v-card>
                    </v-col>

                </v-row>

            </v-window-item>

            <v-window-item value="2">
                <h1 class="text-h5 text-center py-4 ">Performance "E-commerce"</h1>
                <v-row>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>1st project</v-card-title>
                            <img src="../assets/images/e-commerce/Qotof - ecom sales - 1st.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card> <v-card-title>1st project</v-card-title>

                            <img src="../assets/images/e-commerce/Qotof - ecom sales - 2nd.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card> <v-card-title>1st project</v-card-title>

                            <img src="../assets/images/e-commerce/TikTok - Qotof.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>1st project</v-card-title>

                            <img src="../assets/images/e-commerce/Qotof - ecom sales 4th.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>1st project</v-card-title>

                            <img src="../assets/images/e-commerce/Google - qotof.png" alt="" width="100%">

                        </v-card>
                    </v-col><v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>2nd project</v-card-title>

                            <img src="../assets/images/e-commerce/Rahala - eom meta 1st.png" alt="" width="100%">


                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>2nd project</v-card-title>

                            <img src="../assets/images/e-commerce/Rahala - shopify dash2nd.png" alt="" width="100%">


                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>2nd project</v-card-title>

                            <img src="../assets/images/e-commerce/Rahala - shopify dash2nd.png" alt="" width="100%">

                        </v-card>
                    </v-col>

                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>2nd project</v-card-title>

                            <img src="../assets/images/e-commerce/Rahala - cart abandond (whastapp)3rd.png" alt=""
                                width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>3rd project</v-card-title>
                            <img src="../assets/images/e-commerce/Tshop - Shopify sales-1st image.png" alt=""
                                width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>3rd project</v-card-title>

                            <img src="../assets/images/e-commerce/Tshop - ecom sales 2nd.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>4th project</v-card-title>
                            <img src="../assets/images/e-commerce/last project- ROAS8-.png" alt="" width="100%">
                        </v-card>
                    </v-col>

                </v-row>

            </v-window-item>
            <v-window-item value="3">
                <h1 class="text-h5 text-center py-4 ">Saas</h1>

                <v-row>

                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <!-- <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle> -->
                            <img src="../assets/images/saas/KSA - OTO - Meta 2025-1st image.png" alt="" width="100%">
                        </v-card>
                    </v-col> <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <!-- <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle> -->
                            <img src="../assets/images/saas/KSA - OTO - Google - Jan to Dec 2024-2nd.png" alt=""
                                width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <!-- <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle> -->
                            <img src="../assets/images/saas/KSA - OTO Google - Jan to Dec 2025-3rd.png" alt=""
                                width="100%">
                        </v-card>
                    </v-col> <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <!-- <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle> -->
                            <img src="../assets/images/saas/Turkey - OTO Google - Jan to Dec 2025-4th.png" alt=""
                                width="100%">
                        </v-card>
                    </v-col> <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <!-- <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle> -->
                            <img src="../assets/images/saas/TR - OTO Meta - Jun to Dec 2024-5th.png" alt=""
                                width="100%">
                        </v-card>
                    </v-col> <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <!-- <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle> -->
                            <img src="../assets/images/saas/OTO TR - Meta - Jan to june 2025-6th.png" alt="" width="100%">
                        </v-card>
                    </v-col> <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <!-- <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle> -->
                            <img src="../assets/images/saas/UAE - OTO Google - Jan to Dec 2025-7th.png" alt="" width="100%">
                        </v-card>
                    </v-col> <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <!-- <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle> -->
                            <img src="../assets/images/saas/UAE - OTO Meta - June to Dec 2025-8th.png" alt="" width="100%">
                        </v-card>
                    </v-col>

                </v-row>

            </v-window-item>

        </v-window>
    </v-container>
</template>

<script>
export default {
    name: 'Projects',
    data() {
        return {
            tab: 1
        }
    }
};
</script>

<style scoped>
.v-btn {
    font-size: 13px;
    background: rgba(16, 100, 209, 0.349);
    margin-inline-end: 10px;
    color: rgb(255, 255, 255);

}

.v-card {
    max-height: 400px !important;
    height: 400px !important;
}

img {
    height: 90%;
    width: 100%;
}
</style>