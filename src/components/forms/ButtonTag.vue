<template>

<button 
    :type="type" 
    class="btn btn-info">

</button>

</template>

<script>
export default{
    name: 'ButtonTag',
    props: ["type"]

}

</script>