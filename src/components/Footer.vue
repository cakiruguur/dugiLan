<template>
    <footer>
        <div class="container">
            <div class="footer-links">
                <ul class="footer-list">
                    <li class="footer-list-item" v-for="i in 4" :key="i">
                        <h5>Envato Market</h5>

                        <ul>
                            <li>
                                <a href="#">Terms</a>
                            </li>
                            <li>
                                <a href="#">Licenses</a>
                            </li>
                            <li>
                                <a href="#">Market API</a>
                            </li>
                            <li>
                                <a href="#">Become an affiliate</a>
                            </li>
                        </ul>
                    </li>
                </ul>
            </div>
            <div class="footer-bottom">
                <span>© 2020 DugiLanding All right reserved.</span>
                <ul>
                    <li>
                        <a href="#">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <i class="fab fa-twitter"></i>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <i class="fab fa-linkedin-in"></i>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <i class="fab fa-instagram"></i>
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.footer-links {
    padding: 70px 0;
    .footer-list {
        display: flex;
        justify-content: space-between;
        align-items: flex-start;

        &-item {
            h5 {
                font-size: 20px;
                font-weight: 600;
                margin-bottom: 25px;
            }

            ul {
                li {
                    margin-bottom: 10px;

                    a {
                        font-size: 15px;
                        color: #33334f;
                    }
                }
            }
        }
    }
}

.footer-bottom {
    height: 84px;
    line-height: 84px;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    border-top: 1px solid #a7a7a7;
    span {
        font-size: 15px;
        color: #b9b9b9;
    }

    ul {
        display: flex;
        align-items: center;
        gap: 8px;

        li {
            a {
                color: black;
            }
        }
    }
}
</style>