<template>
  <!-- <table id="burger-table">
    <thead>
      <tr>
        <th>#</th>
        <th>Cliente</th>
        <th>Pão</th>
        <th>Carne</th>
        <th>Opcionais</th>
      </tr>
    </thead>
    <tbody>
      <tr v-for="(item, index) in items" :key="index">
        <td class="order-id">{{ item.id }}</td>
        <td>{{ item.cliente }}</td>
        <td>{{ item.pao }}</td>
        <td>{{ item.carne }}</td>
        <td>{{ item.opcionais }}</td>
      </tr>
    </tbody>
  </table> -->

  <div id="burger-table">
    <div>
      <div id="burger-table-heading">
        <div class="order-id">#:</div>
        <div>Cliente</div>
        <div>Pão:</div>
        <div>Carne:</div>
        <div>Opcionais:</div>
        <div>Ações:</div>
      </div>
    </div>
  </div>

  <div id="burger-table-rows">
    <div class="burger-table-row">
      <div class="order-number">1</div>
      <div>João</div>
      <div>Pao xis</div>
      <div>Carne</div>
      <div>
        <ul>
          <li>Salame</li>
          <li>Tomate</li>
        </ul>
      </div>
      <div>
        <select name="status" class="status">
          <option value="">Selecione o statue do Hamburger</option>
        </select>
        <button class="delete-btn">Cancelar</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Dashboard",
};
</script>

<style scoped>
#burger-table {
  max-width: 1200px;
  margin: 0 auto;
}
</style>
