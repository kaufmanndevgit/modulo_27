<script setup>
  
</script>

<template>
  <div class="container">
    <header class="p-5 mb-4 mt-4 bg-light rounded-3">
      <h1>Meus calculos</h1>
      <p>
        O resultado é: 
      </p>
    </header>
    <form>
      <div class="row">
        <div class="col-md-2">
          <input type="number" placeholder="Digite aqui o numero" class="form-control">
        </div>
        <div class="col-md-2">
          <input type="number" placeholder="Digite aqui o numero" class="form-control">
        </div>
        <div class="col-md-2">
          <select class="form-control">
            <option value="somar">Somar</option>
            <option value="diminuir">Diminuir</option>
            <option value="multiplicar">Multiplicar</option>
          </select>
        </div>
      </div>
    </form> 
  </div>
</template>

<style scoped>

</style>
