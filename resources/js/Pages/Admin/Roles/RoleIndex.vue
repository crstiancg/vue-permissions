<script setup>
import AdminLayout from '@/Layouts/AdminLayout.vue';
import { Head } from '@inertiajs/vue3';
</script>

<template>
    <Head title="Administrador" />

    <AdminLayout>
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 dark:text-gray-200 leading-tight">Administrador</h2>
        </template>

        <div class="py-4">
            <h1>Welcome Roles</h1>
        </div>
    </AdminLayout>
</template>
