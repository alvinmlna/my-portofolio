---

layout: ../../templates/BasePostLayout.astro
title: Hello, World

---

<div class="w-75 mx-auto">
    <div id="carouselExampleControls" class="carousel carousel-dark slide" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
            <img src="/assets/mathadventure.png" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
            <img src="/assets/mathadventure.png" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
            <img src="/assets/mathadventure.png" class="d-block w-100" alt="...">
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
</div>