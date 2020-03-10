<template>
  <table class="transactionList table">
    <tr>
      <th>{{ $t("labels.transactions.id") }}</th>
      <th>{{ $t("labels.transactions.date") }}</th>
      <th>{{ $t("labels.transactions.amount_crypto") }}</th>
      <th>{{ $t("labels.transactions.amount_real") }}</th>
    </tr>
    <Transaction :key="i" v-for="i in 10" />
  </table>
</template>

<script>
import Transaction from "./Transaction";
export default {
  components: {
    Transaction
  }
};
</script>

<style>
</style>