<template>
  <div class="table">
    <div class="table__row table__row--head">
      <div class="table__cell table__cell--head">Название</div>
      <div class="table__cell table__cell--head">Расход топлива мл/г</div>
      <div class="table__cell table__cell--head">Цилиндры</div>
      <div class="table__cell table__cell--head">Рабочий объём</div>
      <div class="table__cell table__cell--head">Л.C</div>
      <div class="table__cell table__cell--head">Вес</div>
      <div class="table__cell table__cell--head">Ускорение м/c2</div>
      <div class="table__cell table__cell--head">Год выпуска</div>
      <div class="table__cell table__cell--head">Производство</div>
    </div>
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
