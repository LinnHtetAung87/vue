<template>
  <div>
    <AdminTemplate>
      <IntroTest />
      <h1>Login View</h1>
      <p>This is Login Page</p>
    </AdminTemplate>
  </div>
</template>
<script>
import IntroTest from "@/components/IntroTest.vue";
import AdminTemplate from "@/components/AdminTemplate.vue";
export default {
  component: {
    AdminTemplate,
    IntroTest,
  },
};
</script>
