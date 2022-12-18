<template>
  <div style=" display: flex;
  align-items: center;
  height: 130px;
  border: 4px solid #669966;
  margin-top: 12px;
  padding: 20px;">
    <img width="40" src="https://vuejs.org/images/logo.png" />
    <h1 style="font-size: 1.5em">{{ message }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return { message: "Strategfy MFE 3 . Vue Application Module" };
  },
};
</script>