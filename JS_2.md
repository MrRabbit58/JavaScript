    function script(input){
        switch(true){
            case input.trim() === "": console.log("Строка не должна быть пустой")
                break;
            case input.length < 5: console.log("Минимум 5 символов в строке")
                break;
            case input.length > 64: console.log("Максимум 64 символа в строке")
                break;
            case (!/[a-zA-Z]/.test(input)): console.log("В строке должны быть буквы")
                break;
            case (!/[A-Z]/.test(input)): console.log("Должна быть хотя бы одна буква в верхнем регистре")
                break;
            case (!/[0-9]/.test(input)): console.log("Должна быть хотя бы одна цифра")
                    break;
            case (!/@/.test(input)): console.log("Должна быть хотя бы одна @")
                break;
            default: return true
        }
    }
    
    script("dhjKj@9")
