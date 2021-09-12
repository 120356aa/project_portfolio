<script>
    let logo = `assets/logo_large.png`;
    let realestate = 'assets/home.svg';
    let github_btn = 'assets/github_btn_dark.svg';
</script>

<main>
    <div class="content">
        <div class="card">
            <div class="logo_container avnw_app">
                <img src={logo} class="avnw_logo" alt="alpha visuals app logo" />
            </div>
            <div class="header">
                <h3>Alpha Visuals App</h3>
                <p>Alpha Visuals is a cross platform mobile app created for a photography startup using React Native along with Expo. Available on the Android and IOS stores</p>
            </div>
            <div class="technologies">
                <h3>Key Technologies</h3>
                <div class="tags_box">
                    <div class="tag">
                        <p>React Native</p>
                    </div>
                    <div class="tag">
                        <p>Expo</p>
                    </div>
                    <div class="tag">
                        <p>NodeJS</p>
                    </div>
                    <div class="tag">
                        <p>Express</p>
                    </div>
                    <div class="tag">
                        <p>PostGresql</p>
                    </div>
                    <div class="tag">
                        <p>Stripe</p>
                    </div>
                    <div class="tag">
                        <p>Sequelize</p>
                    </div>
                    <div class="tag">
                        <p>Heroku</p>
                    </div>
                </div>
            </div>
            <div class="buttons">
                <a href="https://github.com/120356aa/avnw_app">
                    <img src={github_btn} alt="github button logo" />
                    <p>Github</p>
                </a>
            </div>
        </div>
        <div class="card">
            <div class="logo_container dc">
                <h2>D&C</h2>
            </div>
            <div class="header">
                <h3>D&C Test Drive</h3>
                <p>A public facing marketing tool created to drive business and automate the test drive process. Built to be an injectable form for facebook ads and vehicle marketplace platforms</p>
            </div>
            <div class="technologies">
                <h3>Key Technologies</h3>
                <div class="tags_box">
                    <div class="tag">
                        <p>React</p>
                    </div>
                    <div class="tag">
                        <p>Express</p>
                    </div>
                    <div class="tag">
                        <p>NodeJS</p>
                    </div>
                    <div class="tag">
                        <p>Nodemailer</p>
                    </div>
                    <div class="tag">
                        <p>Styled Components</p>
                    </div>
                    <div class="tag">
                        <p>Heroku</p>
                    </div>
                    <div class="tag">
                        <p>Netlify</p>
                    </div>
                </div>
            </div>
            <div class="buttons">
                <a href="https://github.com/120356aa/dcmc-form-2">
                    <img src={github_btn} alt="github button image" />
                    <p>Github</p>
                </a>
                <a href="https://dcmotorcompany.netlify.app/" class="demo">
                    <p>Demo</p>
                </a>
            </div>
        </div>
        <div class="card">
            <div class="logo_container avnw_site">
                <img src={realestate} class="avnw_logo" alt="alpha visuals website logo" />
            </div>
            <div class="header">
                <h3>Real Estate Ad Form</h3>
                <p>A marketing tool intended to be used on mobile devices via mobile Facebook and Instagram ads. Features complex validation and error handling</p>
            </div>
            <div class="technologies">
                <h3>Key Technologies</h3>
                <div class="tags_box">
                    <div class="tag">
                        <p>React</p>
                    </div>
                    <div class="tag">
                        <p>Express</p>
                    </div>
                    <div class="tag">
                        <p>NodeJS</p>
                    </div>
                    <div class="tag">
                        <p>Nodemailer</p>
                    </div>
                    <div class="tag">
                        <p>Styled Components</p>
                    </div>
                    <div class="tag">
                        <p>Heroku</p>
                    </div>
                    <div class="tag">
                        <p>Netlify</p>
                    </div>
                </div>
            </div>
            <div class="buttons">
                <a href="https://github.com/120356aa/realestate-form">
                    <img src={github_btn} alt="github button image" />
                    <p>Github</p>
                </a>
                <a href="https://realestateform.netlify.app/" class="demo">
                    <p>Demo</p>
                </a>
            </div>
        </div>
    </div>
    <div class="back_btn">
    </div>
</main>

<style type="text/scss">
    @import url('https://fonts.googleapis.com/css2?family=Kaisei+HarunoUmi&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Lato:wght@100;300;400;700&display=swap');

	main {
        .content {
            max-width: 1000px;
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
    
            @media screen and(max-width: 1400px) { max-width: 800px; }
            @media screen and (max-width: 1000px) {
                max-width: 100%;
            }
            @media screen and (max-width: 700px) {
                flex-direction: column;
                justify-content: flex-start;
                padding: 40px 0;
            }
    
            .card {
                width: 240px;
                padding: 25px;
                border-radius: 8px;
                background-color: #15161B;
                box-shadow: 0px 0px 15px 0px rgba(0,0,0,0.15);
    
                &:nth-child(2) {
                    margin: 0 20px;
                    @media screen and (max-width: 700px) { margin: 20px 0; }
                }
    
                @media screen and (max-width: 1400px) {
                    width: 220px;
                    padding: 15px;
                }
    
                @media screen and (max-width: 1000px) {
                    width: 200px;
                    padding: 12px;
                }
    
                @media screen and (max-width: 700px) {}
    
                .avnw_app { background-color: #2669B8; }
                .dc { background-color: #CDCDCD; }
                .avnw_site { background-color: #E05B50; }
    
                .logo_container {
                    width: 240px;
                    height: 240px;
                    border-radius: 8px;
                    display: flex;
                    justify-content: center;
                    align-items: center;
    
                    @media screen and (max-width: 1400px) {
                        width: 220px;
                        height: 220px;
                    }
    
                    @media screen and (max-width: 1000px) {
                        width: 200px;
                        height: 200px;
                    }
    
                    img {
                        width: 160px;
                        height: 160px;
    
                        @media screen and (max-width: 1000px) {
                            width: 120px;
                            height: 120px;
                        }
                    }
    
                    h2 {
                        font-family: 'Kaisei HarunoUmi', serif;
                        font-size: 60px;
                        color: #181818;
                        @media screen and (max-width: 1400px) { font-size: 50px; }
                    }
                }
    
                .header {
                    margin-top: 40px;
                    @media screen and (max-width: 1400px) { margin-top: 30px; }
                    @media screen and (max-width: 1000px) { margin-top: 24px; }
    
                    h3 {
                        font-family: 'Loto', sans-serif;
                        font-size: 20px;
                        color: #E5E5E5;
                        font-weight: 700;
                        @media screen and (max-width: 1400px) { font-size: 18px; }
                        @media screen and (max-width: 1000px) { font-size: 16px; }
                    }
    
                    p {
                        font-family: 'Loto', sans-serif;
                        font-size: 14px;
                        line-height: 19px;
                        margin-top: 15px;
                        color: #B2B2B2;
                        font-weight: 100;
                        @media screen and (max-width: 1400px) { font-size: 12px; }
                        @media screen and (max-width: 1000px) { margin-top: 10px; }
                    }
                }
    
                .technologies {
                    margin-top: 30px;
                    @media screen and (max-width: 1400px) { margin-top: 20px; }
                    @media screen and (max-width: 1000px) { margin-top: 16px; }
    
                    h3 {
                        font-family: 'Lato', sans-serif;
                        font-size: 16px;
                        color: #E5E5E5;
                        font-weight: 700;
                        @media screen and (max-width: 1400px) { font-size: 14px; }
                    }
    
                    .tags_box {
                        display: flex;
                        justify-content: flex-start;
                        margin-top: 10px;
                        flex-wrap: wrap;
                        @media screen and (max-width: 1000px) { margin-top: 6px; }
    
                        .tag {
                            border-radius: 4px;
                            padding: 8px 14px;
                            background-color: #24252D;
                            margin: 3px 6px 3px 0;
                            @media screen and (max-width: 1000px) { padding: 6px 10px; }
    
                            p {
                                font-family: 'Lato', sans-serif;
                                font-size: 12px;
                                font-weight: 700;
                                color: #CBCBCB;
                                @media screen and (max-width: 1400px) { font-size: 10px; }
                            }
                        }
                    }
                }
    
                .buttons {
                    display: flex;
                    margin-top: 30px;
                    justify-content: space-between;
                    @media screen and (max-width: 1400px) { margin-top: 20px; }
                    @media screen and (max-width: 1000px) { margin-top: 16px; }
    
                    a {
                        text-decoration: none;
                        display: flex;
                        justify-content: flex-start;
                        align-items: center;
                        background-color: #CBCBCB;
                        padding: 6px 14px;
                        border-radius: 4px;
                        width: 36%;
                        @media screen and (max-width: 1000px) { padding: 6px 10px; }
    
                        img {
                            width: 20px;
                            height: 20px;
                            margin-right: 5px;
                            @media screen and (max-width: 1400px) {
                                width: 18px;
                                height: 18px;
                            }
    
                            @media screen and (max-width: 1000px) {
                                width: 16px;
                                height: 16px;
                            }
                        }
    
                        p {
                            font-family: 'Lato', sans-serif;
                            font-weight: 900;
                            font-size: 14px;
                            color: #202020;
                            margin-left: 5px;
                            @media screen and (max-width: 1400px) { font-size: 12px; }
                        }
                    }
    
                    .demo {
                        justify-content: center;
                        p {
                            margin: 0;
                        }
                    }
                }
            }
        }
    }
</style>