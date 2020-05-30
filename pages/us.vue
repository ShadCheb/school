<template>
  <div>
    <article class="m-block">
      <h2 class="caption__h2">Нам 80!</h2>
      <div class="m-inform">
        <a-row :gutter="[8,8]">
          <a-col :md="12" :xs="{span: 24}">
            <img 
              src="http://sarg-pressa.ru/wp-content/uploads/2017/06/Nam-300x200.jpg" 
              alt="Нам 80!"
            >
          </a-col>
          <a-col :md="12" :xs="{span: 24}">
            <div calss="m-inform__text">
              <h3>Нам 80!</h3>
              <p>Были на празднике и воспоминания, и радость встреч, и искренние 
                признания, и трогательные до слез минуты.
              </p>
            </div>
          </a-col>
        </a-row>
      </div>
    </article>
    <article class="m-block">
      <p class="text__p">В этот день прозвучало много теплых слов. На торжество постарались 
        пригласить всех своих коллег.</p>
      <p class="text__p">К этой дате было приурочено открытие школьного музея, в котором 
        представлена история учебного заведения от его основания до наших дней. Был проведён 
        праздничный концерт, на котором чествовались ветераны педагогического труда, награждены 
        грамотами различного уровня все работники школы..</p>
    </article>
    <article class="m-block">
      <div class="m-video">
        <iframe width="100%" height="100%" src="https://www.youtube.com/embed/sV9bQDIsjLs" 
          frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
          allowfullscreen></iframe>
      </div>
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


