<template>

<div class="container">
<TransactionList/>
<AddTransaction/>
 </div>
</template>
<script>
import Header from './components/Header.vue';
import Balance from './components/Balance.vue';
import IncomeExpenses from './components/IncomeExpenses.vue';
import TransactionList from './components/TransactionList.vue';
import AddTransaction from './components/AddTransaction.vue';
export default {
  components:{
Header,
Balance,
IncomeExpenses,
TransactionList,
AddTransaction,

  },
};
</script>