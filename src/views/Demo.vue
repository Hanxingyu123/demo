<template>
    <div>
        <table>
            <tr>
                <td>标题1</td>
                <td>标题2</td>
            </tr>
            <tr>
                <td>内容1</td>
                <td>内容2</td>
            </tr>
        </table>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
table {
    width: 500px;
    border-collapse:collapse;
    margin: 0 auto;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    td {
        border: 1px solid #ccc;
        height: 50px;
    }
}
</style>