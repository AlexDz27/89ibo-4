<template>
  <header class="header cont">
    <h1 class="app-title">KIBERone Result</h1>
    <h3 class="app-descr">Сервис для загрузки/просмотра результатов работы ученика</h3>
  </header>

  <main class="main cont">
    <form method="POST" class="enter-form">
      <p>Введите фамилию и имя ученика, чтобы получить доступ к его результатам:</p>
      <input name="nameSurname" required class="form-input"><br><br>
      <button type="submit" class="form-submit-btn">Войти</button>
    </form>
  </main>
</template>
