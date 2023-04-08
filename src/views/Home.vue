<template>
  <Banner />
  <div class="main-container">
    <h1>Monte o seu burger:</h1>
    <BurgerForm />
  </div>
</template>

<script>
import BurgerForm from "../components/BurgerForm";

export default {
  name: "Home",
  components: {
    BurgerForm,
  },
};
</script>
