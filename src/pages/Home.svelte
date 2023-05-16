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

    <div class="center">
        <h1 on:mousedown={() => window.open('https://store.3core.dev/')}>3Core<span>.dev</span></h1>
    </div>

    <div class="footer">
        <span>© 3Core Development 2023</span>
    </div>

</div>