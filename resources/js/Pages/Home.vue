<template>
    <div>Home Page</div>
    <part> component slot for home page </part>
    <br>

    <inertia-link href="/test"> Test </inertia-link>
</template>

<script>
import Part from "../Components/Part";

export default {
    components: {
        Part,
    },
};
</script>
