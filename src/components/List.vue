<template>
    <div>
        <h5 @click="$router.push('/detail/0')">{{blog[0].title}}</h5>
        <p>{{blog[0].content}}</p>
    </div>
    <div>
        <h5>{{blog[1].title}}</h5>
        <p>{{blog[1].content}}</p>
    </div>
    <div>
        <h5>{{blog[2].title}}</h5>
        <p>{{blog[2].content}}</p>
    </div>
</template>

<script>
export default {
    name : 'List',
    props : {
        blog : Array,
    },
}
</script>

<style>

</style>