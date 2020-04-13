<template>
    <b-container class="bv-example-row mt-3" fluid>
        <b-row>
            <b-col cols="8">
                <div class="embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/4OjiOn5s8s8"
                            allowfullscreen></iframe>
                    <!--                    <video autoplay="true" id="videoElement"></video>-->
                </div>
                <div class="embed-responsive embed-responsive-16by9 mt-3">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Q0oIoR9mLwc"
                            allowfullscreen></iframe>
                </div>
            </b-col>
            <b-col cols="4">
                <div class="cards fill">
                    <div class="container padd">
                        <div class="idcard">
                            <div class="container" fluid>
                                <b-row>
                                    <b-col cols="5">
                                        <div class="photo">asdasdas</div>
                                    </b-col>

                                    <b-col cols="7">
                                        <div class="info">asdasd</div>
                                    </b-col>
                                </b-row>
                            </div>
                        </div>
                    </div>
                </div>
            </b-col>
        </b-row>
    </b-container>
</template>

<script>
    export default {
        name: "Recognition"
    };

    // var video = document.querySelector("#videoElement");
    //
    // if (navigator.mediaDevices.getUserMedia) {
    //     navigator.mediaDevices.getUserMedia({ video: true })
    //         .then(function (stream) {
    //             video.srcObject = stream;
    //         })
    // }

</script>

<style scoped>
    .cards {
        background: darkgray;
        height: 100%;
    }

    .idcard {
        background: #2c3e50;
        height: 200px;
    }

    .padd {
        padding: 30px;
    }
</style>