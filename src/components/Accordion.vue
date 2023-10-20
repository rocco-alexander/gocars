<template>
  <div class="accordion-container">
  <div class="accordion" id='a'>
    <div class="title"><p>Title</p><div class="d">V</div></div>
    <div class="accordion-content">
      <div>
<!--    Content Here      -->
        
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
*{
  padding:0;
  margin:0;
}
.accordion{
    cursor:pointer;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    color: white;
    margin-bottom: 1px;
  .title{
    display:flex;
    justify-content: space-between;
    align-items: center;
  }
  background:#FF6A6A;
  padding:1rem;
  &.open{
    .accordion-content{
      grid-template-rows: 1fr;
    }
  }
  .accordion-content{
    display:grid;
    grid-template-rows: 0fr;
    transition: grid-template-rows 500ms;
    >div{
      overflow:hidden;
    }
  }
}
</style>