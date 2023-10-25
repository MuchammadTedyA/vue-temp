<template>
<div class="form-check">
  <input class="form-check-input" type="checkbox" :value="name" :id="name" :checked="checked">
  <label class="form-check-label" :for="name">
    {{label}}
  </label>
</div>
</template>

<script>
    export default{
        name: 'CheckTag',
        props: ["name","checked"],
    }
</script>
