<script setup lang="ts">
import TotalGrowth from './components/TotalGrowth.vue';
import GoalProgress from './components/GoalProgress.vue';
import TotalGoalsProgress from './components/TotalGoalsProgress.vue';
import TransactionsTable from './components/TransactionsTable.vue';
</script>

<template>
  <v-row>
    <v-col cols="12" lg="8">
      <GoalProgress />
    </v-col>
    <v-col cols="12" lg="4">
      <TotalGoalsProgress />
    </v-col>
    <v-col cols="12" lg="12">
      <TotalGrowth />
    </v-col>
    <v-col cols="12" lg="12">
      <TransactionsTable />
    </v-col>
  </v-row>
</template>
