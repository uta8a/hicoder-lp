<template>
    <div>
        <top></top>
        <about></about>
        <news></news>
        <contact></contact>
    </div>
</template>

<script>
import Top from '~/components/Top'
import About from '~/components/About'
import News from '~/components/News'
import Contact from '~/components/Contact'
export default {
    components: {
        Top,
        About,
        News,
        Contact
    }
}
</script>