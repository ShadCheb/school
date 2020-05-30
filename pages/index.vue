<template>
  <div>
    <article class="m-block">
      <a-carousel autoplay>
        <div><h3>1</h3></div>
        <div><h3>2</h3></div>
        <div><h3>3</h3></div>
        <div><h3>4</h3></div>
      </a-carousel>
    </article>
    <article class="m-block">
      <h2 class="caption__h2">Ссылки</h2>
      <a-list item-layout="horizontal" :data-source="listLinks">
        <a-list-item slot="renderItem" slot-scope="item">
          <a-list-item-meta>
            <a slot="title" :href="item.link" target="_blank">{{ item.title }}</a>
          </a-list-item-meta>
        </a-list-item>
      </a-list>
    </article>
    <article class="m-block">
      <h2 class="caption__h2">Новости</h2>
      <div class="m-news">
        <a-row :gutter="[8,8]">
          <a-col :md="8" :sm="{span: 12}" :xs="{span: 24}">
            <a-card hoverable>
              <img
                slot="cover"
                alt="Скарлетт Йоханссон"
                src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSoqyz0gbWS0Sahbq9T79GDeEpQt6JLDRdUG1594UUAhhsQLaqa&s"
              />
              <a-card-meta title="Новый преподаватель по ядерной физике">
                <template slot="description"><p class="date">20.05.2020</p></template>
              </a-card-meta>
            </a-card>
          </a-col>
          <a-col :md="8" :sm="{span: 12}" :xs="{span: 24}">
            <a-card hoverable>
              <img
                slot="cover"
                alt="Скарлетт Йоханссон"
                src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSoqyz0gbWS0Sahbq9T79GDeEpQt6JLDRdUG1594UUAhhsQLaqa&s"
              />
              <a-card-meta title="Новый преподаватель по ядерной физике">
                <template slot="description"><p class="date">20.05.2020</p></template>
              </a-card-meta>
            </a-card>
          </a-col>
          <a-col :md="8" :sm="{span: 12}" :xs="{span: 24}">
            <a-card hoverable>
              <img
                slot="cover"
                alt="Скарлетт Йоханссон"
                src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSoqyz0gbWS0Sahbq9T79GDeEpQt6JLDRdUG1594UUAhhsQLaqa&s"
              />
              <a-card-meta title="Новый преподаватель по ядерной физике">
                <template slot="description"><p class="date">20.05.2020</p></template>
              </a-card-meta>
            </a-card>
          </a-col>
          <a-col :md="8" :sm="{span: 12}" :xs="{span: 24}">
            <a-card hoverable>
              <img
                slot="cover"
                alt="Скарлетт Йоханссон"
                src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSoqyz0gbWS0Sahbq9T79GDeEpQt6JLDRdUG1594UUAhhsQLaqa&s"
              />
              <a-card-meta title="Новый преподаватель по ядерной физике">
                <template slot="description"><p class="date">20.05.2020</p></template>
              </a-card-meta>
            </a-card>
          </a-col>
        </a-row>
      </div>
    </article>
  </div>
</template>


<script>
export default {
  data() {
    return {
      listLinks: [
        {
          title: 'Министерство образования и науки РФ',
          link: 'https://minobrnauki.gov.ru/'
        },
        {
          title: 'Департамент образования',
          link: 'http://chebobraz.cap.ru/'
        },
        {
          title: 'Федеральная служба по надзору в сфере образования',
          link: 'http://www.obrnadzor.gov.ru/ru/'
        },
        {
          title: 'Администрация РМР',
          link: 'http://chebs.cap.ru/'
        },
        {
          title: 'Наши координаты',
          link: 'https://www.google.ru/maps/place/%D0%A8%D0%BA%D0%BE%D0%BB%D0%B0+%E2%84%96+31/@56.1405524,47.2113578,18z/data=!4m8!1m2!2m1!1z0YjQutC-0LvQsCDRgNGP0LTQvtC8INGBINCn0LXQsdC-0LrRgdCw0YDRiw!3m4!1s0x0:0xb27091f015eccfac!8m2!3d56.1407139!4d47.2120607'
        },
      ],
    };
  },
};
</script>



