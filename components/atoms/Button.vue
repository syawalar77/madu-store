<template>
    <div>
        <button class="btn btn-warning text-white">
            {{ titleBtn }}
        </button>
    </div>
</template>

<script>
export default {
    props: {
        titleBtn: {
            type: String,
            default: 'Submit'
        }
    }

}
</script>

<style>


</style>