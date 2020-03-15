<template functional>
    <footer class="the-footer flex-wrap justify-between" :class="classes">
        <span>&copy; {{ new Date().getFullYear() }} <a href="https://tripcarte.asia/" target="_blank" rel="nofollow">Tripcarte.Asia</a>, All rights Reserved</span>
    </footer>
</template>

<script>
export default {
    name: "the-footer",
    props: {
        classes: {
            type: String,
        },
    }
}
</script>
