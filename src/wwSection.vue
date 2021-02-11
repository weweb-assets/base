<template>
    <div>
        BASEEEEE
        <wwLayout path="wwObjects" class="section-base"></wwLayout>
    </div>
</template>

<script>
export default {
    name: '__COMPONENT_NAME__',
    props: {
        content: Object,
    },
    wwDefaultContent: {
        wwObjects: [],
    },
};
</script>

<style lang="scss" scoped>
.section-base {
    display: flex;
    flex-direction: column;
    align-items: stretch;
}
</style>
