<template>
<div class="footer">
    <div><p class="tag center default">My Blog {{ new Date().getFullYear() }}</p></div>
</div>
</template>

<script>
export default { name: 'footers' }
</script>

<style scoped>
.footer {
    background-color: #1D1D1D;
    padding: 25px;
    margin-top: 20px;
    border-radius: 10px 10px 0px 0px;
}
.tag {
    color: white;
    font-family: 'Inria Serif';
    font-size: 20px;
}
</style>