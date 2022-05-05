<template>
  <div>
    <div>
      <div class="breadcrumb-wrap">
        <a href="/history" class="breadcrumb">История</a>
        <a class="breadcrumb"> Описание задачи </a>
      </div>
      <div class="row">
        <div class="col s12 m6">
          <div class="card red">
            <div class="card-content white-text">
              <p>Заголовок:</p>
              <p>Дисциплина:</p>
              <p>Дедлайн:</p>
              <p>Описание:</p>
              <button>
                <router-link to="/edit">Редактировать</router-link>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
