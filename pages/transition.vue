<template>
  <div>
    <transition-group tag="form">
      <div v-for="(value, key) in formData" :key="key" class="flex">
        <input
          v-model="formData[key].heroineName"
          type="text"
          placeholder="ヒロインの名前"
        >
        <button @click="removeBtn(key)">
          Remove
        </button>
      </div>
    </transition-group>
    <button @click="addBtn()">
      Add
    </button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      formData: [
        {
          heroineName: ''
        }
      ]
    }
  },
  methods: {
    addBtn() {
      this.formData.push({ heroineName: '' })
    },
    removeBtn(key) {
      if (this.formData.length !== 1) {
        this.formData.splice(key, 1)
      }
    }
  }
}
</script>

<style scoped>
.flex {
  display: flex;
}

.v-enter-active {
  transition: all 1.5s ease-in;
}

.v-leave-active {
  transition: all 1.5s ease-out;
}

.v-enter, .v-leave-to {
  transform: translateY(50px);
  opacity: 0;
}
</style>
