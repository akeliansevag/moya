<template>
    <div class="flex flex-col justify-center items-center relative min-h-screen w-full overflow-hidden text-white py-10">
        <img src="~/assets/img/shape.webp" alt="Background Shape" class="h-full left-1/2 -translate-x-1/2 absolute -z-10" />
        <div class="container">
            <section class="flex max-lg:flex-col items-center max-lg:gap-10 lg:gap-24">
                <div class="xl:w-1/3 w-full">
                    <div class="mb-[5.5rem]">
                        <svg width="193" height="56" viewBox="0 0 193 56" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M18.2227 38.3192V39.7533H0.927386V38.3192C4.13021 37.3918 4.21626 33.9309 4.21626 29.6286V11.1478C4.21626 8.19351 3.46097 6.67336 0 4.81858V3.38448L14.7617 0V29.619C14.7617 34.2559 15.2684 37.4683 18.2227 38.3097V38.3192ZM41.5985 38.3192V39.7533H24.2172V38.3192C27.42 37.3918 27.5921 33.7588 27.5921 29.4565V13.0886C27.5921 8.3656 25.3167 6.0806 21.5211 6.0806C20.2591 6.0806 18.9015 6.7594 17.8115 7.68679L16.7981 6.33873C19.4082 2.87777 23.2898 0 27.5061 0C37.3823 0 38.1376 7.42865 38.1376 13.2511V29.4565C38.1376 34.0934 38.5582 37.5544 41.5985 38.3192ZM64.9744 38.3192V39.7533H47.5931V38.3192C50.7959 37.3918 50.968 33.7588 50.968 29.4565V13.0886C50.968 8.3656 48.6065 6.0806 44.8109 6.0806C43.5489 6.0806 42.1913 6.7594 41.1014 7.68679L39.9158 6.33873C42.4399 2.87777 46.6657 0 50.8819 0C57.4597 0 61.5134 2.61963 61.5134 12.8304V29.4565C61.5134 34.0934 61.9341 37.5544 64.9744 38.3192Z" fill="white"/>
                            <path d="M86.8292 38.9116V40.4317C75.0983 39.6764 68.5205 30.8137 68.5205 20.2683C68.5205 9.72282 75.1078 0.850509 86.8292 0.0952148V1.61536C82.1923 2.29417 80.9207 6.59648 80.9207 20.2587C80.9207 33.9209 82.1827 38.2328 86.8292 38.9116ZM90.2902 40.4317V38.9116C94.9271 38.2328 96.1987 33.9305 96.1987 20.2587C96.1987 6.58692 94.9367 2.28461 90.2902 1.61536V0.0952148C102.107 0.850509 108.685 9.62722 108.685 20.2587C108.685 30.8902 102.107 39.6669 90.2902 40.4222V40.4317Z" fill="white"/>
                            <path d="M131.688 40.5091H130.082L114.135 5.49792C112.787 2.20904 110.081 2.20904 108.819 2.20904V0.765381H128.734V2.19948C124.346 2.19948 126.545 7.34313 126.545 7.34313L136.335 28.2715L131.698 40.5091H131.688ZM129.193 44.5533C127.845 48.1003 125.904 48.521 125.57 47.5076C125.149 46.0735 124.221 44.7254 122.701 44.0466C119.747 42.6985 116.286 44.0466 114.938 47.0008C113.676 49.9551 114.938 53.4161 117.892 54.7641C119.919 55.6915 122.873 55.1848 124.394 53.9228C126 52.6608 128.524 50.2993 130.723 44.5533H129.203H129.193ZM152.282 0.765381V2.19948C150.513 2.19948 144.911 7.10411 139.519 20.0971L138.505 18.9116C139.605 16.1294 144.012 2.11344 135.752 2.19948V0.765381H152.292H152.282Z" fill="white"/>
                            <path d="M191.147 33.9312L192.581 34.5239C191.902 37.22 188.021 40.5185 182.705 40.5185C182.705 40.5185 174.187 40.5185 174.187 32.9273V19.6762C165.917 21.531 163.134 25.4986 163.134 29.8009C163.134 29.8009 163.134 35.3748 168.622 35.3748C169.55 35.3748 170.391 35.2888 171.07 34.9542L172.083 36.3883C169.808 38.5012 166.175 40.5185 162.044 40.5185C162.044 40.5185 152.34 40.5185 152.34 31.9139C152.34 22.7165 159.425 21.8751 174.196 18.156V12.9263C174.196 4.99098 170.142 0.688673 165.085 2.20882L164.492 0.946811C167.695 -0.152667 170.735 0.0194252 170.735 0.0194252C181.787 0.0194252 184.828 6.94136 184.828 16.894V29.4663C184.828 29.4663 184.741 35.3748 188.881 35.3748C188.881 35.3748 190.65 35.3748 191.157 33.9407L191.147 33.9312ZM156.212 12.9168C155.199 11.3106 155.113 9.29329 155.954 7.84962C156.71 6.58761 157.723 4.6468 161.356 2.44784L161.949 3.79589C160.687 4.80933 160.601 5.65067 161.021 5.65067C162.283 5.82276 163.383 6.40596 164.148 7.50544C165.668 9.69484 165.075 12.6491 162.886 14.1692C160.696 15.6033 157.742 15.0966 156.222 12.9072L156.212 12.9168Z" fill="white"/>
                        </svg>
                    </div>
                    <h1 class="max-lg:text-3xl lg:text-4xl mb-3 font-[700]">We’re Coming Soon</h1>
                    <p>We are using this time to give our website a revamp! Please leave us your email and we will let you know when we are back up.</p>
                    <a href="mailto:hassan.raya@montymobile.com" class="mt-8 m-button">Contact us</a>
                </div>
                <div class="xl:w-2/3 w-full">
                    <div class="md:aspect-[16/9] max-md:aspect-[3/4] rounded-2xl overflow-hidden">
                        <video
                            class="w-full max-md:h-full max-md:object-cover"
                            src="~/assets/video.webm"
                            poster="~/assets/img/video-poster.webp"
                            autoplay
                            muted
                            playsinline
                            loop
                        ></video>
                    </div>
                </div>
            </section>
        </div>
        <footer class="text-center max-lg:mt-10 lg:absolute bottom-14 text-[#828282] text-[14px]">
            <p>© Copyrights Moya | All Rights Reserved</p>
        </footer>
    </div>
</template>

<script setup>
    useSeoMeta({
        title: 'Moya - We’re Coming Soon',
        ogTitle: 'Moya - We’re Coming Soon',
        description: 'We are using this time to give our website a revamp! Please leave us your email and we will let you know when we are back up.',
        ogDescription: 'We are using this time to give our website a revamp! Please leave us your email and we will let you know when we are back up.',
        ogImage: 'https://moya.com/moyalogo.png',
        twitterCard: 'summary_large_image',
    })
</script>