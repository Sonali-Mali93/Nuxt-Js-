<template>
    <!-- <h3 class="text-blue-600">This is Contact page</h3> -->
    <div class="mt-10">
        <demo></demo>
        <Title>Contact page</Title>
        <table class="border border-black">
            <tr>
                <td>First Name</td>
                <td>Last Name</td>
                <td>Email</td>
                <td>Contacts</td>
            </tr>
            <tr v-for="per in allUser" :key="per">
                <td>{{ per.firstName }}</td>
                <td>{{ per.firstName }}</td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
        </table>
    </div>
</template>
<script>

import demo from '../components/demo.vue';
definePageMeta({
    components: {
        demo,
    }
});
</script>
