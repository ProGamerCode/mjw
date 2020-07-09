<template>
  <div>

    <button @click="toggleModal">Open</button>

    <transition name="fade">
      <div v-if="isOpen" class="modal">
        <p>
          <button @click="toggleModal">Close</button>
        </p>
          <iframe width="760" height="515" src="https://www.youtube-nocookie.com/em></iframe>
        
      </div>
    </transition>
  </div>
</template>

<script>
export default {
name: 'Modal',
  data() {
    return {
      isOpen: false
    }
  },
  methods: {
    toggleModal() {
      this.isOpen = !this.isOpen
    }
  }
}
</script>
