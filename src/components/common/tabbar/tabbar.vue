<template>
    <div id="tabbar">
        <slot></slot>
    </div>
</template>

<script>
export default {
    name: 'tabbar'
}
</script>

<style>
#tabbar{
  display: flex;
  background-color: #f6f6f6;
  position: fixed;
  left: 0;
  right: 0;
  bottom: -1px;
  box-shadow: 0 -1px 5px rgba(100,100,100,.2);
}

</style>