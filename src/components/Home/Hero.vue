<template>
    <div class="container">
        <section class="hero">
            <div class="left">
                <h1>More than 100 Wordpress Themes & Templates</h1>
                <div class="search">
                    <input type="text" placeholder="e.g Responsive slider" />
                    <button class="search-btn">SEARCH</button>
                </div>
                <p>
                    From multipurpose themes to niche templates,
                    you’ll always find something that catches your eye.
                </p>
            </div>
            <div class="hero-image">
                <img src="../../assets/img/hero_image.png" alt />
            </div>
        </section>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.hero {
    display: flex;
    align-items: center;
    justify-content: center;
    .left {
        width: 750px;
        height: 317px;
        h1 {
            font-size: 45px;
            font-weight: 700;
            line-height: 54px;
            margin-bottom: 44px;
        }

        .search {
            input {
                width: 336px;
                height: 60px;
                margin: 0 24px;
                border-radius: 10px;
                background-color: inherit;
                font-size: 16px;
                margin-bottom: 45px;
            }

            button {
                height: 60px;
                width: 190px;
                border-radius: 10px;
                background-color: #0fafe9;
                color: white;
                font-weight: 500;
                font-size: 15px;
                white-space: normal;
                cursor: pointer;
            }
        }
        p {
            font-size: 20px;
            font-weight: 400;
        }
    }

    .hero-image {
        img {
            max-width: 100%;
        }
    }
}
</style>