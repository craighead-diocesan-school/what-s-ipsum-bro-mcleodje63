<slot />

<style>
  /* Add your own fonts and global styles here. */


  /* The code below resets the browser's default styles. It's a good idea to include this in your layout component. */
  :global(body) {
    margin: 0;
    padding: 0;
    font-family: sans-serif;
  }

  :global(a) {
    color: #1eaedb;
    text-decoration: none;
  }

  :global(a:hover) {
    color: #0fa0ce;
  }

  :global(h1) {
    font-size: 2rem;
    font-weight: 300;
    margin: 0 0 1rem 0;
  }

  :global(h2) {
    font-size: 1.5rem;
    font-weight: 300;
    margin: 0 0 1rem 0;
  }
</style>