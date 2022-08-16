<template>
    <main>
        <center>
            <div class="searchend-container">
                <div class="searchend-phase1">
                    <div class="phase1-text1">
                        This is where your
                        search ends
                    </div>
                    <div class="pictalk">
                        <img src="/pictalk.png" alt="" class="pic" />
                    </div>
                </div>
                <!--2-->
                <div class="searchend-phase2">
                    <div class="rment">
                        <div class="connect">
                            <img src="/connect.svg" alt="" />
                            <span class="r">Recruitment</span>
                        </div>
                        <div><i class="las la-angle-down"></i></div>
                    </div>
                    <!---->
                    <div class="rment2">
                        <div class="connect">
                            <img src="/ostaffing.svg" alt="" />
                            <span class="r">Outstaffing</span>
                        </div>
                        <div><i class="las la-angle-down"></i></div>
                    </div>
                    <!---->
                    <div class="rment2">
                        <div class="connect">
                            <img src="/advisory.svg" alt="" />
                            <span class="r">Advisory</span>
                        </div>
                        <div><i class="las la-angle-down"></i></div>
                    </div>
                </div>
            </div>
        </center>
    </main>
</template>

<style scoped>
.searchend-container {
    width: 80%;
    background: #f0f9ff;
    margin-top: 100px;
    display: flex;
    padding: 70px;
    justify-content: space-between;
}
.searchend-phase1 {
    width: 50%;
    text-align: left;
}
.phase1-text1 {
    width: 60%;
    font-family: 'Poppins', sans-serif;
    font-size: 30px;
    font-weight: 400;
}
.pictalk {
    margin-top: 20px;
}

.searchend-phase2 {
    width: 50%;
    text-align: left;
}
.rment {
    width: 80%;
    padding: 40px;
    background: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-radius: 10px;
}
.connect {
    align-items: center;
    display: flex;
    font-size: 25px;
    font-family: 'Poppins', sans-serif;
    font-weight: bold;
}
.r {
    margin-left: 20px;
}

.rment2 {
    width: 80%;
    padding: 40px;
    background: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-radius: 10px;
    margin-top: 20px;
}

@media only screen and (max-width:1024px) {
.searchend-container {
    width: 80%;
    background: #f0f9ff;
    margin-top: 100px;
    display: block;
    padding: 30px;
}
.searchend-phase1 {
    width: 100%;
    text-align: left;
}
.phase1-text1 {
    width: 80%;
    font-family: 'Poppins', sans-serif;
    font-size: 30px;
    font-weight: 400;
}

.searchend-phase2 {
    width: 100%;
    text-align: left;
}
.rment {
    width: 90%;
    padding: 30px;
    background: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-radius: 10px;
    margin-top: 10px;
    text-align: left;
}
.connect {
    align-items: center;
    display: flex;
    font-size: 18px;
    font-family: 'Poppins', sans-serif;
    font-weight: bold;
}
.r {
    margin-left: 20px;
}

.rment2 {
    width: 90%;
    padding: 30px;
    background: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-radius: 10px;
    margin-top: 10px;
    text-align: left;
    margin-top: 20px;
}
}


@media only screen and (max-width:767px) {
.searchend-container {
    width: 80%;
    background: #f0f9ff;
    margin-top: 100px;
    display: block;
    padding: 30px;
    text-align: left;
}
.searchend-phase1 {
    width: 100%;
    text-align: left;
}
.phase1-text1 {
    width: 80%;
    font-family: 'Poppins', sans-serif;
    font-size: 18px;
    font-weight: 600;
}
.pictalk {
    margin-top: 20px;
    width: 100%;
}
.pic {
    width: 100%;
}


.searchend-phase2 {
    width: 100%;
    text-align: left;
}
.rment {
    width: 80%;
    padding: 30px;
    background: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-radius: 10px;
    margin-top: 10px;
    text-align:left;
}
.connect {
    align-items: center;
    display: flex;
    font-size: 18px;
    font-family: 'Poppins', sans-serif;
    font-weight: bold;
}
.r {
    margin-left: 20px;
}

.rment2 {
    width: 80%;
    padding: 30px;
    background: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-radius: 10px;
    margin-top: 10px;
    text-align:left;
}
}
</style>