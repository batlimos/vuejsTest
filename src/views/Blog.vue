<template>
    <div>
        <div>
            <h1>{{pageName}}</h1>
            <p>{{pageDesc}}</p>
            <div class="container text-left">
                
                <div class="row">
                    <div class="blogPostArea col-md-8">
                        <blogPost v-for="post in posts" :key="post.id" 
                        :views="post.views"
                        :date="post.date"
                        :title="post.title"
                        :content="post.content"
                        :author="post.author"
                        :cat="post.category"
                        />
                        
                    </div>
                    <div class="sideBarArea col-md-4">
                        <blogside/>
                    </div>
                </div>
                
            </div>
        </div>
    </div>
</template>

<script>

import blogPost from "@/components/Blog/BlogPost";
import blogside from "@/components/Blog/BlogSidebar";
import jsonPost from "../json/JsBlogPost.json";

export default {
    data() {
        return {
            pageName:"blog page",
            pageDesc:"lorem upsum",
            posts:jsonPost
        }
    },
    name:"Blog",
    components:{
        blogPost,
        blogside
    }
}
</script>