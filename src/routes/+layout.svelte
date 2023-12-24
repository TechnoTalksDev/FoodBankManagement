<header>
  <nav>
    <a href="/">Home</a>
    <a href="/about">About</a>
    <a href="/settings">Settings</a>
  </nav>
</header>

<slot></slot>

<footer class="w-full text-gray-700 bg-white body-font fixed bottom-0">
  <div class="container flex flex-col items-start p-6 mx-auto md:flex-row">
      <div class="flex items-center mb-4 font-light text-gray-900 title-font md:mb-0">
          <h1>© Copyright 2023</h1>
      </div>
      <div class="flex items-center justify-center text-base md:ml-auto">
          <a href="/legal#terms" class="mr-5 font-light hover:text-gray-900">
            Terms
          </a>
          <a href="/legal#privacy" class="mr-5 font-light hover:text-gray-900">
            Privacy
          </a>
      </div>
  </div>
</footer>

<script>
  import "../app.css";
</script>