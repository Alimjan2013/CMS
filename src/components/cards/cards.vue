
<template>
  <div class="container1">
<div class="cardGrid">
    <IconCard />
    <IconCard />
    <IconCard />
    <IconCard />
    <IconCard />
  </div>
  </div>
  
</template>


<script>
import IconCard from "./iconCard.vue";

export default {
  name: "App",
  components: {
    IconCard: IconCard,
  },
};
</script>

<style>
.container1{
  display: flex;
  justify-content: center;
}
.cardGrid{
  max-width: 1200px;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  gap: 10px;
}
@media (max-width: 1200px) {
  .cardGrid{
  padding:16px;
}
}
@media (max-width: 1000px) {
  .cardGrid{
  display: grid;
  grid-template-columns: 1fr  1fr 1fr;

 
}
}
@media (max-width: 770px) {
  .cardGrid{
  display: grid;
  grid-template-columns: 1fr 1fr ;
  gap: 10px;
  padding:8px;
}
}

</style>