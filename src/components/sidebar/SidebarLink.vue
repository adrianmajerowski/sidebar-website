<script>
import { computed } from 'vue'
import { useRoute } from 'vue-router'
import { collapsed } from './state'

export default {
  props: {
    to: { type: String, required: true },
    icon: { type: String, required: true }
  },
  setup(props) {
    const route = useRoute()
    const isActive = computed(() => route.path === props.to)
    return { isActive, collapsed }
  }
}
</script>

<template>
  <router-link :to="to" class="link" :class="{ active: isActive }">
    <i class="icon" :class="icon" />
    <transition name="fade">
      <span v-if="!collapsed">
        <slot />
      </span>
    </transition>
  </router-link>
</template>

<style scoped>
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.1s;
}

.fade-enter,
.fade-leave-to {
  opacity: 0;
}

.link {
  display: flex;
  align-items: center;
  font-family: 'Poppins';
  font-style: normal;

  cursor: pointer;
  position: relative;
  font-weight: 600;
  font-size: 13px;
  user-select: none;
  

  margin: 0.1em 0;
  padding: 0.4em;
  border-radius: 0.25em;
  height: 2em;

  color: #747381;
  text-decoration: none;
}

.link:hover {
  background-color: rgba(129, 128, 128, 0.11);
}

.link.active {
  background-color: rgba(230, 230, 230, 0.11);
}

.link .icon {
  flex-shrink: 0;
  width: 25px;
  margin-right: 10px;
}
</style>
