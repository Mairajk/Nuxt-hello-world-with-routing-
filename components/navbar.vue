<template>
<div>
    <nav>
        <ul>
            <li>
                <NuxtLink to="/">Home </NuxtLink>
            </li>
            <li>
                <NuxtLink to="/about">About </NuxtLink>
            </li>
            <li>
                <NuxtLink to="/gallery">Gallery </NuxtLink>
            </li>
            <li>
                <NuxtLink to="/contact">Contact </NuxtLink>
            </li>

        </ul>
    </nav>
</div>
</template>

<script>
export default {
    name: 'Navbar',
}
</script>
