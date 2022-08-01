<template>

    <div class="message-container">
       <p> {{msg}}</p>
       <progress class="progress is-warning is-small" max="100">5%</progress>
    </div>


</template>

<script>
export default {
    name: 'Message',
    props: {
        msg: String
    }
}
</script>

<style scoped>
.message-container {
    color: #222;
    background-color: #f0ebba;
    border: 2px solid #fcba03;
    border-radius: 5px;
    padding: 10px;
    max-width: 400px;
    margin: 30px auto;
    border-left: 4px solid #fcba03;
}

progress{
    background-color: #222;
}
</style>