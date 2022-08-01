<template>
    <div id="main_banner">
        <h1>Git pharmacy</h1>
    </div>

</template>

<script>
export default {
    name: 'Banner'
}
</script>

<style scoped>
#main_banner {
    background-image: url('/public/img/farma.jpg');
    background-position: 0 -250px;
    background-size: cover;
    height: 600px;
    display: flex;
    align-items: center;
    justify-content: flex-start;

}

#main_banner h1{
    color: #fff;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
}
</style>