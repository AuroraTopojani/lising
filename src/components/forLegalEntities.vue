<template>
<section class="container">
<h1 class="text-center"><strong>Документација со барање за лизинг: ПРАВНИ ЛИЦА</strong></h1>
<h4>Со пополнето барање за одобрување на лизинг, профактура на добавувачот и прифатена лизинг понуда, потребно е да се приложат и:</h4>
<ul >
  <li v-for="docs in forLegalEntities" :key="docs.title" >
    <p class="mb-0">
      {{ docs.description }}
      <a :href="docs.link" target="”_blank”"
      ><strong>{{ docs.linkedTxt }}</strong></a></p>
  </li>
</ul>
<p>
  <strong
  >Документација треба да биде заверена со потпис и печат на овластеното
    лице!
  </strong>
</p>
<p>
  <strong>AUTOWELT</strong> го задржува правото да побара дополнителна
  документација за разгледување на барањата за одобрување на лизинг.
</p>
<hr />

</section>
</template>

<script>
export default {
  data() {
    return {

      forLegalEntities: [
        {
          description: "Барање за одобрување на лизинг",
          link: "https://s-leasing.mk/content/%D0%91%D0%B0%D1%80%D0%B0%D1%9A%D0%B5%20%D0%B7%D0%B0%20%D0%BE%D0%B4%D0%BE%D0%B1%D1%80%D1%83%D0%B2%D0%B0%D1%9A%D0%B5%20%D0%BD%D0%B0%20%D0%BB%D0%B8%D0%B7%D0%B8%D0%BD%D0%B3_Pravni%20Lica-11.01.2022.pdf",
        },
        {
          description: "Копија од тековна состојба, не постара од 6 недели",
        },
        {
          description: "Завршна сметка (биланс на состојба и биланс на успех за последните две фискални години)",
        },
        {
          description: "Аналитички заклучни листови кон завршните сметки за последните две години",
        },
        {
          description: "Аналитички заклучен лист за тековната година со последен датум на книжење",
        },
        {
          description: "Согласност за извадок од Македонско Кредитно Биро",
          link: "https://s-leasing.mk/content/%D0%A1%D0%BE%D0%B3%D0%BB%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%20%D0%B7%D0%B0%20%D0%B8%D0%B7%D0%B2%D0%B0%D0%B4%D0%BE%D0%BA%20%D0%BE%D0%B4%20%D0%9C%D0%B0%D0%BA%D0%B5%D0%B4%D0%BE%D0%BD%D1%81%D0%BA%D0%BE%20%D0%9A%D1%80%D0%B5%D0%B4%D0%B8%D1%82%D0%BD%D0%BE%20%D0%91%D0%B8%D1%80%D0%BE.pdf",
        },
        {
          description: "Изјава за вистински сопственик",
          link: "https://s-leasing.mk/content/Izjava-za-vistinski-sopstvenik.pdf",
        },
      ],
    }
  },
  props: {

    description: {
      type: String,
    },
    linkTxt:{
      type: String,
    },
    link:{
      type:String,
    }
  },
};
</script>