<template>
  <div class="feedback-container">
    <div class="feedback-form">
      <h2>Напишите нам</h2>
      <form class="form" @submit.prevent="submitForm">
        <input
          style="font-size: 16px; width: 313px; height: 24px; border-radius: 10px"
          v-model="formData.name"
          type="text"
          placeholder="Имя"
          required
        />
        <input
          style="font-size: 16px; width: 313px; height: 24px; border-radius: 10px"
          v-model="formData.email"
          type="email"
          placeholder="Email"
          required
        />
        <textarea
          style="font-size: 16px; width: 313px; height: 97px"
          v-model="formData.message"
          placeholder="Ваше сообщение"
          required
        ></textarea>
        <button class="but but_five" type="submit">Отправить</button>
      </form>
    </div>
    <div class="feedback-info">
      <span class="quote-mark">
        <img src="../assets/img/Vector.svg" alt="" />
      </span>
      <p>
        Уважаемый пользователь!<br />
        Если у вас есть предложения, комментарии или замечания по улучшению нашей платформы для
        бронирования коворкингов, мы будем рады услышать ваше мнение! Ваши отзывы помогают нам
        становиться лучше и делать платформу еще удобнее.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FeedbackForm',
  data() {
    return {
      formData: {
        name: '',
        email: '',
        message: '',
      },
    }
  },
  methods: {
    submitForm() {
      console.log('Form Submitted', this.formData)
      // Здесь может быть отправка данных на сервер через axios или fetch
      alert('Ваше сообщение отправлено!')
      // Очистка формы
      this.formData = { name: '', email: '', message: '' }
    },
  },
}
</script>

<style scoped>
.but_five {
  height: 50px;
  width: 152px;
  margin-top: 10px;
}

.form {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.feedback-container {
  display: flex;
  justify-content: center;
  align-items: flex-start;
  gap: 2rem;
  margin-top: 150px;
  background: #fff;
}

.feedback-form {
  flex-direction: column;
  display: flex;
  align-items: center;
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
  padding: 2rem;
  width: 329px;
  height: 387px;
}

h2 {
  color: #0078ff;
  font-size: 36px;
  margin-bottom: 1rem;
}

input,
textarea {
  width: 100%;
  padding: 0.5rem;
  margin: 0.5rem 0;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  background-color: #ff8c00;
  color: #fff;
  border: none;
  padding: 0.75rem 1.5rem;
  border-radius: 5px;
  cursor: pointer;
  font-size: 1rem;
  border-radius: 25px;
}

button:hover {
  background-color: #e67e00;
}

.feedback-info {
  max-width: 500px;
}

.feedback-info .quote-mark {
  font-size: 3rem;
  color: #ff8c00;
  margin-right: 0.5rem;
}

.feedback-info p {
  font-size: 18px;
  color: #333;
  line-height: 1.5;
  margin-top: -39px;
  margin-left: 41px;
}
</style>
