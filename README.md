# usefullInJs

dateFormatter(date) {
            return `${date.getDate()}-${("0" + (date.getMonth() + 1)).slice(-2)}-${date.getFullYear()}`;
        },
