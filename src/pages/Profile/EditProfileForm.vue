<template>
  <card>
    <h5 slot="header" class="title">Create New Profile</h5>
    <div class="row">
      <div class="col-md-3 px-md-1">
        <base-input
          label="Username"
          placeholder="Username"
          v-model="model.username"
        >
        </base-input>
      </div>
      <div class="col-md-4 pl-md-1">
        <base-input
          label="Password"
          type="Password"
          placeholder="Password"
          v-model="model.password"
        >
        </base-input>
      </div>
    </div>

    <base-button slot="footer" type="primary" fill>Save</base-button>
  </card>
</template>
<script>
export default {
  props: {
    model: {
      type: Object,
      default: () => {
        return {};
      }
    }
  }
};
</script>
<style></style>
