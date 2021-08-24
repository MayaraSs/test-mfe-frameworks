<script>
    import { Dropdown } from "bootstrap";
    import "./css/custom.css";
</script>

<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
        >
            <span class="navbar-toggler-icon" />
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                    <a
                        class="nav-link active"
                        aria-current="page"
                        href="/"
                    >Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="react">React</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="angular">Angular</a>
                </li>
                <li class="nav-item"><a class="nav-link" href="vue">Vue</a></li>
            </ul>
        </div>
    </div>
</nav>
