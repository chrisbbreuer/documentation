<template>
  <ClientOnly>
    <div class="route">
      <div>{{ text }}</div>
    </div>
  </ClientOnly>
</template>

<script>
export default {
  name: 'LinkButton',
  props: {
    text: {
      type: String,
      default: '',
    },
  },
}
</script>

<style lang="css" scoped>
div.route {
  display: block;
  text-align: center;
  margin: 3em 0;
}

.route > div {
  display: inline;
  line-height: 1.4;
  padding: 1.25rem 1.75rem;
  margin: 0.85rem 0;
  background-color: #FF4E62;;

  border-color: #21004B;
  border-style: solid;
  border-width: 2px 2px 9px 2px;
  border-radius: 71.3971px;
  overflow: auto;
  color: white;
  font-weight: bold;
  margin-left: auto;
  margin-right: auto;
}
.route > div:hover {
  background-color: #e64658;
}
</style>
