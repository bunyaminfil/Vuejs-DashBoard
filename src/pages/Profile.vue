<template>
  <div class="row">
    <div class="col-md-8">
      <edit-profile-form :model="model"> </edit-profile-form>
    </div>
    <div class="col-md-4">
      <user-card :user="user"></user-card>
    </div>
  </div>
</template>
<script>
import EditProfileForm from "./Profile/EditProfileForm";
import UserCard from "./Profile/UserCard";
export default {
  components: {
    EditProfileForm,
    UserCard
  },
  data() {
    return {
      model: {
        username: "",
        password: ""
      },
      user: {
        fullName: "Bünyamin FİL",
        title: "Admin",
        description: "Selam burası açıklama kısmıdır...",
      }
    };
  }
};
</script>
<style></style>
