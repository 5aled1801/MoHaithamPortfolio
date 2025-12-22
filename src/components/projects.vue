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
            </v-window>
    </v-container>
</template>

<script>
export default {
    name: 'Projects',
    data() {
        return {
            tab: 0
        }
    }
};
</script>

<style scoped>
.v-btn {
    font-size: 13px;
    background:rgba(16, 100, 209, 0.349);
    margin-inline-end: 10px;
    color: rgb(255, 255, 255);
    
}
.v-card{
        min-height: 365px !important;
}
</style>