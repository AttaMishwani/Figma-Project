https://attamishwani.github.io/Figma-Project/

 <ul class="menu">
                <li class="menuItem"><a href="">Home</a></li>
                <li class="menuItem"><a href="">About</a></li>
                <li class="menuItem"><a href="">Testimonials</a></li>
                <li class="menuItem"><a href="">Contact</a></li>
            </ul>

                 <i class="fa-solid fa-bars"></i>

media (max-width:1200px) {
.navbar .content {

        width: 95%;

        transform: translateX(-75px);
        padding: 0 68px;

    }

    .homeHeading {
        font-size: 76px;

        width: 47%;
        line-height: 80px;
    }

    .home-text {
        font-size: 18px;

        width: 52%;

    }

    .homeHero {

        width: 883px;
        bottom: -51%;
    }

    .homeDownloads {

        bottom: -91%;
        width: 489px;
    }

}

@media (max-width:1100px) {

    .about-item {

        margin-bottom: -7rem;
    }

    .testimonials-container {
        width: 97%;
        margin-top: 50px;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
    }

    .six-content-container {
        width: 100%;
        margin: 0 auto;
    }

    .six-content-container .about-item .item-right {
        transform: translateX(169px);
        width: 40%;
    }

    .six-content-container .about-item .item-left {
        width: 71%;
        transform: translateX(74px);
    }


    .section-six {

        margin-bottom: 4rem;
    }

    .six-content-container .about-item {
        width: 50%;
    }

    .about-item-heading {
        font-size: 31px;

    }

    .about-item-text {
        font-size: 14px;


    }

    .about-btn {
        font-size: 14px;
        background-color: var(--darkest-blue);
        padding: 10px 23px;

    }

    .whiteSpace {
        width: 100%;
        height: 56vh;
    }

    .about-item:nth-child(odd) .item-right {

        transform: translateX(-68px);
    }

    .about-item:nth-child(even) .item-right {

        transform: translateX(68px);
    }

    .accordion-container {
        width: 62%;

    }

    .banner {
        width: 86%;


    }

}

@media (max-width:950px) {

    .clients-container {
        width: 90%;
        margin: 20px auto;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
    }

    .testimonial-card {
        width: 41%;
        background-color: var("--light-grey");

    }

    .testimonials-container {
        width: 100%;

    }

    .testimonials {

        margin-bottom: 6rem;

    }

}

@media(max-width:768px) {

    .homeHeading {
        font-size: 37px;
        width: 58%;
    }

    .homeHero {
        width: 65%;
    }

    .whiteSpace {
        width: 100%;
        height: 33vh;
    }

    .about-item {
        margin-bottom: -3rem;
    }

    .about-item-heading {
        font-size: 23px;
    }

    .about-item-text {
        font-size: 14px;

        line-height: 20px;

    }

    .about-item:nth-child(odd) .item-right {
        transform: translateX(-56px);
    }

    .about {
        margin-bottom: 10rem;
    }

    .banner-text p {
        width: 95%;
    }

    .banner {
        width: 95%;
        padding: 21px;

    }

    .input-button {
        display: flex;
        flex-direction: row;
        gap: 10px;
    }

    .input-button button {
        width: 100%;
        max-width: 133px;

    }

    .input-button input {
        width: 100%;
        max-width: 142px;

    }

    .sectionHeading {
        font-size: 46px;
    }

}
