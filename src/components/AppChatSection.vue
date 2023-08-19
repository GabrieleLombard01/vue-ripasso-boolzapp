<script >
import AppChatHeader from './ChatContents/AppChatHeader.vue';
import AppChatMessages from './ChatContents/AppChatMessages.vue';
import AppChatFooter from './ChatContents/AppChatFooter.vue';
export default {
    components: { AppChatHeader, AppChatMessages, AppChatFooter },
}
</script>

<template>
    <section id="chat" class="col-8 p-0 h-100 bg-chat-color d-flex flex-column">

        <!-- Chat header -->
        <AppChatHeader />

        <!-- Chat messages -->
        <AppChatMessages />

        <!-- Chat footer -->
        <AppChatFooter />

    </section>
</template>

<style scoped>
/* --- STYLE HERE... --- */

/*CSS reset*/

/*Pseudo-classes*/

/*Generics*/

/*Utilties*/
</style>