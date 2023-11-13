<template>
  <div class="table__row">
    <div class="table__cell">chevrolet caprice classic</div>
    <div class="table__cell">13</div>
    <div class="table__cell">8</div>
    <div class="table__cell">400</div>
    <div class="table__cell">150</div>
    <div class="table__cell">4464</div>
    <div class="table__cell">12</div>
    <div class="table__cell">1973-01-01</div>
    <div class="table__cell">USA</div>
  </div>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: padding-box;
}

.table {
  display: table;
  margin: 0 auto;
  border-left: 1px solid #ccc;
  border-right: 1px solid #ccc;
}

.table__row {
  display: table-row;

  border-bottom: 1px solid #ccc;
}

.table__row--head {
  color: #fff;
  text-transform: uppercase;
  font-weight: bold;

  background-color: #08beff;
  box-shadow: 1px 0 6px 3px #ccc;
}

.table__cell {
  display: table-cell;
  padding: 10px;
}
</style>
