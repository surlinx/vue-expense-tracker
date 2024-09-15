<template>
    <div>
        <h3>Historial</h3>
        <ul id="list" class="list">
            <li v-for="transaction in transactions" v-bind:key="transaction.id">
                {{ transaction.text }}
                <span>-${{ transaction.amount }}</span>
                <button class="delete-btn">X</button>
            </li>

        </ul>

    </div>
</template>
<script>
export default {
    data() {
        return {
            transactions: [
                { id: 1, text: 'floristeria', amount: -20 },
                { id: 2, text: 'Salario', amount: 300 },
                { id: 3, text: 'Libro', amount: -10 },
                { id: 4, text: 'Cámara', amount: 150 },

            ]
        }
    }
}
</script>