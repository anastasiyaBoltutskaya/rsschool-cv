### CV
## **Anastasiya Boltutskaya**
![Photo](1632480363198.jpg)

*******************************************

## **Contacts**

tel.number: + 37529 8293868
e-mail: nastia1oskirko@gmail.com

********************************************

## **About myself**

Graduated BrSTU in 2016 year in speciality "Heat and Gas Supply, Ventilation and Air Protection".
Have been working for 3 years an engineer in gassupply organization.
Intrested in web develompent, badminton, swimming.


********************************************

## **Skills**

1. Git
2. HTML&CSS
3. Basic knowledge of Python
4. PyCharm


********************************************

## **English level**

  B1

********************************************  
## **Code Example**

```
def quiz(them):
    answers = []
    correct_answers_count = 0

    install.install_lib("pandas")
    import pandas as pd
    df = pd.read_csv(f"{THEMES_PATH}/{them}", delimiter=";", dtype=str)\
        .sample(frac=1)\
        .reset_index(drop=True)\
        .head(COUNT_QUESTIONS)

    for idx in df.index:
        _question = df['question'][idx]
        _variant = df['variant'][idx]
        _answer = df['answer'][idx]
        print(_question, _variant, sep='\n')
        answer = validate.handle_answer()
        # сравниваем ответы
        if answer == _answer:
            print(f'{answer} - Отлично\n')
            correct_answers_count += 1
        else:
            print(f'{answer} - К сожалению нет\n', end='\n')

        answers.append(f"{_question}\n{_variant}\nВаш ответ: {answer}\nПравельный ответ: {_answer}")
    return correct_answers_count, answers
    ```


