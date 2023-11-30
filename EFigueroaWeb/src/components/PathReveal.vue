<template>
    <div>
        <a class="sixbtn" href="/ActSixCap" @click="emitEvent"> Return  </a><br><br>
    </div>
</template>
<script>
export default {
  name: "PathReveal",
  props: {
    count: Number  // Define count as a prop
  },
  methods: {
    emitEvent() {
      try {
        // Emit an event to update the count in the parent
        this.$emit('update-count', this.count + 1);
        console.log("clicked");
      } catch (error) {
        console.error(error);
      }
    }
  }
};
</script>
<style></style>
