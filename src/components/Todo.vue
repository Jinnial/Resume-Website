<template>
  <div>
      <div class='ui centered card'>
          <div class="content">
              <div class="header">{{item.title}}</div>
              <div class="meta">{{item.project}}</div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Todo',
  props: ['item']
}
</script>
<style>

</style>
