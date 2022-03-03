<template>
    <div class="nav text-blue-500">
        <ul class="navbar h-full flex justify-center items-center space-x-8">
            <li class="nav-link">Home</li>
            <li class="nav-link">Contact</li>
            <li class="nav-link">Projects</li>
        </ul>
    </div>
</template>

<script>
</script>

<style>
.nav {
    height: 89px;
}

.navbar {
    font-size: 1.2rem;
    cursor: pointer;
    color: whitesmoke;
    padding: 3px;
    transition: .3s;
    font-weight: bold;
}

.nav-link:hover {
    color: red;
    font-weight: bold;
}
</style>