<script setup>
    import photoGallary from '../components/photoGallary.vue';
</script>
<template>
    <div class="container">
        <photoGallary></photoGallary>
        <div class="item-ctn">
            <div class="item">
                <div class="item-ctx">
                    <RouterLink to="/"><i class="bi bi-house-door-fill" style="font-size: 50px;"></i></RouterLink><br>
                    <RouterLink to="/">首頁 ｜ HOME</RouterLink>
                </div>
            </div>
            <div class="item">
                <div class="item-ctx">
                    <RouterLink to="/About"><i class="bi bi-file-person-fill" style="font-size: 50px;"></i></RouterLink><br>
                    <RouterLink to="/About">公司簡介 ｜ ABOUT</RouterLink>
                </div>
            </div>
            <div class="item">
                <div class="item-ctx">
                    <RouterLink to="/Product"><i class="bi bi-bricks" style="font-size: 50px;"></i></RouterLink><br>
                    <RouterLink to="/Product">產品介紹 ｜ PRODUCT</RouterLink>
                </div>
            </div>
            <div class="item">
                <div class="item-ctx">
                    <RouterLink to="/Contact"><i class="bi bi-person-lines-fill" style="font-size: 50px;"></i></RouterLink><br>
                    <RouterLink to="/Contact">聯繫我們 ｜ CONTACT</RouterLink>
                </div>
            </div>
        </div><br>
        
        
        
        
    </div>
</template>


<style>
.item-ctn{
    margin-bottom: 20px;
    display: flex;
    justify-content: space-between;
    flex-flow: row wrap;
}
.item{
    width: 110px;
    height: 100px;
    margin-bottom: 20px;
}
.item-ctx{
    height: 100%;
}
</style>