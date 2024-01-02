<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  </head>
  <body>
    <header>
      <nav class="navbar navbar-expand-lg">
        <div class="container">
          <h1 class="navbar-brand text-white">Assignments</h1>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <h2
                  class="nav-link active text-white"
                  aria-current="page"
                  >Chapter 39 - 42</h2>
              </li>
            </ul>
            <form class="d-flex" role="search">
              <input
                class="form-control me-2"
                type="search"
                placeholder="Search"
                aria-label="Search"
              />
              <button class="btn btn-outline-success" type="submit">
                Search
              </button>
            </form>
          </div>
        </div>
      </nav>
    </header>

  <main>
      <div class="container">
        <div class="row">
          <div class="offset-1 col-10 offset-1 text-center my-5">
            <h4>Chapter # 39 - 42 | Switch Statement &amp; While and Do While Loops</h4>
            <div class="border-bottom mt-4 border-secondary"></div>
          </div>
        </div>
        <div class="row mb-5">
          <div class="col-12 col-md-6 mb-3 mb-md-0">
            <div class="h-100">
              <h4 class="text-center mt-4">Buttons</h4>
              <div class="box1 px-2 py-4 text-center">
                <div class="btn btn-danger m-1" id="if" onclick="ifelse()">
                if else
                </div>
                <div class="btn btn-danger m-1" id="swtch" onclick="swtch()">
                switch
                </div>
                <div class="btn btn-danger m-1" id="askname" onclick="askthename()">
                Keep Asking the Name
                </div>
            </div>
            </div>
          </div>
          <div class="col-12 col-md-6 mb-3 mb-md-0">
              <h4 class="text-center mt-4">Output / Result</h4>
              <div class="box2 px-2 py-4">
              <div class="text-center" id="output"></div>
              </div>
              <div class="text-center">
              <div class="btn btn-outline-dark my-4" id="clearOutput">
              Clear Output
            </div>
          </div>
          </div>
      </div>
    </main>
    <footer id="footer" class="py-2">
      <p class="text-center text-white">
        &copy; <span id="f-year"></span>. Assignment By
        <a
          href="https://www.facebook.com/profile.php?id=100061029926998"
          target="_blank"
          class="text-decoration-none fw-bold text-white"
          >ᖺᗩᖇᓮᔕ ᙢᕰᘐᖺᗩᒪ.</a
        >
      </p>
    </footer>
</body>
</html>
