<template>
    <div id="main" :class="isDay ? 'day' : 'night'">
    <div class="container">
        <h1 id="title">Weather Closet</h1>
        <form id="searchBox">
            <input type="text" placeholder="도시를 선택하세요...">
        </form>

        <div>
            <div icon="sunny" v-if="clearSky" data-label="Sunny">
                <span class="sun"></span>
            </div>
        </div>
    </div>
</template>