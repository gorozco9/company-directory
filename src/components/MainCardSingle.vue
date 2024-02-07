<script setup>
import { faker } from '@faker-js/faker'
const fullname = faker.person.fullName() //generate a fake name
</script>


<template>
    {{ fullname }} <br />
</template>