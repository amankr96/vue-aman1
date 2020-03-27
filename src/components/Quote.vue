<template>
    <div>
      <div class="title">
      <slot name="title"></slot>
      <span style="color:rgb(0,0,0)"><slot name="subtitle">The subtitle</slot></span>
      </div>
      <hr>
      <div class="content">
        <slot name="content"></slot>
      </div>
    </div>
</template>

<script>
export default{
    
}
</script>

<style scoped>
div {
    border: 1px solid rgb(236, 24, 24);
    box-shadow: 1px 1px 2px black;
    background-color: rgb(201, 179, 199);
    padding: 30px;
    margin: auto;
    text-align: center;
}

.title
{
  font-style: italic;
}


</style>