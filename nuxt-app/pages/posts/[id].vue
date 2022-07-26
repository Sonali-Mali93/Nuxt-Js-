<template>
<p>dynamic link: {{ $route.params.id}}</p>
<ul>
    <li><NuxtLink to="/">Home page</NuxtLink></li>
    <li><NuxtLink to="/about">Contact</NuxtLink></li>
    <li><NuxtLink to="/contact"></NuxtLink></li>
</ul>
<!-- ul>li*4>a -->
</template>