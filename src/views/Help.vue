<template>
    <div>
        <h1>help page</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis, odit. Perspiciatis cum consequatur quam dicta placeat, deserunt iure voluptas eos quaerat facilis ducimus recusandae, vero culpa impedit vitae reprehenderit excepturi?</p>
        <QuiSommes/>
        
    </div>
</template>

<script>
import QuiSommes from '@/components/QuiSommes.vue';


export default {
    name: "Help",
    components: {
        QuiSommes,
        } 
};
</script>
