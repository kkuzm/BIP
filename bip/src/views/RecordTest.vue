<template>
  <div>
    <div class="page-title">
      <h3>Новая запись</h3>
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
    </head>
    <body>
      <form>
        <p>
          Дедлайн
          <input type="datetime-local" id="localdate" name="Deadline" />
        </p>
        <p>
          Начальная дата и время показа уведомлений
          <input type="datetime-local" id="localdate" name="NotificationDate" />
        </p>
        <p>
          Частота уведомлений
          <input type="time" id="time" name="NotificationFrequency" />
        </p>
      </form>
    </body>

    <div class="input-field">
      <input id="description" type="text" />
      <label for="description">Описание</label>
      <span class="helper-text invalid">Description</span>
    </div>

    <button class="btn waves-effect waves-light" type="submit">
      Создать
      <i class="material-icons right">send</i>
    </button>
  </div>
</template>
