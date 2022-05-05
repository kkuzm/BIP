<template>
  <ul class="sidenav app-sidenav open">
<router-link
      v-for="link in links"
      :key="link.url"
      active-class="active"
      :to="link.url"
    >
      <li :class="[isExactActive && 'active']">
        <a :href="href" @click="navigate" class="waves-effect waves-orange pointer">{{
          link.title
        }}</a>
      </li>
    </router-link>
  </ul>
</template>

 <script>
export default {
  data: () => ({
    links: [
      { title: "Домашняя страница", url: "/" },
      { title: "История", url: "/history" },
      { title: "Новая запись", url: "/record" },
      { title: "Редактирование записи", url: "/edit" },
    ],
  }),
};
</script>>