<script>
    import { dev } from '$app/environment';
    import { inject } from '@vercel/analytics';
 
    inject({ mode: dev ? 'development' : 'production' });
</script>

<h1>Welcome to my website! It's still under development so check back later. :)</h1>
<p>Visit my <a href="https://github.com/dsawires">GitHub</a> to check out some of my projects.</p>
