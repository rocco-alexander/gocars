<template>
  <div class="container">
        <div class="tab-group">
            <div class="tab">Sales</div>
            <div class="tab">Clients</div>
        </div>
    </div>
</template>

<script>

export default {

}

</script>

<style lang="scss" scoped>
.tab-group{
  cursor:pointer;
  margin-left:1rem;
  display: flex;
  align-items: center;
    .tab{
    padding:25px 50px;
    background:#FF6A6A;
    border-radius: 20px 20px 0 0;
    font-size:1.25rem;
    font-weight:bold;
    font-family: system-ui;
    color:white;
      &:hover{
        opacity:.7;
      }
  }
}
</style>