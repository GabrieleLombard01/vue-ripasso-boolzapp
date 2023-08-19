<script >
import AppUserSection from './SidebarContents/AppUserSection.vue';
import AppNotifications from './SidebarContents/AppNotifications.vue';
import AppSearch from './SidebarContents/AppSearch.vue';
import AppContacts from './SidebarContents/AppContacts.vue';
export default {
    components: { AppUserSection, AppNotifications, AppSearch, AppContacts },
}
</script>

<template>
    <section id="sidebar" class="col-4 p-0 h-100 bg-light-gray">

        <!-- User section -->
        <AppUserSection />

        <!-- Notifications -->
        <AppNotifications />

        <!-- Search contacts -->
        <AppSearch />

        <!-- Contacts list -->
        <AppContacts />

    </section>
</template>

<style scoped>
/* --- STYLE HERE... --- */

/*CSS reset*/

/*Pseudo-classes*/

/*Generics*/

/*Utilties*/
</style>