<template>
  <a-layout style="min-height: 100vh">
    <a-layout-sider v-model="collapsed" collapsible>
      <div class="logo">
        <svg viewBox="0 0 1024 1024" width="32px" height="32px" fill="currentColor">
          <path d="M99.096 315.634s-82.58-64.032-82.58-132.13c0-66.064 33.032-165.162 148.646-148.646 83.37 11.91 99.096 165.162 99.096 165.162l-165.162 115.614zM924.906 315.634s82.58-64.032 82.58-132.13c0-66.064-33.032-165.162-148.646-148.646-83.37 11.91-99.096 165.162-99.096 165.162l165.162 115.614z" fill="#6B676E" p-id="1143" />
          <path d="M1024 561.548c0 264.526-229.23 429.42-512.002 429.42S0 826.076 0 561.548 283.96 66.064 512.002 66.064 1024 297.022 1024 561.548z" fill="#FFEBD2" p-id="1144" />
          <path d="M330.324 842.126c0 82.096 81.34 148.646 181.678 148.646s181.678-66.55 181.678-148.646H330.324z" fill="#E9D7C3" p-id="1145" />
          <path d="M644.13 611.098C594.582 528.516 561.55 512 512.002 512c-49.548 0-82.58 16.516-132.13 99.096-42.488 70.814-78.73 211.264-49.548 247.742 66.064 82.58 165.162 33.032 181.678 33.032 16.516 0 115.614 49.548 181.678-33.032 29.18-36.476-7.064-176.93-49.55-247.74z" fill="#FFFFFF" p-id="1146" />
          <path d="M611.098 495.484c0-45.608 36.974-82.58 82.58-82.58 49.548 0 198.194 99.098 198.194 165.162s-79.934 144.904-148.646 99.096c-49.548-33.032-132.128-148.646-132.128-181.678zM412.904 495.484c0-45.608-36.974-82.58-82.58-82.58-49.548 0-198.194 99.098-198.194 165.162s79.934 144.904 148.646 99.096c49.548-33.032 132.128-148.646 132.128-181.678z" fill="#6B676E" p-id="1147" />
          <path d="M512.002 726.622c-30.06 0-115.614 5.668-115.614 33.032 0 49.638 105.484 85.24 115.614 82.58 10.128 2.66 115.614-32.944 115.614-82.58-0.002-27.366-85.556-33.032-115.614-33.032z" fill="#464655" p-id="1148" />
          <path d="M330.324 495.484m-33.032 0a33.032 33.032 0 1 0 66.064 0 33.032 33.032 0 1 0-66.064 0Z" fill="#464655" p-id="1149" />
          <path d="M693.678 495.484m-33.032 0a33.032 33.032 0 1 0 66.064 0 33.032 33.032 0 1 0-66.064 0Z" fill="#464655" p-id="1150" />
        </svg>
      </div>
      <a-menu theme="dark" :default-selected-keys="['0']" mode="inline">
        <a-menu-item key="0">
          <router-link to="/">
            <a-icon type="bank" />
            <span>Главная</span>
          </router-link>
        </a-menu-item>
        <a-sub-menu key="1">
          <span slot="title">
            <a-icon type="apartment" />
            <span>Сведения об образовательной организации</span>
          </span>
          <a-menu-item key="3">
            <router-link to="/basic_information">
              Основные сведения
            </router-link>
          </a-menu-item>
          <a-menu-item key="4">
            <router-link to="/governing_bodies">
              Структура и органы управления
            </router-link>
          </a-menu-item>
          <a-menu-item key="5">
            <router-link to="/documents">
              Документы
            </router-link>
          </a-menu-item>
          <a-menu-item key="6">
            <router-link to="/education">
              Образование
            </router-link>
          </a-menu-item>
          <a-menu-item key="7">
            <router-link to="/educational_standards">
              Образовательные стандарты
            </router-link>
          </a-menu-item>
          <a-menu-item key="8">
            <router-link to="/guide">
              Руководство
            </router-link>
          </a-menu-item>
          <a-menu-item key="9">
            <router-link to="/teaching_staff">
              Педагогический состав
            </router-link>
          </a-menu-item>
          <a-menu-item key="10">
            <router-link to="/equipment">
              МТО и оснащенность
            </router-link>
          </a-menu-item>
          <a-menu-item key="11">
            <router-link to="/scholarships">
              Стипендии и иные виды поддержки
            </router-link>
          </a-menu-item>
          <a-menu-item key="12">
            <router-link to="/services">
              Платные образовательные услуги
            </router-link>
          </a-menu-item>
          <a-menu-item key="13">
            <router-link to="/financial_activities">
              Финансово-хозяйственная деятельность
            </router-link>
          </a-menu-item>
          <a-menu-item key="14">
            <router-link to="/vacant_places">
              Вакантные места для приема (перевода)
            </router-link>
          </a-menu-item>
        </a-sub-menu>
        <a-sub-menu key="2">
          <span slot="title">
            <a-icon type="team" />
            <span>Для учеников</span>
          </span>
          <a-menu-item key="3">
            <router-link to="/schedule_lessons">
              Расписание уроков
            </router-link>
          </a-menu-item>
          <a-menu-item key="4">
            <router-link to="/call_schedule">
              Расписание звонков
            </router-link>
          </a-menu-item>
          <a-menu-item key="5">
            <router-link to="/extracurricular_Schedule">
              Расписание внеурочной деятельности
            </router-link>
          </a-menu-item>
          <a-menu-item key="6">
            <router-link to="/class_hours_schedule">
              Расписание классных часов
            </router-link>
          </a-menu-item>
          <a-menu-item key="7">
            <router-link to="/consultation_schedule">
              Расписание консультаций заочного обучения
            </router-link>
          </a-menu-item>
          <a-menu-item key="8">
            <router-link to="/individual_schedule">
              Расписание индивидуальных занятий
            </router-link>
          </a-menu-item>
          <a-menu-item key="9">
            <router-link to="/internet">
              Безопасный интернет
            </router-link>
          </a-menu-item>
          <a-menu-item key="10">
            <router-link to="/summer_camp">
              Отзыв о работе летнего лагеря
            </router-link>
          </a-menu-item>
        </a-sub-menu>
        <a-sub-menu key="9">
          <span slot="title">
            <a-icon type="team" />
            <span>Для родителей</span>
          </span>
          <a-menu-item key="3">
            <router-link to="/hotline">
              Горячая линия
            </router-link>
          </a-menu-item>
          <a-menu-item key="4">
            <router-link to="/accessible_environment">
              Доступная среда
            </router-link>
          </a-menu-item>
          <a-menu-item key="5">
            <router-link to="/call_schedule">
              Расписание звонков
            </router-link>
          </a-menu-item>
          <a-menu-item key="6">
            <router-link to="/admission_rules">
              Правила приема
            </router-link>
          </a-menu-item>
          <a-menu-item key="7">
            <router-link to="/first_grader">
              Памятка для родителей первоклассников
            </router-link>
          </a-menu-item>
          <a-menu-item key="8">
            <router-link to="/educational_plan">
              План воспитательной работы
            </router-link>
          </a-menu-item>
          <a-menu-item key="9">
            <router-link to="/order_transfer">
              Порядок и основания перевода
            </router-link>
          </a-menu-item>
          <a-menu-item key="10">
            <router-link to="/appearance_requirements">
              Требования к внешнему виду
            </router-link>
          </a-menu-item>
          <a-menu-item key="11">
            <router-link to="/nutrition_information">
              Информация об условиях питания
            </router-link>
          </a-menu-item>
          <a-menu-item key="12">
            <router-link to="/fixed_territories">
              Закрепленные территории
            </router-link>
          </a-menu-item>
          <a-menu-item key="13">
            <router-link to="/electronic_diary">
              Электронный дневник
            </router-link>
          </a-menu-item>
          <a-menu-item key="14">
            <router-link to="/vacation_information">
              Информация об летнем отдыхе
            </router-link>
          </a-menu-item>
        </a-sub-menu>
        <a-menu-item key="10">
          <router-link to="/emergency">
            <a-icon type="book" />
            <span>Профилактическая информация при поведении в ЧС</span>
          </router-link>
        </a-menu-item>
        <a-menu-item key="11">
          <router-link to="/traffic_laws">
            <a-icon type="profile" />
            <span>Профилактическая информация по ПДД</span>
          </router-link>
        </a-menu-item>
        <a-menu-item key="12">
          <router-link to="/electrical">
            <a-icon type="thunderbolt" />
            <span>Правила пользования электроприборами</span>
          </router-link>
        </a-menu-item>
        <a-menu-item key="13">
          <router-link to="/gia">
            <a-icon type="star" />
            <span>ГИА</span>
          </router-link>
        </a-menu-item>
        <a-menu-item key="14">
          <router-link to="/veterans">
            <a-icon type="user" />
            <span>Ветераны педагогического труда</span>
          </router-link>
        </a-menu-item>
        <a-menu-item key="15">
          <router-link to="/us">
            <a-icon type="rocket" />
            <span>Нам 80!</span>
          </router-link>
        </a-menu-item>
        <a-menu-item key="16">
          <router-link to="/gallery">
            <a-icon type="picture" />
            <span>Фотогалерея</span>
          </router-link>
        </a-menu-item>
        <a-menu-item key="17">
          <router-link to="/psychologist">
            <a-icon type="user" />
            <span>Школьный психолог</span>
          </router-link>
        </a-menu-item>
        <a-menu-item key="18">
          <router-link to="/feedback">
            <a-icon type="shake" />
            <span>Обратная связь</span>
          </router-link>
        </a-menu-item>
      </a-menu>
    </a-layout-sider>
    <a-layout>
      <a-layout-header style="background: #fff; padding: 0">
        <h2 class="header__caption">МАОУ "СОШ №1"</h2>
      </a-layout-header>
      <a-layout-content style="margin: 0 16px">
        <a-breadcrumb style="margin: 16px 0">
          <a-breadcrumb-item>Главная</a-breadcrumb-item>
        </a-breadcrumb>
        <div :style="{ padding: '24px', background: '#fff', minHeight: '360px' }">
          <nuxt />
        </div>
      </a-layout-content>
      <a-layout-footer style="text-align: center">
        ©2020 МAОУ "CОШ №1" г.Чебоксары
      </a-layout-footer>
    </a-layout>
  </a-layout>
</template>

<script>
export default {
  data() {
    return {
      collapsed: false,
    };
  },
};
</script>

