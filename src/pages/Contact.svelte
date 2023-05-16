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
    
    <div class="contactus">
        <h1>Contact us</h1>
        <div class="socials">
            <img alt="" src="img/discord.png" on:mousedown={() => window.open('https://discord.gg/sPeetDwfN2')}>
            <img alt="" src="img/youtube.png" on:mousedown={() => window.open('https://www.youtube.com/@3Core814')}>
            <!-- <img alt="" src="img/github.png"> -->
        </div>
    </div>
    
    <div class="footer">
        <span>© 3Core Development 2023</span>
    </div>

</div>