<template>
  <div class="row my-5">
    <div class="col-md-6 offset-md-3">
      <div class="card">
        <div class="card-body">
          <h3 class="text-center my-4">Signup</h3>
          <div class="form-group">
            <input
              v-model="name"
              type="text"
              class="form-control"
              placeholder="Name"
            />
          </div>
          <div class="form-group">
            <input
              v-model="email"
              type="text"
              class="form-control"
              placeholder="email"
            />
          </div>
          <div class="form-group">
            <input
              v-model="password"
              type="password"
              class="form-control"
              placeholder="password"
            />
          </div>
          <div class="form-group text-center">
            <button
              @click="registerUser()"
              class="btn btn-success form-control"
            >
              Signup
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Axios from 'axios'
export default {
  data() {
    return {
      name: '',
      email: '',
      password: '',
    }
  },
  methods: {
    registerUser() {
      console.log(this.name, this.email, this.password)
      Axios.post('https://react-blog-api.bahdcasts.com')
    },
  },
}
</script>
