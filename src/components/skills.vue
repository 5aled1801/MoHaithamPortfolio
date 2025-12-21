<template>
  <v-container>
    <v-row justify="center">
      <v-col cols="12" md="8">
        <h2 class="text-h2 text-center my-2 py-16 w-100 text-white">
          Experience
        </h2>

        <v-timeline align="start" side="end" class="bold-timeline" color="white">
          <v-timeline-item
            v-for="(item, index) in experiences"
            :key="index"
            :dot-color="item.color"
            size="small"
          >
            <template #opposite>
              <span class="font-weight-bold text-grey">
                {{ item.period }}
              </span>
            </template>

            <v-card elevation="4" rounded="lg" color="primary"> 
              <v-card-title class="text-h6">
                {{ item.title }}
              </v-card-title>

              <v-card-subtitle class="mb-2">
                {{ item.company }}
              </v-card-subtitle>

              <v-card-text>
                <ul>
                  <li v-for="(point, i) in item.points" :key="i">
                    {{ point }}
                  </li>
                </ul>
              </v-card-text>
            </v-card>
          </v-timeline-item>
        </v-timeline>
      </v-col>
    </v-row>
  </v-container>
</template>

<script setup>
const experiences = [
  {
    period: "July 2023 – Present",
    title: "Performance Media buyer",
    company: " MarketKing company, New Cairo",
    color: "primary",
    points: [
      "Create and manage Campaigns on different platforms",
      "full website Auditing & Conversion Rate Optimization (CRO)",
      "Full Website tracking through GTM & other CMS",
      "Landing page structure & design","Create and manage paid media strategies ","A/B testing, optimizing, scaling all paid media campaigns Across Multiple Channels","proceed on effective ads to drive better fit branding, Conversions, Revenue for the brand "
    ]
  },
  {
    period: "Feb 2023 – March 2023",
    title: "Marketing intern",
    company: " Phoenix Marketing company",
    color: "success",
    points: [
      "Generated and executed creative ideas for marketing campaigns",
      "Planned and scheduled campaign’s activities and deliverables",
      "Involved with content and media buying teams and following all daily tasks",
    ]
  }
];
</script>

<style scoped>
ul {
  padding-left: 18px;
}
li {
  margin-bottom: 6px;
}
.bold-timeline :deep(.v-timeline-divider__line),
.bold-timeline :deep(.v-timeline-divider__before),
.bold-timeline :deep(.v-timeline-divider__after) {
  background-color: #ffffff !important;
}

/* thickness */
.bold-timeline :deep(.v-timeline-divider__line) {
  width: 4px;
}
</style>
