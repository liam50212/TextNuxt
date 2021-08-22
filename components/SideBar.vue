<template>
    <div>
        <b-button v-b-toggle.sidebar-variant class="side mt-1" variant="light" style="border-color: #fff;">
            <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-list"
                viewBox="0 0 16 16">
                <path fill-rule="evenodd"
                    d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z" />
            </svg>
        </b-button>
        <b-sidebar id="sidebar-variant" shadow>
            <div class="px-3 py-2 mt-3">
                <b-list-group>
                    <div v-for="(pro, index) in pros" :key="index" class="d-flex">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                            class="bi bi-justify-left mt-3" viewBox="0 0 16 16">
                            <path fill-rule="evenodd"
                                d="M2 12.5a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 0 1h-7a.5.5 0 0 1-.5-.5zm0-3a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5zm0-3a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5zm0-3a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5z" />
                        </svg>
                        <b-list-group-item class="border-0" href="#">{{ pro.title }}
                        </b-list-group-item>
                    </div>
                    <hr style="width: 100%;">

                    <div v-for="(pro1, index) in pros1" :key="index" class="d-flex">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                            class="bi bi-justify-left mt-3" viewBox="0 0 16 16">
                            <path fill-rule="evenodd"
                                d="M2 12.5a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 0 1h-7a.5.5 0 0 1-.5-.5zm0-3a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5zm0-3a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5zm0-3a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5z" />
                        </svg>
                        <b-list-group-item class="border-0" href="#">{{ pro1.title }}
                        </b-list-group-item>
                    </div>
                    <hr style="width: 100%;">

                    <p style="font-size: 15px;">訂閱內容</p>
                    <div v-for="(pro2, index) in pros2" :key="index" class="d-flex">
                        <img :src="pro2.icon" alt="" class="mt-2" style="width: 24px;height: 24px;border-radius: 24px;">
                        <b-list-group-item class="border-0" href="#">{{ pro2.title }}
                        </b-list-group-item>
                    </div>
                    <hr style="width: 100%;">

                    <p style="font-size: 15px;">更多 YOUTUBE 功能</p>
                    <div v-for="(pro3, index) in pros3" :key="index" class="d-flex">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                            class="bi bi-justify-left mt-3" viewBox="0 0 16 16">
                            <path fill-rule="evenodd"
                                d="M2 12.5a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 0 1h-7a.5.5 0 0 1-.5-.5zm0-3a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5zm0-3a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5zm0-3a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5z" />
                        </svg>
                        <b-list-group-item class="border-0" href="#">{{ pro3.title }}
                        </b-list-group-item>
                    </div>
                    <hr style="width: 100%;">

                    <div v-for="(pro4, index) in pros4" :key="index" class="d-flex">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                            class="bi bi-justify-left mt-3" viewBox="0 0 16 16">
                            <path fill-rule="evenodd"
                                d="M2 12.5a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 0 1h-7a.5.5 0 0 1-.5-.5zm0-3a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5zm0-3a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5zm0-3a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5z" />
                        </svg>
                        <b-list-group-item class="border-0" href="#">{{ pro4.title }}
                        </b-list-group-item>
                    </div>
                </b-list-group>
            </div>
        </b-sidebar>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                pros: [
                    {
                        title: '首頁',
                    },
                    {
                        title: '探索',
                    },
                    {
                        title: '訂閱內容',
                    },
                ],
                pros1: [
                    {
                        title: '媒體庫',
                    },
                    {
                        title: '觀看記錄',
                    },
                    {
                        title: '你的影片',
                    },
                    {
                        title: '稍後觀看',
                    },
                ],
                pros2: [
                    {
                        title: '三立新聞網SETN',
                        icon: 'https://yt3.ggpht.com/8pTD2vQWUxcT8cCR0Xu2sLO_3P8c9sYubGuoBUlahh_ASEDIrKrTxjP1vRf_vU7tvIC1tE-XTH4=s88-c-k-c0x00ffffff-no-rj'
                    },
                    {
                        title: 'Muse木棉花-TW',
                        icon: 'https://yt3.ggpht.com/ytc/AKedOLTTHp_J9at0FzmyJ2n9ODG37zTxsHfiQg3MgVrjYA=s88-c-k-c0x00ffffff-no-rj'
                    },
                    {
                        title: '布魯斯前端',
                        icon: 'https://yt3.ggpht.com/ytc/AKedOLQ_XCcQ3OvhEZ8-mHbVnYbNtJ-89d2e93EoUwAR=s88-c-k-c0x00ffffff-no-rj'
                    },
                    {
                        title: 'Highlight NBA',
                        icon: 'https://yt3.ggpht.com/ytc/AKedOLSOAP_l3VMUyZzGTnycC2g6w0vA3njRKJaboroE2w=s88-c-k-c0x00ffffff-no-rj'
                    },
                    {
                        title: 'Pablo Cimadevila',
                        icon: 'https://yt3.ggpht.com/ytc/AKedOLRZzktyP1c8QkchWFjUC8nU6iyeijM563r_OA4N6A=s88-c-k-c0x00ffffff-no-rj'
                    },
                    {
                        title: 'GEM鄧紫棋',
                        icon: 'https://yt3.ggpht.com/ytc/AKedOLTDfaToBSHyjN59dgb831O040QCWpjcMEaixPWvSg=s88-c-k-c0x00ffffff-no-rj'
                    },
                    {
                        title: 'Aries艾瑞絲',
                        icon: 'https://yt3.ggpht.com/vDkj9GLpI4Rtgny2KDhfYtUqPJ94uUJOWmYpLgtc56_oOeVTQHLvDwFHVTu73jM17l7ZEWl0Pw=s88-c-k-c0x00ffffff-no-rj'
                    },
                ],
                pros3: [
                    {
                        title: 'YouTube Premium',
                    },
                    {
                        title: '電影',
                    },
                    {
                        title: '遊戲',
                    },
                    {
                        title: '直播',
                    },
                    {
                        title: '體育',
                    },
                ],
                pros4: [
                    {
                        title: '設定',
                    },
                    {
                        title: '檢舉記錄',
                    },
                    {
                        title: '說明',
                    },
                    {
                        title: '提供意見',
                    },
                ],
            }
        }
    }
</script>

<style>
    .side {
        position:fixed;
        z-index: 9998;
        top: 12px;
    }

    .b-icon.bi {
        margin-top: 15px;
    }

    .b-sidebar-header,
    .b-sidebar-body {
        background-color: #fff;
    }

    .b-sidebar {
        width: 240px;
        z-index: 9999;
    }

    @media (max-width:375px) {
        
    }
</style>