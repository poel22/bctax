<template>
  <tr class="transaction">
    <td>{{ id }}</td>
    <td>{{ date }}</td>
    <td>{{ direction }}</td>
    <td>{{ amount_crypto }}</td>
    <td>{{ amount_real }}</td>
  </tr>
</template>

<script>
export default {
  props: {
    id: {
      default: 1
    },
    date: {
      default: "10.02.2019"
    },
    direction: {
      default: "sell"
    },
    amount_crypto: {
      default: 232
    },
    amount_real: {
      default: 372.23
    }
  },
  data() {
    return {};
  },
  methods: {}
};
</script>

<style>
</style>