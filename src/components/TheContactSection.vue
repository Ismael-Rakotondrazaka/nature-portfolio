<template>
  <div class="bg-secondary text-black px-3 py-4">
    <h1>Contact Me</h1>
    <ul
      class="
        list-group
        d-flex
        list-group-horizontal list-group-flush
        text-center
      "
    >
      <li class="list-group-item col-4" style="border-radius: 0">
        email@email
      </li>
      <li class="list-group-item col-4 bg-success" style="border-radius: 0">
        Chicago, US
      </li>
      <li class="list-group-item col-4" style="border-radius: 0">512312311</li>
    </ul>
    <hr class="bg-white" />
    <form action="">
      <div class="form-group">
        <label for="name">Name</label>
        <input
          type="text"
          name="name"
          class="form-control mb-3"
          style="border-radius: 0"
          id="name"
        />
      </div>
      <div class="form-group">
        <label for="email">Email</label>
        <input
          type="email"
          name="email"
          class="form-control mb-3"
          style="border-radius: 0"
          id="email"
        />
      </div>
      <div class="form-group">
        <label for="message">Message</label>
        <input
          type="text"
          name="message"
          class="form-control mb-3"
          style="border-radius: 0"
          id="message"
        />
      </div>
      <button type="submit" class="btn bg-dark text-white">Send Message</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "TheContactSection"
};
</script>

<style></style>
