<template>
  <div>
    <div class="form-group">
      <small id="emailHelp" class="form-text text-light">No compartiremos tus datos con nadie más.</small>

      <label for="exampleInputEmail1">Email</label>
      <input
        type="email"
        class="form-control"
        id="exampleInputEmail1"
        aria-describedby="emailHelp"
        placeholder="Enter email"
        v-model="email"
      />
    </div>
    <div class="form-group">
      <label for="exampleInputPassword1">Contraseña</label>
      <input
        type="password"
        class="form-control"
        id="exampleInputPassword1"
        placeholder="Password"
        v-model="password"
      />
    </div>
    <button type="submit" class="btn btn-primary">Entrar</button>
    <!-- 

    <div class="row container">
      <form class="col s12">
        <div class="row">
          <div class="input-field col s12">
            <input id="email" type="email" name="email" class="validate" v-model="email" />
            <label for="email">Email</label>
          </div>
        </div>
        <div class="row">
          <div class="input-field col s12">
            <input
              id="password"
              type="password"
              name="password"
              class="validate"
              v-model="password"
            />
            <label for="password">Password</label>
          </div>
        </div>
      </form>
      <div>
        <button
          class="btn waves-effect waves-light indigo darken-4"
          type="submit"
          name="action"
          @click="knownUser({email, password})"
        >
          Submit
          <i class="material-icons right">send</i>
        </button>
      </div>
    </div>
    <p>{{ error }}</p>-->
  </div>
</template>

<script>
export default {
  name: "Login",
  data() {
    return {
      email: null,
      password: null
    };
  }
};
</script>

