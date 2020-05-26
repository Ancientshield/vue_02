<template>
  <div>
    <label>Please ask a yes or no question. For example: Is the sky blue?</label>
    <input v-model="question" />
    <button>Search</button>
    <p>{{ answer }}</p>
  </div>
</template>