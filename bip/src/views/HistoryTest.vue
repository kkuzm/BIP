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
          <th>Дата дедлайна</th>
          <th>Открыть</th>
        </tr>
        </thead>

        <tbody>
        <tr>
          <td>1</td>
          <td>Название</td>
          <td>23.04.2022</td>
          <td>
            <button class="btn-small btn">
              <i class="material-icons">open_in_new</i>
            </button>
          </td>
        </tr>
        </tbody>
      </table>
    </section>
  </div>
</template>