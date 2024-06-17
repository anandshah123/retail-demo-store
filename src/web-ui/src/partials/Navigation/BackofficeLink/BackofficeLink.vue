<template>
  <router-link to="/backoffice" aria-label="Backoffice" class="backoffice"><BackofficeIcon class="icon"></BackofficeIcon></router-link>
</template>

<script>
import BackofficeIcon from './BackofficeIcon.vue';

export default {
  name: 'BackofficeLink',
  components: { BackofficeIcon },
};
</script>

<style>
.support {
  width: 40px;
}

.icon {
  transition: fill 150ms ease-in-out;
}

.support:hover .icon,
.support:focus .icon {
  fill: var(--blue-600);
}
</style>
