<script setup>
const counter = useCounter();
import { useCounterStore } from "../stores/myStore";
const store = useCounterStore();
console.log("storestore", store);
</script>

<template>
  <div>
    <h2>Home</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. In perspiciatis
      omnis consequatur quod necessitatibus autem repellat aperiam quia atque
      fugit praesentium earum rerum minus, porro asperiores explicabo inventore
      animi ducimus. Itaque voluptatum facilis nobis, praesentium, quasi
      pariatur veniam veritatis quo eligendi, ratione libero impedit.
      Distinctio, delectus sapiente adipisci assumenda obcaecati aliquid
      exercitationem sit ad autem! Veritatis nihil accusamus recusandae esse?
    </p>
  </div>
  <Counter id="counter" />
</template>

<style>
.button-style {
  height: 50px;
  width: 100px;
  border: 1px solid;
  margin: 10px;
}
</style>
