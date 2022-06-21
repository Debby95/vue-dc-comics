<template>
    <footer>
        <div class="container">
            <div class="row">
                <div class="col">
                    <h5>DC COMICS</h5>
                    <ul>
                        <li v-for="link in dcComicsLinks" :key="link">
                            {{link}}
                        </li>
                    </ul>
                </div>
                <div class="col">
                    <h5>DC</h5>
                    <ul>
                        <li v-for="link in dcLinks" :key="link">
                            {{link}}
                        </li>
                    </ul>
                    
                </div>
                <div class="col">
                    <h5>SITES</h5>
                    <ul>
                        <li v-for="link in sitesLinks" :key="link">
                            {{link}}
                        </li>
                    </ul>
                </div>
                <div class="col">
                    <h5>SHOP</h5>
                    <ul>
                        <li v-for="link in shopLinks" :key="link">
                            {{link}}
                        </li>
                    </ul>
                </div>
                <div class="col-lg-6">
                    <img class="img-footer" src="/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "TheFooter",
    data() {
        return {
            dcComicsLinks: [
                "Characters",
                "Comics",
                "Movies",
                "TV",
                "Games",
                "Videos",
                "News",
            ],
            dcLinks: [
                "Terms Of Us",
                "Privacy policy (New)",
                "Ad Choise",
                "Advertising",
                "Jobs",
                "Subsciptions",
                "Talent Workshops",
                "CPSC Certificates",
                "Ratings",
                "Shop Help",
                "Contact Us",
            ],
            sitesLinks: [
                "DC",
                "MAD Magazine",
                "DC Kids",
                "DC Universe",
                "DC Power Visa",
            ],
            shopLinks: [
                "Shop DC",
                "Shop DC Collectibles",
            ]
        }
    }
}
</script>

<style>
    footer {
        background-image: url("/public/img/footer-bg.jpg");
        color: white;
        padding: 30px;
    }

    ul {
        list-style-type: none;
    }

    li {
        color: grey;
        text-align: start;
    }

    .img-footer {
        width: 400px;
    }
</style>