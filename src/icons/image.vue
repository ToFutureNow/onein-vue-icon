
  <template>
    <svg
      xmlns="http://www.w3.org/2000/svg" :width="size" :height="size" viewBox="0 0 24 24" aria-hidden="true" :stroke="color" fill="none" stroke-width="1" stroke-linecap="round" stroke-linejoin="round"
    >
      <path fill-rule="evenodd" clip-rule="evenodd" d="M8.5 8C8.22386 8 8 8.22386 8 8.5C8 8.77614 8.22386 9 8.5 9C8.77614 9 9 8.77614 9 8.5C9 8.22386 8.77614 8 8.5 8ZM6 8.5C6 7.11929 7.11929 6 8.5 6C9.88071 6 11 7.11929 11 8.5C11 9.88071 9.88071 11 8.5 11C7.11929 11 6 9.88071 6 8.5Z"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M5 2C3.34315 2 2 3.34315 2 5V19C2 20.6569 3.34315 22 5 22H19C20.6569 22 22 20.6569 22 19V5C22 3.34315 20.6569 2 19 2H5ZM5 4C4.44772 4 4 4.44772 4 5V19C4 19.4288 4.2699 19.7946 4.64909 19.9367L15.2929 9.29289C15.6834 8.90237 16.3166 8.90237 16.7071 9.29289L20 12.5858V5C20 4.44772 19.5523 4 19 4H5ZM8.5 6C7.11929 6 6 7.11929 6 8.5C6 9.88071 7.11929 11 8.5 11C9.88071 11 11 9.88071 11 8.5C11 7.11929 9.88071 6 8.5 6ZM20 19C20 19.5523 19.5523 20 19 20H7.41421L16 11.4142L20 15.4142V19ZM8.5 8C8.22386 8 8 8.22386 8 8.5C8 8.77614 8.22386 9 8.5 9C8.77614 9 9 8.77614 9 8.5C9 8.22386 8.77614 8 8.5 8Z"></path>
    </svg>
  </template>
  <script>
    import { defineComponent } from "vue";

    export default defineComponent({
      name: "OiImage",
      props: {
        size: {
          type: Number,
          default: 16
        },
        color: {
          type: String,
          default: "currentColor"
        }
      }
    });
  </script>
