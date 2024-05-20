<script setup>
import { ref } from 'vue';
import ApplicationLogo from '@/Components/ApplicationLogo.vue';
import Dropdown from '@/Components/Dropdown.vue';
import DropdownLink from '@/Components/DropdownLink.vue';
import NavLink from '@/Components/NavLink.vue';
import ResponsiveNavLink from '@/Components/ResponsiveNavLink.vue';
import { Link } from '@inertiajs/vue3';

const showingNavigationDropdown = ref(false);
</script>

<template>
     <div>
        <div class="min-h-screen bg-gray-50 dark:bg-gray-900">
            <div class="p-4 flex w-full justify-center items-center">
                <div class="w-1/3 h-[150px] bg-gray-300"></div>
            </div>
        </div>
    </div>
</template>
