<template>
  <div>
    <article class="m-block">
      <div class="m-inform">
        <a-row :gutter="[8,8]">
          <a-col :md="12" :xs="{span: 24}">
            <div calss="m-inform__img">
              <img src="/images/model-anastasiya-kovaleva-01.jpg" alt="Кравцова Марина Михайловна">
            </div>
          </a-col>
          <a-col :md="12" :xs="{span: 24}">
            <div calss="m-inform__text">
              <h3>Кравцова Марина Михайловна</h3>
              <p>Профессиональный психолог, выпускницей факультета психологии МГУ, 
                специализировавшейся по кафедре возрастной психологии. В ее обязанности 
                входит работа с учащимися 1- 5 классов, их родителями и учителями.
              </p>
            </div>
          </a-col>
        </a-row>
      </div>
    </article>
    <article class="m-block">
      <a-row :gutter="[8,8]">
        <a-col :md="12" :xs="{span: 24}">
          <p class="text__p">Проводятся индивидуальные и групповые занятия со 
            школьниками (повышение мотивации к учебной деятельности, налаживание 
            межличностных отношений).</p>
          <p class="text__p">Необходимо, чтобы ребенок, родители и учителя не 
            были “изолированы” друг от друга, чтобы между ними не было противостояния.</p>
        </a-col>
        <a-col :md="12" :xs="{span: 24}">
          <p class="text__p">Психолог большую часть времени находится на виду, в контакте 
            с учителями, родителями или учениками. Психолог постоянно находится в потоке 
            многочисленной и зачастую противоречивой информации, в которой ему надо 
            ориентироваться.</p>
        </a-col>
      </a-row>
    </article>
    <article class="m-block">
      <a-descriptions title="Контактная информация">  
        <a-descriptions-item label="E-mail">
          psychologist@cap.ru
        </a-descriptions-item>
        <a-descriptions-item label="Телефон">
          58-77-49
        </a-descriptions-item>
        <a-descriptions-item label="Режим работы">
          с 8.00 до 17.00
        </a-descriptions-item>
      </a-descriptions>
    </article>
  </div>
</template>


<script>
export default {
  data() {
    return {

    };
  },
};
</script>


