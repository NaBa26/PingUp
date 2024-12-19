<script setup>
    import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';
    import { faComment, faUser, faCog, faPhone } from '@fortawesome/free-solid-svg-icons';
</script>

<template>
<div class="functionalities-sidebar">
    <div class="sidebar-items">
        <div class="sidebar-item active mx-4 mt-4" id="chat">
            <FontAwesomeIcon :icon="faComment" size="2x" /> 
        </div>
        <div class="sidebar-item mx-4 mt-4" id="ping">
            <FontAwesomeIcon :icon="faPhone" size="2x" /> 
        </div>
        <div class="sidebar-item mx-4 mt-4" id="settings">
            <FontAwesomeIcon :icon="faCog" size="2x" /> 
        </div>
        <div class="sidebar-item mx-4 mt-4" id="profile">
            <FontAwesomeIcon :icon="faUser" size="2x" /> 
        </div>
    </div>
</div>
</template>