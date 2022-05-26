<template>
    <div class="layout-main">
        <Nuxt class="main-session" />
    </div>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator';

import { Subject } from 'rxjs';

export const ShowDetailEv = new Subject<boolean>();

@Component({
    components: {}
})
export default class extends Vue {
    options: any = {
        token: '',
        ft300: 0,
        isload: true
    };

    isDetail = false;

    mounted() {
        
    }
}
</script>

<style>
.layout-main{display: flex;flex-flow: column;}
/* .layout-main .head-session{position: fixed;top: 0px;left: 0px;width: 100%;} */
.layout-main .main-session{height: calc(100vh - 70px);overflow: auto;scroll-behavior: smooth;}
</style>
