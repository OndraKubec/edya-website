<template>
    <div id="landing" class="w-screen min-h-screen pb-8 relative">
        <div class="container">
            <div class="grid grid-cols-2">
                <div class="w-24 box-border py-8 lg:w-32 lg:py-0">
                    <svg id="a3f116a1-f5f8-4354-ba7b-710dc320000e" data-name="Vrstva 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 154 78.1"><path d="M85.9,66.6H55.2V11.3H67.6L85.9,45.7Z" transform="translate(0 0)" style="fill:#f6ab20"/><path d="M74.5,0h2.8l23,45.7V78.1H97.8V45.7" transform="translate(0 0)" style="fill:#f6ab20"/><path d="M89.9,0h32.3L106,34.6" transform="translate(0 0)" style="fill:#f6ab20"/><path d="M134.5,0h2.9L114.2,45.7V78.1h-2.5V45.7" transform="translate(0 0)" style="fill:#f6ab20"/><path d="M125.6,49.9V45.7l17.1-34.4H154V49.9Z" transform="translate(0 0)" style="fill:#f6ab20"/><path d="M154,60.7H125.6V78H154Z" transform="translate(0 0)" style="fill:#f6ab20"/><path d="M0,2V76.1H8.1V2" transform="translate(0 0)" style="fill:#cfd8d7"/><path d="M46.8,2V9.1h-33V2Z" transform="translate(0 0)" style="fill:#cfd8d7"/><path d="M33.8,36.1h-20v5.6H33.9V36.1Z" transform="translate(0 0)" style="fill:#cfd8d7"/><path d="M13.8,69v7.1H46.9V69Z" transform="translate(0 0)" style="fill:#cfd8d7"/></svg>
                </div>

            </div>
            <div style="margin-top: 13vh">
                <h1>WE ARE<br>EDYA</h1>
                <div class="subtitle">young, dynamically <br class="lg:hidden">growing <br class="hidden lg:block">company creating <br class="lg:hidden">visual<br class="hidden lg:block"> ideas, either digital<br class=""> or physical</div>
            </div>
        </div>
        <div class="hidden lg:block absolute bottom-0 side-finger" style="transform: translateY(5vh);">
            <svg height="auto" viewBox="0 0 472 353" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M-109.845 142.673L471.155 352.673L471.155 262.173L-109.845 54.989L-109.845 142.673Z" fill="url(#paint0_linear_210_11)"/>
                <path d="M-151.401 104.249L377.155 292.809L377.155 194.294L-151.401 0.132221L-151.401 104.249Z" fill="url(#paint1_linear_210_11)"/>
                <defs>
                <linearGradient id="paint0_linear_210_11" x1="-113.543" y1="248.273" x2="429.95" y2="105.412" gradientUnits="userSpaceOnUse">
                <stop offset="0.5" stop-color="#EEB13A"/>
                <stop offset="1" stop-color="#EEBB3A" stop-opacity="0"/>
                </linearGradient>
                <linearGradient id="paint1_linear_210_11" x1="-113.543" y1="248.273" x2="429.95" y2="105.412" gradientUnits="userSpaceOnUse">
                <stop stop-color="#FFB800"/>
                <stop offset="0.541667" stop-color="#FFB800"/>
                <stop offset="1" stop-color="#DBA10B" stop-opacity="0.22"/>
                </linearGradient>
                </defs>
            </svg>
        </div>

        <div class="absolute left-0 bottom-0 h-1/3 w-screen" style="background: linear-gradient(0deg, rgba(0,0,0,0), #202020); transform: translateY(30vh); z-index: -5;"></div>
    </div>
</template>

<script>
export default {
    name: 'landingSection'
}
</script>

<style>
    #landing{
        background-image: linear-gradient(0deg, #202020, #202020 3%,rgba(0,0,0,0) 30%, rgba(0,0,0,0)) ,url('@/assets/landing.png');
        /* background-attachment: fixed; */
        background-repeat: no-repeat;
        background-size: cover;
        background-position: 35% 50%;
    }
</style>