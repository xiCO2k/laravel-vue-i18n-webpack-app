<script setup>
import { loadLanguageAsync } from 'laravel-vue-i18n';
</script>

<template>
        {{ $t('Welcome!') }} <br><br>
        <button @click="loadLanguageAsync('pt')">Change Locale to PT</button>
</template>
