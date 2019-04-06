<template>
  <section class="container">
    <div>
      <button @click="inc">
        {{ value }}
      </button>
    </div>
  </section>
</template>
<script>
export default {
  computed: {
    value() {
      return this.$store.state.counter.count
    }
  },
  methods: {
    inc: function () {
      this.$store.commit(`counter/increment`, 1)
    }
  }
}
</script>
