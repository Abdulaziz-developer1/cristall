<template>
  <header>
    <div>
      <h2>Cristall</h2>
      <button class="katalog">Каталог</button>
      <ul>
        <li>Оптовые продажи</li>
        <li>Продажи в рознице</li>
        <li>Контакты</li>
        <li>Вакансии</li>
        <li>Отзывы</li>
      </ul>
    </div>
    <div>
      <button class="whiteBtn">Личный кабинет</button>
    </div>
  </header>
</template>

<script>
export default {
}
</script>

<style scoped>
h2{
  color: #A16341;
}
header {
  display: flex;
  justify-content: space-between;
  width: 99vw;
  padding: 30px;
}

header * {
  display: flex;
  gap: 40px;
  align-items: center;
}

button{
  padding: 10px 20px;
  border-radius: 20px;
  border: none;
}

.whiteBtn{
  background: #fff;
  color: #000;
  border: 2px solid;
}

.katalog{
  background: #A16341;
  color: #fff;
}
</style>