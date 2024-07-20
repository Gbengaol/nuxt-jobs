<script setup lang="ts">
import { Toaster } from "@/components/ui/sonner";
import "./assets/css/main.css";
</script>

<template>
  <NuxtLayout>
    <NuxtRouteAnnouncer />
    <Toaster richColors closeButton position="top-right" :visibleToasts="3" />
  </NuxtLayout>
</template>
