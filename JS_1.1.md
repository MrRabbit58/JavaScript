1*:
Преобразовать написанный код в 26-33 пунктах в функцию, принимающую на вход возраст.
Вывести в консоль результат работы функции с возрастами 17, 18, 61
  function checkAge(age_1, age_2, age_3){
      switch(true){
          case age_1 < age_2: console.log("You don’t have access cause your age is " + age_1 + " It’s less then");
              break;
          case age_1 >= age_2 && age_1 <age_3: console.log("Welcome!");
              break;
          case age_1 > age_3: console.log("Keep calm and look Culture channel");
              break;
          default: console.log("Technical work")
      }
  }
  
  checkAge(17, 18, 61)
