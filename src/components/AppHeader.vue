<template>
    <div class="header">
        <div class="SiteLogo">
            Site Logo
        </div>
        <ul>
            <router-link to="/" tag="li" exact>
                <a href="">Home</a>
            </router-link>
            <router-link to="/about" tag="li">
                <a href="">About</a>
            </router-link>
            <router-link to="/blog" tag="li">
                <a href="">Blog</a>
            </router-link>
            <router-link to="/help" tag="li" replace>
                <a href="">Help</a>
            </router-link>
        </ul>
    </div>
</template>

<script>
export default {
    name:"AppHeader"
}
</script>

<style scoped>
.header
{
    background: #000;
    padding: 5px;
}
.SiteLogo
{
    color: #fff;
    float: left;
    width: 100px;
    padding: 10px;
}
ul
{
    display: flex;
    list-style: none;
    width: calc(100% - 100px);
    justify-content: flex-end;
    margin: 0;
}
ul li
{
    display: inline-flex;
    text-decoration: none;
    color:#fff;
   
    
}
ul li a
{
    color: #fff ;
    text-decoration: none;
    padding: 10px;
    
}


</style>
