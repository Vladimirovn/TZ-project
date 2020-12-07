<template>
  <div class="container">
    <form action="#" class="conditionOne">
      <h3>Добавить опрос</h3>
        <div class="try">
          <p>
            <label for="conditionOne">Условие 1</label>
            <select
              id="conditionOne"
              v-model="Condition"
              name="condition"
            >
              <option>Возраст респондента</option>
              <option>Рост респондента</option>
              <option>Размер ноги респондента</option>
            </select>
          </p>
        </div>
     </form>
  </div>
</template>

<script>
export default {


}
</script>

<style>

</style>
