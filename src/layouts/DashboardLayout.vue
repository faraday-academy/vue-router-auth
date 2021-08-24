<template>
  <div>
    <div id="nav">
      <router-link to="/dashboard">Dashboard</router-link> |
      <router-link to="/reports">Reports</router-link> |
      <router-link to="/settings">Settings</router-link> |
      <router-link to="/">Logout</router-link>
    </div>

    <router-view />
  </div>
</template>
