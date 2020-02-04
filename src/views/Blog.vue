<template>
    <div>
        <div>
            <h1>{{pageName}}</h1>
            <p>{{pageDesc}}</p>
            <div class="container">
                <div class="alert alert-primary" role="alert">
                    A simple primary alert—check it out!
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            pageName:"blog page",
            pageDesc:"lorem upsum"
        }
    },
    name:"Blog"
}
</script>