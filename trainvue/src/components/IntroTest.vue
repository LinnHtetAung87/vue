<template>
  <div>
    <h1>Intro View</h1>
    <h1>{{ msg }}</h1>
    <h1>{{ sms }}</h1>
  </div>
</template>
<script>
export default {
  props: {
    msg: String,
    sms: String,
  },
};
</script>
