<template>
    <div id="game">
        <logout-button></logout-button>
        Game Page
    </div>
</template>

<script>
import LogoutButton from '@/components/LogoutButton.vue';

export default {
    name: 'Game',
    components: { LogoutButton }
}
</script>