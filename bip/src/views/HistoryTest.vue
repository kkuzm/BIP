<template>
  <div>
    <div class="page-title">
      <h3>История
      </h3>
    </div>

    <div class="history-chart">
      <canvas></canvas>
    </div>

    <section>
      <table>
        <thead>
        <tr>
          <th>#</th>
          <th>Дисциплина</th>
          <th>Дедлайн</th>
          <th>Открыть</th>
        </tr>
        </thead>

        <tbody>
        <tr>
          <td>1</td>
          <td>Название</td>
          <td>01.01.2022 23:59</td>
          <td>
            <button class="btn-small btn">
              <router-link to ="/detail" class="material-icons">open_in_new</router-link>
            </button>
          </td>
        </tr>
        </tbody>
      </table>
    </section>
  </div>
</template>