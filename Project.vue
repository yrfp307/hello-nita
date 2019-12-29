<template>
    <div class="project-wrap">
        <h2 class="header">Yah Bingung</h2>
        <div class="item-project">
            <img class="logo" alt="Aerosystem logo" src="../assets/spirit-aerosystems-logo.png">
        </div>
        <div class="item-project">
            <img class="logo" alt="Filtech logo" src="../assets/fil-tech-logo.png">
        </div>
        <div class="item-project">
            <img class="logo" alt="Geekfox logo" src="../assets/geek-fox-mascot-logo.png">
        </div>
        <div class="item-project">
            <img class="logo" alt="Aerosystem logo" src="../assets/spirit-aerosystems-logo.png">
        </div>
        <div class="item-project">
            <img class="logo" alt="Filtech logo" src="../assets/fil-tech-logo.png">
        </div>
        <div class="item-project">
            <img class="logo" alt="Geekfox logo" src="../assets/geek-fox-mascot-logo.png">
        </div>
    </div>
</template>

<script>
export default {
    name : 'Project',
}
</script>

<style scoped>

.header {
    margin-bottom: 80px;
    text-align: left;
}
.project-wrap {
    width: 50%;
    overflow: hidden;
    margin: auto;
}

.item-project {
    float: left;
    margin-left: 95px;
    margin-right: 70px;
    margin-bottom: 50px;
    width: 150px;
    height: 100px;
}

.item-project .logo {
    width: 150px;
    height: 100px;
}
</style>