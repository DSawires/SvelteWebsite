import { dev } from '$app/environment';
import { inject } from '@vercel/analytics';
 
inject({ mode: dev ? 'development' : 'production' });

<h1>Welcome to my website</h1>
<p>Visit my <a href="https://github.com/dsawires">GitHub</a> to check out some of my projects.</p>
