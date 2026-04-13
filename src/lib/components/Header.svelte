<header>
  <div class="outer">
    <div class="inner">
      <a class="logo" href="/">Logo</a>
      <nav>
        <ul>
          <li><a href="/">Home</a></li>
          <li><a href="/about">About</a></li>
          <li><a href="/blog">Blog</a></li>
          <li><a href="/contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </div>
</header>

<style>
  .outer {
    background: dodgerblue;
    color: white;
  }

  .inner {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    gap: 1.5rem;
    padding-block: 1.5rem;
  }

  ul {
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem;
    padding: 0;
    list-style: none;
  }

  a {
    color: white;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  .logo {
    font-size: 2rem;
    font-weight: bold;
  }

  .logo:hover {
    text-decoration: none;
  }
</style>