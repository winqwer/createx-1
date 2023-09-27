<template>
    <form class="question">
        <label for="name">Name<input type="text" placeholder="Your name"></label>
        <label for="phone">Phone<input type="text" placeholder="Your phone"></label>
        <label for="massege">Message<input class="question_width" type="text" placeholder="Your message"></label>
        <button>send</button>
    </form>
</template>

<script>
export default {
    data() {


    }
}


</script>
<style>

.question label input::placeholder{
    color: var(--gray-600, #9A9CA5);

/* small/regular */
font-family: Ubuntu;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: 150%; /* 21px */
padding: 0 0 0 16px;
}

.question label input {
    width: 260px;
    height: 44px;
    border-radius: 4px;
    border: 1px solid var(--gray-400, #D7DADD);
    background: var(--gray-200, #F4F5F6);
    margin: 8px 0 0 0;
}

.question label {
    display: flex;
    flex-direction: column;
    color: var(--gray-800, #424551);

/* small/regular */
font-family: Ubuntu;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: 150%; /* 21px */
   
}

.question {

    background-color: #fff;
    display: flex;
    justify-content: center;
    align-items: flex-end;
    gap: 24px;

}

.question>button {
    border: none;
    border-radius: 4px;
    background: var(--primary, #FF5A30);
    width: 104px;
    height: 48px;
    color: var(--white, #FFF);
    text-align: center;
    font-family: Ubuntu;
    font-size: 14px;
    font-style: normal;
    font-weight: 700;
    line-height: 44px;
    /* 314.286% */
    letter-spacing: 0.5px;
    text-transform: uppercase;

}
</style>