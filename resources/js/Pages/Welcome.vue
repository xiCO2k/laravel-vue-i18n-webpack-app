<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';
import { trans } from 'laravel-vue-i18n';

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
});

const test = trans('auth.failed')
</script>

<template>
        {{ $t('auth.failed') }}
        {{ $t('auth.password') }}
        {{ test }}
</template>
