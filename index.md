---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

title: Be a blue bubble on Android

head:
  - - meta
    - name: description
      content: "Finally, be a blue bubble on Android. Chat everywhere, seamlessly."
  - - meta
    - http-equiv: Content-Language
      content: en
  - - script
    - src: https://challenges.cloudflare.com/turnstile/v0/api.js

hero:
  name: "OpenBubbles"
  text: "Finally, be a blue bubble on Android"
  tagline: iMessage + FaceTime and more for your Android number
  image:
    src: /MessagesDesktop-joined3.png
    alt: OpenBubbles
  actions:
    - theme: brand
      text: Join the waitlist
      link: /#hosted-waitlist
    - theme: alt
      text: Self-host
      link: /quickstart

features:
  - icon: <svg width="300" height="300" version="1.1" viewBox="0 0 256 256" xmlns="http://www.w3.org/2000/svg"> <g transform="translate(25.6 25.6) scale(.8)"> <g fill="#3087e5" font-family="none" font-size="none" font-weight="none" stroke-dasharray="" stroke-miterlimit="10" text-anchor="none" style="mix-blend-mode:normal"> <g transform="translate(0) scale(1.1378)"> <g transform="translate(20.781 38.456) scale(.99337 1.1516)"> <path transform="translate(-83.843 -112.25) scale(.9811)" d="m169.66 111.74c-51.203 0-92.712 27.793-92.712 62.079 0 34.281 41.509 62.075 92.712 62.075 49.428 0 89.808-25.901 92.55-58.535v-7.0791c-2.7414-32.637-43.122-58.539-92.55-58.539z" opacity=".75"/> <path transform="translate(-85.557 -111.76)" d="m184.82 126.95c-50.394 0-91.418 26.013-91.418 58.013 0 0.38282-2.8e-4 0.73405 0.03097 1.1169 0.95703 31.461 41.562 56.895 91.387 56.895 22.023 0 43.317-5.0665 59.989-14.277 0.28516-0.16015 0.66802-0.12924 0.89067 0.12467 5.832 5.6445 24.895 7.3635 32.863 7.8752-1.7227-0.98828-3.9231-2.3592-6.1536-4.1443-1.0508-0.82813-2.038-1.719-2.9286-2.5823-2.2969-2.2617-4.0508-4.6525-5.2305-7.1056-1.082-2.2656-1.6881-4.5944-1.7858-6.9187 0-0.22266 0.06641-0.41353 0.22267-0.57369 8.8945-9.1484 13.583-19.636 13.583-30.41 0-9.5312-3.6368-18.552-10.106-26.489-15.203-18.711-45.966-31.524-81.344-31.524z" opacity=".75"/> </g> </g> </g> </g> </svg>
    title: Join iPhone Group Chats
    details: Be a blue bubble on Android. Chat everywhere, seamlessly.
  - icon: 📹
    title: Join FaceTime calls
    details: Receive & place FaceTime calls on any device. Join existing calls without links!
  - icon: 🖼️
    title: iCloud Shared Albums
    details: Share your favorite moments with your family and friends on any phone you want.
  - icon: 🔒
    title: True end-to-end encryption
    details: No one can read your messages, not even OpenBubbles or Apple.
  - icon: 🎉
    title: Reactions and Replies
    details: React, reply, edit, and unsend formatted messages with your friends.
  - icon: 🌐
    title: Serverless
    details: Unlike other apps, OpenBubbles talks directly to Apple. One-time access to a Mac or an always-online iPhone is required for activation
  
---

<style>
:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(120deg, #5CA7F8 30%, #256cb9);
}

@media (min-width: 960px) {
    .image-src {
        max-width: 420px;
        max-height: 320px;
    }
}
@media (min-width: 640px) {
    .image-src {
        max-width: 336px;
        max-height: 256px;
    }
}
.image-src {
    max-width: 252px;
    max-height: 192px;
}

@media (max-width: 767px) {
    .background {
      display: block !important;
    }
    .vp-doc {
      padding: 0 !important;
    }
    .VPHome {
      margin-bottom: 0 !important;
    }
}

.footer {
  padding: 200px 10px;
  padding-top: 50px;
  text-align: center;
  display: block;
  position: relative;
  overflow: hidden;
}

.footer img {
  width: 70px;
  display: inline;
  padding: 5px;
  border-radius: 6px;
  background-color: var(--vp-c-default-soft);
  margin-bottom: 50px;
}

.footer h3 {
  margin: 25px 0 !important;
  font-weight: 400 !important;
}

.footer a {
  text-decoration: inherit !important;
}

.background {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: -webkit-linear-gradient(300deg, #5CA7F8 30%, #256cb9);
  z-index: -100;
  mask-image: linear-gradient(to top, rgba(0,0,0,.8), rgba(0,0,0,.1) 60%, rgba(0,0,0,0) 80%);
  display: none;
}

</style>

<br>
<br>
<br>
<br>

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
        margin-top: 10px;
        margin-bottom: 10px;
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
        margin-top: 15px;
        font-family: Inter, ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    }

    form {
      background-color: var(--vp-c-bg);
      text-align: left;
      padding: 20px;
      border-radius: 10px;
    }
</style>

<script>
  let turnstilePassed = false;
  window.turnstileReady = (_token) => {
    turnstilePassed = true;
    setTimeout(() => turnstilePassed = false, 300 * 1000);
  }

  window.checkTurnstile = (event) => {
    if (!turnstilePassed) {
      event.preventDefault();
      alert("Please verify you are human before submitting.");
    }
  }
</script>

<div class="footer" id="hosted-waitlist">
  <img src="/icon.png" />
    <h1>Join the waitlist!</h1>
    <h3>Turn your Android phone number into a blue bubble without the need of an iPhone or other Apple device.</h3>

<!-- Intentionally not using vue events, because then that triggers hydration which breaks the turnstile -->
<form action="https://hw.openbubbles.app/waitlist" method="POST" onsubmit="checkTurnstile">
<label for="emailimp">Email</label>
<input type="email" name="email" id="emailimp" placeholder="Enter email here" class="myinput" required/>

<input type="hidden" name="price_okay" value="okay">
<input type="hidden" name="price" value="">

<div style="margin-top: 15px" class="cf-turnstile" data-sitekey="0x4AAAAAABB_VM-Rvy-vlB1W" data-callback="turnstileReady"></div>

<input type="submit" value="Join waitlist">
</form>

There will be a monthly fee for OpenBubbles Hosted. <a href="/quickstart.html#activate-openbubbles">Self-host now for free.</a>
<div class="background" />
</div>


