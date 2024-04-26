<script setup lang="ts"></script>

<template>
  
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <img src="/logos/logo.svg" width="32px" height="32px" alt="image du logo">
            <a class="navbar-brand" href="#">Accueil</a>
            <div class="collapse navbar-collapse justify-content-between" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Admin</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Déroulant</a>
                    </li>
                </ul>
                <ul class="navbar-nav">
                  <a class="nav-link" href="#">
                            <span class="bi bi-cart-fill"></span>
                        </a>
                    <li class="nav-item dropdown">
                        <a
                            class="nav-link dropdown-toggle"
                            href="#"
                            id="navbarDropdownTheme"
                            role="button"
                            data-bs-toggle="dropdown"
                            aria-expanded="false"
                        >
                        <span class="bi bi-sun-fill"></span>
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdownTheme">
                            <li><a class="dropdown-item" href="#"><span class="bi bi-sun"></span>Mode Clair</a></li>
                            <li><a class="dropdown-item" href="#"><span class="bi bi-moon"></span>Mode Sombre</a></li>
                            <li><a class="dropdown-item" href="#"><span class="bi bi-brilliance"></span>Mode Auto</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a
                            class="nav-link dropdown-toggle"
                            href="#"
                            id="navbarDropdownConnexion"
                            role="button"
                            data-bs-toggle="dropdown"
                            aria-expanded="false"
                        >
                            Connexion
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdownConnexion">
                            <!-- Insérez ici les éléments du menu de connexion -->
                        </ul>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>
