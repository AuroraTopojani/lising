<template>
  <main class="container bg-white mx-auto">
      <section class="col-sm-5 col-md-7 col-lg-12">
       <div class="d-flex justify-content-around text-center">
         <img class="img-fluid ratio-13x10" src="../assets/images/Picture1.jpg" alt="..." />
       </div>
      <div class=" justify-content-around text-left ms-5 me-5">
       <p>Доколку сакате да купите возило на лизинг Ве молиме детално прегледајте ги податоците на оваа страна.
         Подолу имате калкулатор со кој можете орентационо <br/>да ги пресметате ратите за лизингот.
         Плаќањето можете да го прилагодите според вашите можности и потреби.На пример можете да си одредите
         фиксен дел за Учество кој ќе го платите, а останата сума да ја плаќате на онолку рати колку што Ви одговара.</p>

        <p>НАПОМЕНА: дел од трошоците за процедурата зa лизинг се фиксни и се плаќаат на лизинг компанијата.
          Корисникот на лизинг е обврзан да го осигура возилото со целосно КАСКО осигурување за целото времетраење на лизингот, вклучувајќи и додаток во случај на кражба и проневера
        </p>
      </div>
      </section>

    <five-steps title="five-steps-for-rent="/>
    <for-individuals/>
    <for-legal-entities/>

    <p class="text-danger"><i>* НАПОМЕНА: ДОКОЛКУ ПОДАТОЦИТЕ КОИ ГИ ОСТАВАТЕ ПРИ ПРЕД-ОДОБРУВАЊЕТО НЕ СЕ
      ТОЧНИ И ПРЕЦИЗНИ МОЖНО <br/>Е АПЛИКАЦИЈАТА ЗА ЛИЗИНГ ДА ВИ БИДЕ ОДБИЕНА ИЛИ ПРОЛОНГИРАНА
      ОД СТРАНА НА БАНКАТА И ПРИТОА ГО ГУБИТЕ ОСТАВЕНИОТ КАПАР.</i></p>

  </main>
</template>
<script>
import fiveSteps from "./fiveSteps";
import forIndividuals from "./forIndividuals";
import forLegalEntities from "./forLegalEntities";
export default {

  components:{
    fiveSteps,
    forIndividuals,
    forLegalEntities,
  },


};

</script>

<style scoped lang="scss">


</style>
