<script>
    import { Link } from "svelte-routing";
</script>

<div class="wrapper">

    <div class="header">
        <div class="nav">
            <Link to="/">
                <img class="navimg" alt="" src="img/home.png">
            </Link>
            <Link to="/projects">
                <img class="navimg" alt="" src="img/settings.png">
            </Link>
            <Link to="/contact">
                <img class="navimg" alt="" src="img/mail.png">
            </Link>
        </div>
        <img alt="" src="img/arrowdown.png">
    </div>

    <div class="gallery">
        <h1>Projects Gallery</h1>
        <section class="container">
            <div class="slider-wrapper">
                <div class="slider">
                    <img id="beachmarket" src="img/projects/beachmarket/1.png" alt=""/>
                    <img id="trains" src="img/projects/trains/1.png" alt=""/>
                    <img id="insurance" src="img/projects/insurance/1.png" alt=""/>
                    <img id="atm" src="img/projects/atm/1.png" alt=""/>
                    <img id="gasstations1" src="img/projects/gasstations/1.png" alt=""/>
                    <img id="gasstations2" src="img/projects/gasstations/2.png" alt=""/>
                    <img id="dragrace" src="img/projects/dragrace/1.png" alt=""/>
                    <img id="identity1" src="img/projects/identity/1.png" alt=""/>
                    <img id="identity2" src="img/projects/identity/2.png" alt=""/>
                </div>
                <div class="slider-nav">
                    <!-- svelte-ignore a11y-missing-content -->
                    <a href="#beachmarket"></a>
                    <!-- svelte-ignore a11y-missing-content -->
                    <a href="#trains"></a>
                    <!-- svelte-ignore a11y-missing-content -->
                    <a href="#insurance"></a>
                    <!-- svelte-ignore a11y-missing-content -->
                    <a href="#atm"></a>
                    <!-- svelte-ignore a11y-missing-content -->
                    <a href="#gasstations1"></a>
                    <!-- svelte-ignore a11y-missing-content -->
                    <a href="#gasstations2"></a>
                    <!-- svelte-ignore a11y-missing-content -->
                    <a href="#dragrace"></a>
                    <!-- svelte-ignore a11y-missing-content -->
                    <a href="#identity1"></a>
                    <!-- svelte-ignore a11y-missing-content -->
                    <a href="#identity2"></a>
                    <!-- svelte-ignore a11y-missing-content -->
                </div>
            </div>
        </section>
    </div>

    <div class="footer">
        <span>© 3Core Development 2023</span>
    </div>
    
</div>