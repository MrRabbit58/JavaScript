3**:
Преобразовать 2* таким образом, чтобы значение '2' (строка в которой лежит ТОЛЬКО ЦИФРА) пропускалось, преобразовываясь в number

    function checkAge(age_1, age_2, age_3) {
        if (typeof (age_1) !== 'number' || typeof (age_2) !== 'number' || typeof (age_3) !== 'number') {
            age_1 = Number(age_1);
            age_2 = Number(age_2);
            age_3 = Number(age_3);
        
        }
       switch (true) {
            case age_1 < age_2:
                console.log("You don’t have access cause your age is " + age_1 + " It’s less then");
                break;
            case age_1 >= age_2 && age_1 < age_3:
                console.log("Welcome!");
                break;
            case age_1 > age_3:
                console.log("Keep calm and look Culture channel");
                break;
            default:
                console.log("Technical work")
        }
    }
    checkAge(80, "18", "61")
