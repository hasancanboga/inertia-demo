<template>
    <div>Test Page</div>
    <part> component slot for test page </part>
    <br>
    <inertia-link href="/"> Home </inertia-link>

</template>

<script>
import Part from '../Components/Part'

export default {
    components:{
        Part,
    }
};
</script>
