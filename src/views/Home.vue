<template>
  <div class="home">
    <v-row>
      <h1 class="text-left">DashBoard</h1>
    </v-row>
    <v-row>
      <v-col cols=12 md=4 lg=4 style="border-syle=solid:border-width=1px">
        <HabitList/>
      </v-col>
      <v-col cols=12 md=4 lg=4 style="border-syle=solid:border-width=1px">
        grafico con abitudini
      </v-col>
    </v-row>
  </div>
</template>

<script>
// @ is an alias to /src

import HabitList from '@/components/HabitList.vue';

export default {
  name: 'Home',
  components: {
    HabitList,
  },
};
</script>
