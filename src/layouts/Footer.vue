<template>
    <div id="mainFooter">
        <div class="container">
            <div id="mainFooter-tBox">
                <div id="mainFooter-sBox">
                    <a href="#">
                        <button>SCHOOLSMASTER</button>
                    </a>
                    <ul>
                        <li>
                            <a href="#">
                                Top World Universities <br />
                                Top North America Universities <br />
                                Top Latin America Universities <br />
                                Top Europe Universities <br />
                                Top Asia Universities <br />
                                Top Africa Universities <br />
                                Top Arab Region Universities <br />
                                Top Oceania Universities
                            </a>
                        </li>
                        <a href="#"><img src="../assets/images/sch-master.png" alt="SchoolSMaster" /></a>
                    </ul>
                </div>
                <div id="mainFooter-sBox">
                    <a href="#">
                        <button>UNIRANKS</button>
                    </a>
                    <ul>
                        <li>
                            <a href="#">
                                Top World Universities <br />
                                Top North America Universities <br />
                                Top Latin America Universities <br />
                                Top Europe Universities <br />
                                Top Asia Universities <br />
                                Top Africa Universities <br />
                                Top Arab Region Universities <br />
                                Top Oceania Universities
                            </a>
                        </li>
                        <a href="#"><img src="../../src/assets/images/Unira.png" alt="UNIRANKS" /></a>
                    </ul>
                </div>
                <div id="mainFooter-sBox">
                    <a href="#">
                        <button>WHERS</button>
                    </a>
                    <ul>
                        <li>
                            <a href="#">
                                Top World Universities <br />
                                Top North America Universities <br />
                                Top Latin America Universities <br />
                                Top Europe Universities <br />
                                Top Asia Universities <br />
                                Top Africa Universities <br />
                                Top Arab Region Universities <br />
                                Top Oceania Universities
                            </a>
                        </li>
                        <a href="#"><img src="../../src/assets/images/whers.png" alt="SchoolSMaster" /></a>
                    </ul>
                </div>
                <div id="mainFooter-sBox">
                    <a href="#">
                        <button>FOLLOW US</button>
                    </a>
                    <div id="messengers">
                        <ul>
                            <li>
                                <a href="#"><i class="fa-brands fa-square-facebook"></i></a>
                            </li>
                            <li><a href="#"><i class="fa-brands fa-square-twitter"></i></a></li>
                            <li>
                                <a href="#"><i class="fa-brands fa-square-instagram"></i></a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            <div id="mainFooter-bBox">
                <h3>UNITED ARAB EMIRATES</h3>
                <p>
                    Terms and Conditions | Accessibility | Privacy | Legal | Contact Us
                </p>
                <div id="langueage">
                    <p>English | العربية</p>
                </div>
            </div>
            <p>Copyright © 2022 SchoolsMaster. All rights reserved.</p>
        </div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style scoped>
    #mainFooter {
        margin-top: 80px;
        background: #1C345A;
       
    }

    #mainFooter .container {
        padding: 40px 0px;
        margin: 0 auto;
        width: 1242px;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }

    #mainFooter .container #mainFooter-tBox {
        width: 100%;
        display: flex;
        justify-content: space-between;
    }

    #mainFooter .container #mainFooter-tBox #mainFooter-sBox {
        width: 400px;
        display: flex;
        flex-wrap: wrap;
    }

    #mainFooter .container #mainFooter-tBox #mainFooter-sBox a>button {
        padding: 7px 0px;
        font-size: 20px;
        background: transparent;
        color: #ffffff;
        width: 197px;
        text-align: start;
        border-top: none;
        border-left: none;
        border-right: none;
        border-bottom: 2px solid #039BE5;
    }

    #mainFooter .container #mainFooter-tBox #mainFooter-sBox ul {
        margin-top: 20px;
        list-style: none;
        text-decoration: none;
    }

    #mainFooter .container #mainFooter-tBox #mainFooter-sBox ul li a {
        color: white;
        letter-spacing: 0.7px;
        text-decoration: none;
    }

    #mainFooter .container #mainFooter-tBox #mainFooter-sBox #messengers>ul {
        width: 150px;
        margin-top: -125px;
        justify-content: space-between;
        display: flex;
    }

    #mainFooter .container #mainFooter-tBox #mainFooter-sBox #messengers>ul li {
        font-size: 42px;
    }

    #mainFooter .container #mainFooter-tBox #mainFooter-sBox a img {
        margin: 40px 0px 40px 0px;
        width: 100px;
    }

    #mainFooter .container #mainFooter-bBox {
        width: 100%;
        color: white;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }

    #mainFooter .container>p {
        color: white;
        margin: 20px auto 0px auto;
    }
</style>