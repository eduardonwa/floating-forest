<template>
    <div class="contact p-8">
        <span class="w-2/3 text-xl text-white leading-9 font-semibold">
            Hey! 👋 Im Eduardo, Im a graphic designer and I do web design, video editing and play the guitar, yes all from Mexico 🇲🇽 😂.
            Honestly, nobody likes to read a bunch of text unless you're a news site or selling something, I don't want to waste your time, im just here to let
            you know I can help you design a logo, an infographic, a website, a banner, edit a video, you name it. 🤓
        </span>
        <img class="w-64" src="/profile.png" alt="">
        <div class="social-media">
            <ul class="social-media-links h-80">
                <li>
                    <a href="mailto:eduardongua@hotmail.com?&subject=Hey Eduardo">
                        <img class="w-12 bg-gray-300 rounded-full" src="/email.png" alt="">
                    </a>
                </li>
                <li>
                    <a href="https://www.linkedin.com/in/hola-eduardo/">
                        <img class="w-12 bg-blue-500 rounded-full" src="/linkedin.png" alt="">
                    </a>
                </li>
                <li>
                    <a href="https://www.instagram.com/guarpig/">
                        <img class="w-12 bg-gradient-to-r from-yellow-300 via-red-500 to-purple-800  rounded-full" src="/instagram.png" alt="">
                    </a>
                </li>
                <li>
                    <a href="https://www.twitch.tv/warpig3">
                        <img class="w-12 bg-purple-500 rounded-full" src="/twitch.png" alt="">
                    </a>
                </li>
            </ul>
        </div>
    </div>
</template>

<style>
    .contact {
        display: grid;
        place-items: center;
        grid-template-columns: 1fr 1fr;
        grid-template-rows: auto 1fr;
    }
    .social-media {
        width: 100%;
        grid-column: span 2;
    }
    .social-media-links {
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 13px;
    }
    .social-media-links > li {
        margin-right: 13px;
    }
</style>