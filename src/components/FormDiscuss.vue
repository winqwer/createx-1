<script>
export default {

}
</script>
<template>
    <form class="form-discuss">
        <div>
            <h5>A quick way to discuss details</h5>
            <label for="name">Name*<input type="text" placeholder="Your name"> </label>
            <label for="phone">Phone*<input type="text" placeholder="Your phone number"></label>
            <label for="email">Email<input type="text" placeholder="Your working email"></label>
            <label for="massege">Massege*<input type="text" placeholder="Your message"></label>
            <label for="checkbox"><input type="checkbox">I agree to receive communications from Createx Construction
                Bureau.</label>
            <button>send request</button>
        </div>
    </form>
</template>

<style>
.form-discuss>div>h5 {
    color: var(--gray-900, #1E212C);
    text-align: center;

    /* h3 */
    font-family: Ubuntu;
    font-size: 28px;
    font-style: normal;
    font-weight: 700;
    line-height: 150%;
    /* 42px */
    margin: 48px 0 4px 0;
}

.form-discuss>div>button {
    border-radius: 4px;
    background: var(--primary, #FF5A30);
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
    width: 174px;
    height: 44px;
    border: none;
    margin: 0 auto;
}

.form-discuss>div>label:nth-child(6) {

    display: flex;
    flex-direction: row;



}

.form-discuss>div>label:nth-child(6)>input {
    height: 16px;
    width: 16px;
    margin: 0 12px 0 0;
}

.form-discuss>div {
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;

    gap: 20px;
    margin: 0 0 48px 0;


}

.form-discuss {

    width: 495px;
    background-color: #fff;
    margin: 0 365px 0 0;

}

.form-discuss>div>label>input {

    border-radius: 4px;
    border: 1px solid var(--gray-400, #D7DADD);
    background: var(--gray-200, #F4F5F6);

    height: 44px;
}
.form-discuss>div>label>input::placeholder{
    color: var(--gray-600, #9A9CA5);
font-family: Ubuntu;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: 150%; /* 21px */
}
.form-discuss>div>label {
    display: flex;
    flex-direction: column;
    width: 415px;
    color: var(--gray-800, #424551);
font-family: Ubuntu;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: 150%; /* 21px */
}

.form-discuss>div>label:nth-child(5)>input {
    height: 66px;
}</style>