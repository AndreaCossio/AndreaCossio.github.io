<script lang="ts">
import profile_image from '$lib/images/profilo_squared.jpg';
import { Avatar } from '@skeletonlabs/skeleton';
</script>

<svelte:head>
    <title>Andrea Cossio</title>
    <meta name="description" content="Andrea Cossio personal website" />
</svelte:head>

<div class="flex w-full flex-col">
    <div class="flex w-full justify-center">
        <Avatar src={profile_image} width="w-48" />
    </div>
    <div class="flex w-full justify-center">
        <h1 class="align-middle text-7xl font-bold text-white">Andrea Cossio</h1>
    </div>
</div>
