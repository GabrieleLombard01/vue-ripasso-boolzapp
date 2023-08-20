<script >
	//LOGIC HERE...
</script>

<template>
    <!-- Search contacts -->
    <div id="search-contacts" class="p-2 flex-shrink-0">
        <i class="fa-solid fa-search text-muted"></i>
        <input type="text" class="w-100" placeholder="Cerca contatto">
    </div>
</template>

<style>
/* Search section */
#search-contacts {
    height: 50px;
    position: relative;
}

#search-contacts .fa-search {
    position: absolute;
    top: 50%;
    left: 20px;
    transform: translateY(-50%);
}

#search-contacts input {
    border: 0;
    height: 100%;
    padding-left: 50px;
}
</style>