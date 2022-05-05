<template>
  <div>
    <div class="page-title">
      <h3>Редактирование записи</h3>
    </div>

    <div class="input-field">
      <input id="description" type="text" />
      <label for="description">Заголовок</label>
      <span class="helper-text invalid">Header</span>
    </div>

    <div class="input-field">
      <input id="description" type="text" />
      <label for="description">Дисциплина</label>
      <span class="helper-text invalid">Subject</span>
    </div>

    <head>
      <meta charset="utf-8" />
      <title>Календарь</title>
    </head>
    <body>
      <form>
        <p>
          Выберите дату дедлайна:
          <input
            type="date"
            name="calendar"
            value="2022-01-01"
            max="2024-01-01"
            min="2021-01-01"
          />
          <input type="submit" value="Отправить" />
        </p>
      </form>
    </body>

    <div class="input-field">
      <input id="description" type="text" />
      <label for="description">Описание</label>
      <span class="helper-text invalid">Description</span>
    </div>
    <div class="row">
      <button class="btn waves-effect waves-light" type="submit">
        Обновить
        <i class="material-icons right">send</i>
      </button>
    </div>
  </div>
</template>