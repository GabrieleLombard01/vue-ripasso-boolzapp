<script >
	//LOGIC HERE...
</script>

<template>
    <!-- Chat messages -->
    <section class="flex-grow-1 overflow-auto bg-chat-image">
        <ul class="px-3">
            <li class="message-container p-3 sent">
                <div class="message p-2 rounded-3">
                    <p>Hai portato a spasso il cane?</p>
                    <time datetime="2021-08-03T09:53">31/01/2022 - 12:13</time>
                </div>
            </li>
            <li class="message-container p-3 received">
                <div class="message p-2 rounded-3">
                    <p>Si!</p>
                    <time datetime="2021-08-03T09:53">31/01/2022 - 12:14</time>
                </div>
            </li>
        </ul>
    </section>
</template>

<style>
/* --- MESSAGES --- */
.message-container {
    display: flex;
}

.message-container.sent {
    justify-content: flex-end;
}

.message-container.received {
    justify-content: flex-start;
}

.message-container.sent .message {
    background-color: var(--sent-color);
}

.message-container.received .message {
    background-color: #fff;
}

.message-container .message p {
    margin-bottom: 0;
}

.message-container .message time {
    display: block;
    text-align: right;
    font-size: 11px;
    color: var(--gray);
}</style>