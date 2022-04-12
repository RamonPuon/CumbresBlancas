<template>
   <HomeFirst/>
   <HomeNews/>
   <ContactHome/>
</template>

<script>

import HomeFirst from './HomeFirst.vue';
import HomeNews from './HomeNews.vue';
import ContactHome from './ContactHome.vue';

export default {
    name: 'HomeComp',
    components: {
        HomeFirst,
        HomeNews,
        ContactHome
    }
}
</script>