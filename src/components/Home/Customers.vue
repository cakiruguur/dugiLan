<template>
    <div class="container">
        <div class="customers">
            <h6>Some of our 500 clients already using Dugilan</h6>
            <ul>
                <li>
                    <img src="../../assets/img/acer.svg" alt />
                </li>
                <li>
                    <img src="../../assets/img/facebook.svg" alt />
                </li>
                <li>
                    <img src="../../assets/img/linkedin.svg" alt />
                </li>
                <li>
                    <img src="../../assets/img/forbes.svg" alt />
                </li>
                <li>
                    <img src="../../assets/img/dell.svg" alt />
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.customers {
    width: 100%;
    height: 127px;
    margin-top: 100px;
    margin-bottom: 97px;
    display: flex;
    justify-content: center;
    flex-direction: column;

    h6 {
        text-align: center;
        font-size: 18px;
        font-weight: 600;
        line-height: 27px;
        text-transform: uppercase;
        color: #0fafe9;
    }
    ul {
        display: flex;
        align-items: center;
        justify-content: space-around;
        margin-top: 30px;
        li {
            img {
                filter: grayscale(1);
                transition: filter 0.2s ease;
                &:hover {
                    filter: grayscale(0);
                }
            }
        }
    }
}
</style>