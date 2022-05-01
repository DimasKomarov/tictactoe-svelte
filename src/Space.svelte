<!-- Экспортировали переменную -->
<script>
    export let space = "";
</script>

<!-- Стили таблицы и ячеек -->
<style>
    .space {
        border: solid 1px gray;
        height: 125px;
        width: 125px;
        flex: 1;
        font-size: 75px;
        text-align: center;
        line-height: 125px;
        cursor: pointer;
    }
</style>



<!-- Блок див с ником игрока -->
<div class="space">{space}</div>