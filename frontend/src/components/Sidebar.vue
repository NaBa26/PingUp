<template>
<div class="sidebar">
    <div class="sidebar-header">
        <h2>Contacts</h2>
    </div>
    <div class="contacts-list">
        <div class="contact active">
            <span>John Doe</span>
        </div>
        <div class="contact">
            <span>Jane Smith</span>
        </div>
        <div class="contact">
            <span>Mike Johnson</span>
        </div>
        <div class="contact">
            <span>Sarah Brown</span>
        </div>
        <div class="contact">
            <span>David White</span>
        </div>
        <!-- Add more contacts here -->
    </div>
</div>
</template>

<style scoped>
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f7f8fa;
}

/* Sidebar Styling */
.sidebar {
    width: 250px;
    height: 100vh;
    background-color: #3f0e40;
    color: white;
    display: flex;
    flex-direction: column;
    padding: 20px;
    position: fixed;
}

.sidebar-header h2 {
    font-size: 1.5em;
    color: white;
    margin-bottom: 20px;
    font-weight: bold;
}

.contacts-list {
    flex-grow: 1;
    margin-top: 20px;
    overflow-y: auto;
}

.contact {
    padding: 12px;
    margin: 8px 0;
    border-radius: 8px;
    cursor: pointer;
    transition: background-color 0.2s ease;
}

.contact:hover {
    background-color: #4a154b;
}

.contact.active {
    background-color: #6a1b9a;
}

.contact span {
    font-size: 1.1em;
    font-weight: bold;
    color: white;
}
</style>