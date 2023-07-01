<script setup>

  const options = {
        chart: {
          id: 'vuechart-example'
        },
        xaxis: {
          categories: [1991, 1992, 1993, 1994, 1995, 1996, 1997, 1998]
        }
      }
  const series = [{
        name: 'series-1',
        data: [30, 40, 45, 50, 49, 60, 70, 91]
      }]

</script>

<template>
<div>
  <h1>Line chart</h1>
  <apexchart width="500" type="line" :options="options" :series="series"></apexchart>
</div>
</template>

