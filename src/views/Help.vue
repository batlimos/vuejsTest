<template>
    <div>
        <h1>{{pageName}}</h1>
        <p>{{pageDec}}</p>
    </div>
</template>

<script>



export default {
    data() {
        return {
            pageName: "help page",
            pageDec:"Lorem ipsum dolor sit amet consectetur adipisicing elit."
        }
    },
    name: "Help",
    components: {
        } 
};
</script>
