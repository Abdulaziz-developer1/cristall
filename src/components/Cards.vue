<template>
    <h1>Продажи в рознице</h1>
    <br>
    <div class="cards">
        <div class="card" v-for="e in arr" :key="e">
            <img src="https://picsum.photos/id/1/400/100" alt="img of product">
            <div class="text">
                <div class="column">
                    <div>
                        <h3>Коллаж</h3>
                        <p>Амурская улица, 22А</p>
                    </div>
                    <p>Пн - Пт 9:00 - 19:00</p>
                </div>
                <button>Забронировать продукцию</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            arr: [1, 2, 3, 4, 5]
        }
    }
}
</script>

<style scoped>
h1{
    width: 99vw;
    text-align: center;
}
.cards {
    display: flex;
    flex-wrap: wrap;
    /* gap: 20px; */
    width: 99vw;
    justify-content: space-between;
    padding: 30px;
}

.card {
    width: 48%;
    height: 260px;
    border-radius: 20px;
    border: 1px solid gray;
    margin-top: 20px;
}

.card img {
    border-radius: 20px;
    width: 100%;
}
.text{
    align-items: center;
}
.text,
.text * {
    display: flex;
    gap: 25px;
    font-size: .99em;
}

button{
    padding: 10px 20px;
    border-radius: 30px;
    width: 50%;
    height: 35px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.column{
    display: block !important;
}
</style>