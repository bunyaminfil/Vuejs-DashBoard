<template>
  <div class="row">
    <div class="col-md-12">
      <div class="card">
        <card>
          <h5 slot="header" class="title">Create New Category</h5>
          <div class="row">
            <div class="col-md-3 px-md-1">
              <base-input
                label="Category Name"
                placeholder="Name"
                v-model="model.username"
              >
              </base-input>
            </div>
            <div class="col-md-4 pl-md-1">
              <base-input
                label="Image"
                placeholder="Image-Url"
                v-model="model.password"
              >
              </base-input>
            </div>
          </div>

          <base-button slot="footer" type="primary" fill>Add</base-button>
        </card>
      </div>
    </div>
  </div>
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
