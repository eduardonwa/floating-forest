<template>
    <div class="nav text-blue-500">
        <ul class="h-full flex justify-center items-center space-x-8">
            <li>Home</li>
            <li>Contact</li>
            <li>Projects</li>
        </ul>
    </div>
</template>

<script>
</script>

<style>
.nav {
    height: 89px;
}

ul > li {
    font-size: 1.2rem;
    cursor: pointer;
    color: whitesmoke;
    padding: 3px;
}

li:hover {
    border: 2px dashed red;
    padding: 3px;
}
</style>