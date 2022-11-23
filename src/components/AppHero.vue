<script>
export default {
  data() {
    return {
        title : 'La mia jumbotron'
    }
  }
}
</script>

<template>
    <div class="container">
        <h1>{{ title }}</h1>
    </div>
</template>

<style scoped>
*{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

.container{
    width: 1080px;
    height: 50vh;
    background-color: red;
    margin: auto;
    display: flex;
    justify-content: center;
    border-radius: 20px;
}

h1{
    margin-top: 10px;
}
</style>