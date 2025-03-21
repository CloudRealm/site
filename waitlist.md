---
sidebar: false

prev: false
next: false
aside: false
outline: false

---

<script setup>
    import { ref, onMounted } from 'vue'
    import { useRouter } from 'vitepress'

    onMounted(async () => {
        const res = await fetch('https://hw.openbubbles.app/status');
        if ((await res.json()).available) {
            useRouter().go("/quickstart.html#hosted-monthly-subscription")
        }
    })
</script>

# Hosted waitlist

Get all OpenBubbles features (including turning your Android phone number into a blue bubble) without the need of an iPhone or other Apple device. Monthly subscription is required.

If you don't want to pay, you can host the software yourself on an iPhone: [Activation Instructions](https://openbubbles.app/quickstart.html#activate-openbubbles)

<style>
    label {
        font-weight: 500;
    }
    #badprice:checked ~ #price {
        display: block !important;
    }
    .myinput {
        padding: 10px;
        border: solid 1px var(--vp-button-alt-bg);
        border-radius: 10px;
        width: 100%;
        margin: 10px 0;
    }
    input[type=radio] {
        margin-right: 10px;
    }
    input[type=submit] {
        padding: 0 20px;
        line-height: 38px;
        border: none;
        border-radius: 20px;
        font-size: 14px;
        font-weight: 600;
        background-color: var(--vp-button-brand-bg);
        color: var(--vp-button-brand-text);
        cursor: pointer;
        margin-top: 10px;
    }
</style>

<form action="https://hw.openbubbles.app/waitlist" method="POST">
<label for="emailimp">Email</label>
<input type="email" name="email" id="emailimp" placeholder="Enter email here" class="myinput"/><br>

<input type="radio" id="priceokay" name="price_okay" value="okay" checked>
<label for="priceokay">I'm okay with $10/mo USD</label><br>
<input type="radio" id="badprice" name="price_okay" value="none">
<label for="badprice">Let me know when it's cheaper</label><br>

<input type="number" name="price" id="price" style="display: none;"  class="myinput" placeholder="Preferred price ($USD)">

<input type="submit" value="Join waitlist">
</form>