<template>
<div class="form-group">
<div :style="styles">{{label}}</div>
</div>
</template>

<script>
export default {
    props: [
        'label',
        'fontSize',
        'fontWeight'
    ],
    computed: {
        styles() {
            return {
                fontSize: this.fontSize,
                fontWeight: this.fontWeight
            }
        }
    }
}
</script>

<style lang="scss" scoped>

</style>


