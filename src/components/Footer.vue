<template>
    <footer>
        <div class="footer__wrapper flex__footer">
            <div class="footer__wrapper--img">
                <img :src="Logo1" alt="">
            </div>
            <div class="footer__wrapper--text">
                <h3 class="footer__title">Protoapp</h3>
                <h3>Camp One Inc, LLC</h3>
                <p>Que ad Lorem ipsum dolor sit amet, consectetur adipiscing elit. Qui reprehenderit rerum ullam necessitatibus, at ab quae expedita illo, nobis ipsum maxime assumenda dolorum quo ut deleniti possimus. Eveniet, voluptatem, provident. </p>
            </div>
        </div>
        <div class="footer__wrapper--copyright">
            <p>&copy 2019 Protoapp. All rights reserved.</p>
        </div>
       
    </footer>
</template>
<script setup>
import Logo1 from '../assets/logo1.svg'
</script>
