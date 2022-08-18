<template>
  <div class="row mx-0">
    <figure class="col-md-6">
      <img class="w-100" src="@/assets/images/avatar_g.jpg" alt="" />
    </figure>
    <figure class="col-md-6">
      <img class="w-100" src="@/assets/images/me2.jpg" alt="" />
    </figure>
  </div>
  <div>
    <h1>About me</h1>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aliquid animi
      soluta in optio libero nemo consequuntur saepe, laboriosam quo atque
      debitis possimus. Vitae ipsa dolorum quis sunt. Blanditiis eligendi
      tempore consequatur tenetur sint quod! Repellendus facilis pariatur iste
      mollitia tempora possimus temporibus amet quod inventore. Deleniti placeat
      necessitatibus iure totam maiores reiciendis corporis recusandae earum
      officia deserunt, aut hic rerum quos molestias praesentium, impedit
      voluptatem dolor libero! Architecto, a quia excepturi reprehenderit illo
      recusandae. Quod accusantium iste, voluptates laborum provident aliquam
      magnam hic officia dignissimos odit. Et cumque fuga odio saepe sed, porro
      at ex eum dolorem temporibus maiores itaque?
    </p>
    <div class="mb-5">
      <h2>Technical Skills</h2>
      <p>Photography</p>
      <div class="progress mb-4" style="height: 40px; border-radius: 0">
        <div class="progress-bar bg-secondary" style="width: 95%; height: 40px">
          95%
        </div>
      </div>
      <p>Web Design</p>
      <div class="progress mb-4" style="height: 40px; border-radius: 0">
        <div class="progress-bar bg-secondary" style="width: 85%; height: 40px">
          85%
        </div>
      </div>
      <p>Photoshop</p>
      <div class="progress mb-4" style="height: 40px; border-radius: 0">
        <div class="progress-bar bg-secondary" style="width: 80%; height: 40px">
          80%
        </div>
      </div>
      <button class="btn btn-lg btn-secondary">Download Resume</button>
    </div>
    <div>
      <h2>How much I charge</h2>
      <ul class="row mx-0 px-0">
        <li class="list-unstyled col-md-4 my-2 text-center">
          <div class="card h-100">
            <div class="card-header text-white bg-dark py-4">
              <h1 class="card-title">Basic</h1>
            </div>
            <div>
              <ul class="ps-0 pt-3">
                <li class="list-unstyled">Web Design</li>
                <hr />
                <li class="list-unstyled">Photography</li>
                <hr />
                <li class="list-unstyled">50GB Storages</li>
                <hr />
                <li class="list-unstyled">Endless Support</li>
                <hr />
              </ul>
              <p><strong class="display-5">$ 50</strong><br />per month</p>
            </div>
            <div class="card-footer py-4">
              <button class="btn btn-lg btn-success">Sign up</button>
            </div>
          </div>
        </li>
        <li class="list-unstyled col-md-4 my-2 text-center">
          <div class="card h-100">
            <div class="card-header text-white bg-success py-4">
              <h1 class="card-title">Pro</h1>
            </div>
            <div>
              <ul class="ps-0 pt-3">
                <li class="list-unstyled">Web Design</li>
                <hr />
                <li class="list-unstyled">Photography</li>
                <hr />
                <li class="list-unstyled">50GB Storages</li>
                <hr />
                <li class="list-unstyled">Endless Support</li>
                <hr />
              </ul>
              <p><strong class="display-5">$ 25</strong><br />per month</p>
            </div>
            <div class="card-footer py-4">
              <button class="btn btn-lg btn-success">Sign up</button>
            </div>
          </div>
        </li>
        <li class="list-unstyled col-md-4 my-2 text-center">
          <div class="card h-100">
            <div class="card-header text-white bg-dark py-4">
              <h1 class="card-title">Premium</h1>
            </div>
            <div>
              <ul class="ps-0 pt-3">
                <li class="list-unstyled">Web Design</li>
                <hr />
                <li class="list-unstyled">Photography</li>
                <hr />
                <li class="list-unstyled">Unlimited Storage</li>
                <hr />
                <li class="list-unstyled">Endless Support</li>
                <hr />
              </ul>
              <p><strong class="display-5">$ 50</strong><br />per month</p>
            </div>
            <div class="card-footer py-4">
              <button class="btn btn-lg btn-success">Sign up</button>
            </div>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "TheAboutSection"
}
</script>

<style></style>
