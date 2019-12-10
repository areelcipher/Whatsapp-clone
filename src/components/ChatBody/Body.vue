<template>
    <section>
        <div id="dp">
            <div>
                <img src="./1.png" alt="dp" srcset="">
            </div>
        </div>
        <div id="chat-contents">
            <div id="name-and-time">
                <p id="name"> {{name}} </p>
                <p id="time"> {{time}} </p>

            </div>
            <div id="mesg-and-notification">
                <p id="msg"> <a href="#/convo"> {{mesg}} </a> </p>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    data() {
        return {
            name: 'Mickie',
            mesg: 'Thanks for coming around, I really appreciate it.',
            time: 'Yesterday',
            notification: 2
        }
    }
}
</script>

<style scoped>
    section {
        margin: 10px 3px 2px 0px;
        display: flex;
        align-items: center;
    }
    #dp {
        width: 20%;
        height: 70px;
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 0 10px 0 0;
    }
    #dp div {
        width: 55px;
        height: 55px;
        border-radius: 50%;
    }
    img {
        width: 55px;
    }
    #chat-contents {
        width: 85%;
        display: flex;
        height: 50%;
        flex-direction: column;
        border-bottom: 1px solid grey
    }
    #name-and-time {
        display: flex;
        justify-content: space-between;
        height: 50%;
        align-items: center;
        margin: -15px 0px -25px 0;
    }
    #mesg-and-notification {
        display: flex;
        align-items: center;
    }
    #name {
        font-weight: 800;
    }
    #time {
        font-size: 13px;
        color: grey;
    }#msg {
        width: 78%;
        font-size: 14px;
        color: grey;
    }
    a {
        text-decoration: none;
        color: grey;
    }

</style>