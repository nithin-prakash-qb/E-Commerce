<script setup></script>

<template>
  <ul id="outer_li">
    <li>lorem ipsum</li>
    <li>
      <ul>
        <li>Department</li>
        <li>one</li>
        <li>two</li>
        <li>three</li>
        <li>four</li>
        <li>five</li>
      </ul>
    </li>
    <li>
      <ul>
        <li>About Us</li>
        <li>one</li>
        <li>two</li>
        <li>three</li>
        <li>four</li>
        <li>five</li>
      </ul>
    </li>
    <li>
      <ul>
        <li>Services</li>
        <li>one</li>
        <li>two</li>
        <li>three</li>
        <li>four</li>
        <li>five</li>
      </ul>
    </li>
    <li>
      <ul>
        <li>Help</li>
        <li>one</li>
        <li>two</li>
        <li>three</li>
        <li>four</li>
        <li>five</li>
      </ul>
    </li>
  </ul>
</template>

<style scoped>
ul {
  list-style: none;
  padding: 10px 20px;
}
#outer_li {
  display: flex;
  justify-content: space-between;
}
</style>
