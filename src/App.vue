<template>
  <section>
    <h2>Meus Amigos</h2>
    <ul>
      <li></li>
    </ul>
  </section>
</template>

<script>
export default {
  data() {
    return {
      friends: [
        {
          id: 1123,
          name: 'Wladi Veras',
          phone: '00 12345 6789',
          email: 'wladi@admin.com',
        },
        {
          id: 5233,
          name: 'Let Martins',
          phone: '11 09876 5432',
          email: 'let@mtmt.rj',
        },
      ],
    };
  },
};
</script>