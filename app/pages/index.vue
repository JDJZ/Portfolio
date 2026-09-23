<template>
    <div class="content">
        <h1 class="title">Hi, my name is <i>Zachary Richter</i>. I'm a freelanceR based in CALIFORNIA.</h1>

        <div class="img-desc">
            <img class="big-img" src="@/assets/ClayCup-1.jpg">

            <div class="description">
                From stadium broadcast, to keynotes on corporate stages, I live for the adrenaline and precision of live
                production. My background bridges sports broadcasting and corporate AV, with experience across many
                different roles.
                <br><br>
                Working on broadcasts like Thursday Night Football (Prime Video), the PGA Tour (ESPN+), and the FIFA
                World Cup with HBS, I thrive in high-pressure control room environments where precision is everything.
                <br><br>
                As a TD, V1 for corporate live events and an FAA Part 107 licensed remote pilot, I bring a versatile
                skillset. I am continuously expanding my seat time behind production switchers.
            </div>
            <div class="row2">

                <img class="bigger-img" src="@/assets/ClayCup-2.jpg">
                <p>ClayCup Live Stream</p>
                <img class="bigger-img" src="@/assets/ClayCup-3.jpg">
            </div>
        </div>


    </div>
</template>

<style scoped>
.content {
    margin-left: 2rem;
    margin-right: 2rem;
    display: grid;
    text-transform: uppercase;
}

.description {
    text-transform: none;
    flex-shrink: 1;
    flex-grow: 1;
    flex-basis: 50%;
}

.title {
    font-size: 4rem;
    margin-top: 0rem;
}

@media screen and (max-width: 720px) {
    .title {
        font-size: 2rem;
    }
}

@media screen and (max-width: 520px) {
    .content {
        margin: 0.5rem;
    }
}

.big-img {
    object-fit: cover;
    width: 300px;
    height: 300px;
}

.bigger-img {
    object-fit: cover;
    max-width: 500px;
}


.img-desc {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    flex-direction: row;
    gap: 1rem;
}

.row2 {
    width: stretch;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;

}
</style>
