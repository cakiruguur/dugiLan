<template>
    <div class="container">
        <header class="header">
            <div class="left">
                <a href class="logo">
                    <img src="../assets/img/Logo.svg" alt />
                </a>
                <nav class="menu">
                    <ul>
                        <li>
                            <a href="#">
                                Browse
                                <img src="../assets/icons/chevron-down.svg" alt />
                            </a>
                        </li>
                        <li>
                            <a href="#">All-Exclusive</a>
                        </li>
                        <li>
                            <a href="#">Docs</a>
                        </li>
                    </ul>
                </nav>
            </div>
            <div class="right">
                <a href="#">
                    <svg
                        width="20"
                        height="20"
                        viewBox="0 0 18 16"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <path
                            d="M15.6296 2.4574C15.2465 2.07416 14.7917 1.77014 14.2911 1.56272C13.7905 1.3553 13.254 1.24854 12.7121 1.24854C12.1702 1.24854 11.6337 1.3553 11.1331 1.56272C10.6325 1.77014 10.1777 2.07416 9.7946 2.4574L8.9996 3.2524L8.2046 2.4574C7.43083 1.68364 6.38138 1.24894 5.2871 1.24894C4.19283 1.24894 3.14337 1.68364 2.3696 2.4574C1.59583 3.23117 1.16113 4.28063 1.16113 5.3749C1.16113 6.46918 1.59583 7.51864 2.3696 8.2924L3.1646 9.0874L8.9996 14.9224L14.8346 9.0874L15.6296 8.2924C16.0128 7.90934 16.3169 7.45451 16.5243 6.95392C16.7317 6.45333 16.8385 5.91677 16.8385 5.3749C16.8385 4.83304 16.7317 4.29648 16.5243 3.79589C16.3169 3.29529 16.0128 2.84047 15.6296 2.4574V2.4574Z"
                            stroke="black"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        />
                    </svg>
                </a>
                <a href="#">
                    <img src="../assets/icons/bag.svg" alt />
                </a>

                <a href="#" class="account-btn">ACCOUNT</a>
            </div>
        </header>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.header {
    display: flex;
    justify-content: space-between;
    margin-top: 40px;
    height: 60px;
    margin-bottom: 100px;

    .left {
        display: flex;
        align-items: center;

        .logo {
            width: 135px;
            height: 48px;
        }
        .menu {
            ul {
                display: flex;
                margin-left: 50px;
                gap: 30px;
                li {
                    a {
                        font-size: 15px;
                        font-weight: 400;
                        color: black;
                    }
                }
            }
        }
    }

    .right {
        display: flex;
        align-items: center;

        a {
            display: inline-block;
            margin-right: 30px;
            img {
                width: 20px;
                height: 20px;
            }
        }

        .account-btn {
            margin-left: 15px;
            margin-right: 0px;
            width: 190px;
            height: 60px;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: #0fafe9;
            color: white;
            font-weight: 500;
            font-size: 15px;
            border-radius: 10px;
        }
    }
}
</style>