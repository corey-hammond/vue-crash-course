# Vue Crash Course

## Component Structure

- Output: <template> contains markup
- Functionality: <script> contains imports, data, logic
- Style: <style> contains component styles

## Directives

- v-bind:propertyType="propertyName"
  - v-bind:key, v-bind:class, v-bind:todos
- v-for="todo in todos"
  - needs a unique key: v-bind:key="todo.id"
- v-on:change="methodName"
  - v-on:click, v-on:submit

## Event Emitting

- @click="$emit('del-todo', todo.id)"
