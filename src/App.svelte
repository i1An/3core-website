<script>
    // @ts-nocheck
    import { Router, Route } from 'svelte-routing';
    import jquery from 'jquery';
    import Home from './pages/Home.svelte';
    import Projects from './pages/Projects.svelte';
    import Contact from './pages/Contact.svelte';
    export let url = '/';

    jquery(document).ready(function() {
        document.addEventListener('touchmove', function (event) {
            if (event.scale !== 1) { event.preventDefault(); }
        }, { passive: false });
        window.addEventListener('scroll', preventMotion, false);
        window.addEventListener('touchmove', preventMotion, false);
        function preventMotion(event) {
            window.scrollTo(0, 0);
            event.preventDefault();
            event.stopPropagation();
        }
    });
</script>

<Router {url}>
    <Route path="/" component={Home} />
    <Route path="/projects" component={Projects} />
    <Route path="/contact" component={Contact} />
</Router>