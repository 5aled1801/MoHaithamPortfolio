<template>
    <v-container class="text-white relative mt-16 pt-16" id="Projects">
        <v-row>
            <h1 class="text-h2 text-center mt-16 py-16 w-100">Projects</h1>
        </v-row>
        <v-row>
            <v-tabs v-model="tab" align-tabs="center" grow>
                <v-tab value="1">
                    Leads
                </v-tab>
                <v-tab value="2">
                    E-Commerce
                </v-tab>

                <v-tab value="3">
                    Saas
                </v-tab>
                <v-tab value="4">
                    Other Fields
                </v-tab>
            </v-tabs>
        </v-row>
        <v-window v-model="tab" class="my-8 w-100">
            <v-window-item value="1">
                <h1 class="text-h5 text-center py-4 ">Performance "Leads Results"</h1>
                <v-row>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Performance campaigns (meta leads)</v-card-title>
                            <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle>
                            <img src="../assets/images/leads/metaLeads1.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Branding campaigns</v-card-title>
                            <!-- <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle> -->
                            <img src="../assets/images/leads/brandingCampaigns.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Performance campaigns (website leads & messages)</v-card-title>
                            <!-- <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle> -->
                            <img src="../assets/images/leads/performance(website+messages).png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Performance campaigns (Meta leads)</v-card-title>
                            <v-card-subtitle>Conversion Rate is: 28%</v-card-subtitle>
                            <img src="../assets/images/leads/performance camp(metaLeads.png" alt="" width="100%">
                            <img src="../assets/images/leads/performance camp(metaLeads2.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Google Campaigns</v-card-title>
                            <img src="../assets/images/leads/2222.png" alt="" width="100%">
                            <img src="../assets/images/leads/3333.png" alt="" width="100%">
                            <img src="../assets/images/leads/1111.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                </v-row>

            </v-window-item>

            <v-window-item value="2">
                <h1 class="text-h5 text-center py-4 ">Performance "E-commerce"</h1>
                <v-row>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Performance campaigns (Meta)</v-card-title>
                            <v-card-subtitle>1st client</v-card-subtitle>
                            <img src="../assets/images/e-commerce/meta.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Performance campaigns (TikTok)</v-card-title>
                            <v-card-subtitle>1st client</v-card-subtitle>
                            <img src="../assets/images/e-commerce/tiktok.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Performance campaigns (Purchases)</v-card-title>
                            <v-card-subtitle>2nd client</v-card-subtitle>
                            <img src="../assets/images/e-commerce/purchases.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Shopify dashboard</v-card-title>
                            <v-card-subtitle>2nd client</v-card-subtitle>
                            <img src="../assets/images/e-commerce/shopify dash.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>UP selling & Abandoned cart </v-card-title>
                            <v-card-subtitle>2nd client</v-card-subtitle>
                            <img src="../assets/images/e-commerce/upselling.png" alt="" width="100%">

                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Performance campaigns (Purchases) </v-card-title>
                            <v-card-subtitle>2nd client</v-card-subtitle>
                            <img src="../assets/images/e-commerce/Performance campaigns (Purchases).png" alt=""
                                width="100%">
                                
                            <img src="../assets/images/e-commerce/Performance campaigns (Purchases)2.png" alt=""
                                width="100%">

                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Performance campaigns (Purchases) </v-card-title>

                            <v-card-subtitle>3rd client</v-card-subtitle>

                            <img src="../assets/images/e-commerce/Performance campaigns (Purchases) client3.png" alt=""
                                width="100%">


                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6"></v-col>
                    <v-col cols="12">

                        <h1 class="text-h4 text-center py-6 bolder ">Ecommerce "retail marketplace"</h1>
                    </v-col>

                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Shopify dashboard </v-card-title>
                            <v-card-subtitle>1st client</v-card-subtitle>
                            <img src="../assets/images/e-commerce/ret/dash1st.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Performance campaigns (Purchases)</v-card-title>
                            <v-card-subtitle>1st client</v-card-subtitle>
                            <img src="../assets/images/e-commerce/ret/1stpurchases.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Performance campaigns (Purchases)</v-card-title>
                            <v-card-subtitle>2nd client</v-card-subtitle>
                            <img src="../assets/images/e-commerce/ret/2ndpur.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Branding campaigns</v-card-title>
                            <v-card-subtitle>2nd client</v-card-subtitle>
                            <img src="../assets/images/e-commerce/ret/bra.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Performance campaigns (Purchases)</v-card-title>
                            <v-card-subtitle>2nd client</v-card-subtitle>
                            <img src="../assets/images/e-commerce/ret/xxxx.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Branding & messages campaigns</v-card-title>
                            <v-card-subtitle>2nd client</v-card-subtitle>
                            <img src="../assets/images/e-commerce/ret/zzzz.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                </v-row>

            </v-window-item>
            <v-window-item value="3">
                <h1 class="text-h5 text-center py-4 ">Saas</h1>
                <p class="text-h6 text-center py-4"><span class="text-blue text-h5 ">Client X,</span>1st Shipping gateway in the MENA region connecting e-commerce stores and shipping
                    companies</p>
                <v-row>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Performance campaigns (sign-ups - 1st shipment)</v-card-title>
                            <!-- <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle> -->
                            <img src="../assets/images/saas/1.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>Branding campaigns</v-card-title>
                            <!-- <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle> -->
                            <img src="../assets/images/saas/2.png" alt="" width="100%">
                        </v-card>
                    </v-col>
                   
                    
                </v-row>

            </v-window-item>
            <v-window-item value="4">
                <h1 class="text-h5 text-center py-4 ">App & website booking</h1>
                
                <v-row>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>1st client - website booking services</v-card-title>
                            <!-- <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle> -->
                            <img src="../assets/images/ther/1.jpg" alt="" width="100%">
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="12" lg="6">
                        <v-card>
                            <v-card-title>2nd client - A mobile application located in KSA</v-card-title>
                            <!-- <v-card-subtitle>Conversion Rate is: 22%</v-card-subtitle> -->
                            <img src="../assets/images/ther/2.jpg" alt="" width="100%">
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
    min-height: 365px !important;
}
</style>