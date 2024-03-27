<form action="#" method="post" target="_blank">
    <h2>Бронирование билетов онлайн</h2>
    <fieldset>
      <legend>Персональные данные</legend>
      <ul>
        <li>
          <label for="name">Имя:</label>
          <input type="text" name="name" placeholder="Иван Иванов" id="name" required>
        </li>
        <li>
          <label for="age">Возраст:</label>
          <input type="number" name="age" placeholder="27" id="age" min="0" max="125">
        </li>
      </ul>
    </fieldset>
    <fieldset>
      <legend>Контакты</legend>
      <ul>
        <li>
          <label for="email">E-mail:</label>
          <input type="email" name="mail" placeholder="ivanov@gmail.com" id="email" required>
        </li>
        <li>
          <label for="number">Телефон:*</label>
          <input type="tel" name="phone" placeholder="+7 000 000-00-00" id="number" maxlength="21" required>
        </li>
      </ul>
    </fieldset>
  
    <fieldset>
      <legend>Предпочтения</legend>
      <ul>
        <li>
          <input type="radio" name="preference" id="front" value="frontend" checked>
          <label for="front">Гостиница у моря</label>
        </li>
        <li>
          <input type="radio" name="preference" id="back" value="backend">
          <label for="back">Горный курорт</label>
        </li>
      </ul>
    </fieldset>
    <div>
      <button type="submit">Отправить</button>
    </div>
  </form>
  
  <style>
    button{
        border-radius: 10px;
        background-color: green;
        color: white;

    }
    h2{
        text-align: center;
        font-size: 20px;
    }
  </style>