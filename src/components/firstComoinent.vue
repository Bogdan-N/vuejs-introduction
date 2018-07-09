<template>
    <div>The first vue component is created! {{ happy }}</div>
</template>

<script>
export default {
  name: "FirstComponent",
  props: {
    happy: String
  }
};
</script>
