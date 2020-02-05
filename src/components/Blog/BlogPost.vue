<template>
    <div class="col-12 thePost">
        <p class="postTitle">{{title}}</p>
        <p class="postTime">{{date}}</p>
        <p class="postContent">{{content}}</p>
        <span class="postView">{{views}}</span>
        <div class="row">
            <div class="col-md-6">
                <span class="authourst spnAutCat">{{author}}</span>
            </div>
            <div class="col-md-6 text-right">
                <span class="catSl spnAutCat">{{cat}}</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    props:["views","cat","title","content","date","author"],
    name:"BlogPost",
}
</script>

<style scoped>
.thePost
{
    background: #fff;
    border-radius: 5px;
    box-shadow: rgba(0, 0, 0, 0.2) 0 2px 8px;
    padding: 3%;
    margin-bottom: 3%;
}
.postTitle
{
    color:#555;
    font-weight: 600;
    font-size: 1.5rem;
}
.spnAutCat
{
    padding: 2%;
    color:#f5f5f5;
    font-weight: bold;
}
.authourst
{
    background: rgb(61, 196, 139);
}
.catSl
{
    background: #EC407A;
}
.postView
{
    padding: 0.2% 0.7%;
    background: rgb(103, 212, 76);
    color:#f5f5f5;
    font-weight: 500;
    position: absolute;
    border-radius: 20%;
    right: 3%;
    top:8%;
}
</style>
