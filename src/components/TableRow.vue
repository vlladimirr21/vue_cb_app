<script setup>
import Data1 from '../data/cars-1.json'
import Data2 from '../data/cars-2.json'
</script>

<template>
  <div class="table__row table__row--head">
    <div class="table__cell">Название</div>
    <div class="table__cell">Расход топлива мл/г</div>
    <div class="table__cell">Цилиндры</div>
    <div class="table__cell">Рабочий объём</div>
    <div class="table__cell">Л.C</div>
    <div class="table__cell">Вес</div>
    <div class="table__cell">Ускорение м/c2</div>
    <div class="table__cell">Год выпуска</div>
    <div class="table__cell">Производство</div>
  </div>

  <div class="table__row" v-for="car in Data1">
    <div class="table__cell">{{ car.Name }}</div>
    <div class="table__cell">{{ car.Miles_per_Gallon }}</div>
    <div class="table__cell">{{ car.Cylinders }}</div>
    <div class="table__cell">{{ car.Displacement }}</div>
    <div class="table__cell">{{ car.Horsepower }}</div>
    <div class="table__cell">{{ car.Weight_in_lbs }}</div>
    <div class="table__cell">{{ car.Acceleration }}</div>
    <div class="table__cell">{{ car.Year }}</div>
    <div class="table__cell">{{ car.Origin }}</div>
  </div>

  <div class="table__row" v-for="car in Data2">
    <div class="table__cell">{{ car.Name }}</div>
    <div class="table__cell">{{ car.Miles_per_Gallon }}</div>
    <div class="table__cell">{{ car.Cylinders }}</div>
    <div class="table__cell">{{ car.Displacement }}</div>
    <div class="table__cell">{{ car.Horsepower }}</div>
    <div class="table__cell">{{ car.Weight_in_lbs }}</div>
    <div class="table__cell">{{ car.Acceleration }}</div>
    <div class="table__cell">{{ car.Year }}</div>
    <div class="table__cell">{{ car.Origin }}</div>
  </div>
</template>

<!-- 
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

  <div class="table__row">
    <Data1 />
    <Data2 />
  </div>
</template> -->

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
