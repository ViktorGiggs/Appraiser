<template>
    <div class="container">
        <div class="wrok-text text-center mt-5">
		    <h1 class="mt-5 logos">Used:</h1>
                <div class="mt-5 mb-5">
                    <Html5/>
                    <Css3/>
                    <Bootstrap/>
                    <VueLogo/>
                    <NuxtLogo/>
                </div>
                <div class="mt-5 mb-5">
                    <a href="https://t.me/AveryTex"><h2 class="mt-5 wrok-text">Please give me a job</h2></a>
                </div>
            <NuxtLink class="nav-link big-text-link" :to="'/'">Return Home</NuxtLink>
	    </div>
	    <div class="video-bg">
		    <video muted width="100%" height="auto" preload="auto" autoplay="autoplay" loop="loop" poster="bg-img.jpg">
			    <source src="@/assets/video/video_carpet.mp4" type="video/mp4">
		    </video>
	    </div>
    </div>
</template>

<script>
export default {
    head: {
    title: 'About'
    }
}
</script>