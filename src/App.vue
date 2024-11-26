<template>
  <SearchBarComponent />
  <HeaderComponent />
  <div class="flex">
    <div class="w-3/4">
      <ChartComponent />
    </div>
    <div class="w-1/4">
      <SummaryComponent />
    </div>
  </div>
  <TabComponent />
  <InstrumentListComponent />
</template>

<script>
import SearchBarComponent from './components/SearchBarComponent.vue'
import HeaderComponent from './components/HeaderComponent.vue'
import ChartComponent from './components/ChartComponent.vue'
import SummaryComponent from './components/SummaryComponent.vue'
import TabComponent from './components/TabComponent.vue'
import InstrumentListComponent from './components/InstrumentListComponent.vue'

export default {
  name: "App",
  data() {
    return {
    };
  },
  computed: {

  },
  methods: {

  },
  components: { SearchBarComponent, HeaderComponent, ChartComponent, SummaryComponent, TabComponent, InstrumentListComponent }
}
</script>