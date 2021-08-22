<template>
    <div class="nav-button py-1 mb-5 mt-3">
        <div class="button-list d-flex px-3 justify-content-center">
            <button type="button" class="btn1 btn-secondary">All</button>
            <button type="button" class="btn2 btn-secondary">Music</button>
            <button type="button" class="btn3 btn-secondary">One Piece</button>
            <button type="button" class="btn4 btn-secondary">Pet</button>
            <button type="button" class="btn5 btn-secondary">G.E.M</button>
            <button type="button" class="btn6 btn-secondary">Eating</button>
            <button type="button" class="btn7 btn-secondary">Piano</button>
            <button type="button" class="btn8 btn-secondary">Basketball</button>
            <button type="button" class="btn9 btn-secondary">Baseball</button>
            <button type="button" class="btn10 btn-secondary">Love songs</button>
            <button type="button" class="btn11 btn-secondary">Cooking</button>
            <button type="button" class="btn12 btn-secondary">Rap show</button>
        </div>
    </div>
</template>

<style>
    .nav-button {
        width: 80%;
        position: absolute;
        top: 7%;
        left: 15%;
    }

    .btn-secondary {
        width: 100px;
        height: 30px;
        border-radius: 30px;
        line-height: 15px;
        white-space: nowrap;
        margin-right: 10px;
        background-color: #E5E5E5;
        color: black;
    }

    @media (max-width:1440px) {

        .nav-button {
            left: 12%;
        }
    }

    @media (max-width:1100px) {

        .nav-button {
            left: 9%;
        }
    }

    @media (max-width:765px) {

        .nav-button {
            left: 7%;
        }

        .btn10,
        .btn11,
        .btn12 {
            display: none;
        }
    }

    @media (max-width:680px) {

        .nav-button {
            left: 10%;
        }

        .btn7,
        .btn8,
        .btn9 {
            display: none;
        }
    }

    @media (max-width:375px) {

        .btn6 {
            display: none;
        }
    }
</style>