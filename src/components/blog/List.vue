<script setup lang="ts">
import Item from '@/components/blog/Card.vue';

const title = 'Roof party normcore before they sold out, cornhole vape';
const content = `Live-edge letterpress cliche, salvia fanny pack humblebrag narwhal portland. VHS man braid palo santo hoodie brunch trust fund. Bitters hashtag waistcoat fashion axe chia unicorn. Plaid fixie chambray 90's, slow-carb etsy tumeric. Cray pug you probably haven't heard of them hexagon kickstarter craft beer pork chic.`

// iterate an array from props
</script>

<template>
    <!-- v-for items -->
    <item :title="title" :content="content" />
</template>