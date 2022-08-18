<template>
  <h1>My Portfolio</h1>
  <span>Filter :</span>
  <div class="button-group ms-3">
    <button
      class="btn bg-white mx-1text-uppercase active"
      style="border-radius: 0"
    >
      All
    </button>
    <button class="btn bg-white mx-1" style="border-radius: 0">Design</button>
    <button class="btn bg-white mx-1" style="border-radius: 0">Photos</button>
    <button class="btn bg-white mx-1" style="border-radius: 0">Articles</button>
  </div>
  <hr style="height: 5px" />
  <div>
    <ul class="row mx-0 px-0">
      <li class="list-unstyled col-md-4 mt-4">
        <div class="card h-100">
          <img
            src="@/assets/images/mountains.jpg"
            alt=""
            class="card-img-top"
          />
          <div class="card-body">
            <h2 class="card-title">Lorem, ipsum.</h2>
            <p class="card-text" style="text-align: justify">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis
              deleniti distinctio harum iure cum ullam explicabo temporibus
              facilis consequatur?
            </p>
          </div>
        </div>
      </li>
      <li class="list-unstyled col-md-4 mt-4">
        <div class="card h-100">
          <img src="@/assets/images/lights.jpg" alt="" class="card-img-top" />
          <div class="card-body">
            <h2 class="card-title">Esse, libero.</h2>
            <p class="card-text" style="text-align: justify">
              Eveniet, illo, iste sequi debitis quibusdam laudantium rerum quam
              odit nemo maiores dignissimos hic, eum quidem! Nesciunt, debitis
              id.
            </p>
          </div>
        </div>
      </li>
      <li class="list-unstyled col-md-4 mt-4">
        <div class="card h-100">
          <img src="@/assets/images/nature.jpg" alt="" class="card-img-top" />
          <div class="card-body">
            <h2 class="card-title">Non, explicabo!</h2>
            <p class="card-text" style="text-align: justify">Voluptate.</p>
          </div>
        </div>
      </li>
      <li class="list-unstyled col-md-4 mt-4">
        <div class="card h-100">
          <img src="@/assets/images/p1.jpg" alt="" class="card-img-top" />
          <div class="card-body">
            <h2 class="card-title">Corporis, architecto?</h2>
            <p class="card-text" style="text-align: justify">
              Ducimus saepe, reprehenderit minima dignissimos non voluptate at
              id soluta cum sit voluptas molestiae similique quae ratione nisi
              facilis?
            </p>
          </div>
        </div>
      </li>
      <li class="list-unstyled col-md-4 mt-4">
        <div class="card h-100">
          <img src="@/assets/images/p2.jpg" alt="" class="card-img-top" />
          <div class="card-body">
            <h2 class="card-title">Eveniet, veritatis?</h2>
            <p class="card-text" style="text-align: justify">
              Dicta deserunt magnam aut assumenda dolore. Corrupti sapiente
              error, dolores sit voluptas saepe blanditiis ea aliquid voluptates
              illo suscipit.
            </p>
          </div>
        </div>
      </li>
      <li class="list-unstyled col-md-4 mt-4">
        <div class="card h-100">
          <img src="@/assets/images/p3.jpg" alt="" class="card-img-top" />
          <div class="card-body">
            <h2 class="card-title">Voluptatibus, aut!</h2>
            <p class="card-text" style="text-align: justify">
              Temporibus magni modi quod rerum quam esse excepturi officiis rem
              possimus unde, necessitatibus tempore nesciunt inventore
              dignissimos quibusdam incidunt?
            </p>
          </div>
        </div>
      </li>
    </ul>
  </div>
  <div class="my-5">
    <ul class="pagination pagination-lg justify-content-center">
      <li class="page-item"><a class="page-link" href="#">Before</a></li>
      <li class="page-item"><a class="page-link" href="#">1</a></li>
      <li class="page-item"><a class="page-link" href="#">2</a></li>
      <li class="page-item"><a class="page-link" href="#">3</a></li>
      <li class="page-item"><a class="page-link" href="#">Next</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "ThePortfolioSection",
};
</script>

<style></style>
