<template>
    <div class="container">
        <div class="contact">
            <div class="left">
                <h2>We build apps and websites</h2>
                <p>From multipurpose themes to niche templates,you’ll always find something that catches your eye.</p>
                <button>contact us</button>
                <span>or see our portfolio</span>
            </div>
            <div class="right">
                <div class="phones">
                    <img src="../../assets/img/phone1.png" alt />
                    <img src="../../assets/img/phone2.png" alt />
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.contact {
    height: 425px;
    width: 100%;
    border-radius: 10px;
    background-color: #e0f0f6;
    overflow: hidden;
    display: flex;
    padding: 100px;

    .left {
        flex: 1;
        h2 {
            font-size: 35px;
            font-weight: 700;
            color: #0fafe9;
            margin-bottom: 30px;
        }

        p {
            font-size: 20px;
            margin-bottom: 30px;
        }

        button {
            height: 60px;
            width: 190px;
            text-align: center;
            background-color: #0fafe9;
            border-radius: 10px;
            color: #fff;
            text-transform: uppercase;
            margin-right: 25px;
        }

        span {
            font-size: 18px;
        }
    }

    .right {
        display: flex;
        flex: 1;

        .phones {
            transform: translate(100px,-100px);

            img {
                margin-right: 53px;
                width: 255px;
                height: 583px;
                transform: rotate(-25deg);
                object-fit: contain;
            }
        }
    }
}
</style>