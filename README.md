## [HW_1 Работа в Postman](#1)    
[EP_1 /get_method](#2)  
[EP_2 /user_info_3](#3)   
[EP_3 /object_info_1](#4)  
[EP_4 /object_info_2](#5)    
[EP_5 /object_info_3](#6)  
[EP_6 /object_info_4](#7)   
[EP_7 /user_info_2](#8)   
    
------ 
  
## [HW_2 Postman](#9)    
[EP /first](#10)  
[EP_2 /user_info_3](#11)  
[EP_5 /object_info_3](#12)  
[EP_6 /object_info_4](#13)  
[EP_7 /user_info_2](#14)  
  
-----
  
## [HW_2* Postman](#15)  
[EP_7 /user_info_2](#16)  
[EP_6 /object_info_4](#17)  
[EP_5 /object_info_3](#18)  
[EP_7 /user_info_2](#19)  
  
-----  
-----  
  
<a name="1"></a>
## HW_1 Работа в Postman
#### Создать запросы в Postman.  
  
*Create new collection - New request*  
  
Protocol: http  
IP: 162.55.220.72  
Port: 5005
  
*в поле "Enter request URL" вписать http://162.55.220.72:5005/ и нажать Save*  
  
  
  
-----
## EP_1  <a name="2"></a>
Method: GET  
EndPoint: /get_method  
request url params:  
 name: str  
 age: int  
  
*Переименовать "New Request" в "EP1"*  
*1. Выбрать метод GET, в поле "Enter request URL" дописать "/get_method", чтоб получилось http://162.55.220.72:5005/get_method*  
*2. выбрать "Params"*  
*2.1. в столбец "KEY" добавить две строки с именами "name" и "age"*  
*2.2. в столбец "VALUE" добавить значения "Marg0sh" и "34" напротив ключей "name" и "age" соответственно*  
*3. нажать Save и Send*    
  
response:  
*ответ*  
```json
[
    "Marg0sh",
    "34"
]
```
  
*в поле "Enter request URL" будет отображаться URL http://162.55.220.72:5005/get_method?name=Marg0sh&age=34*  
  
  
-----
  
## EP_2  <a name="3"></a>
Method: POST  
EndPoint: /user_info_3  
request form data:  
 name: str  
 age: int  
 salary: int  
  
*В коллекции Marg0sh создать "New Request" и переименовать его в "EP2"*  
*1. Выбрать метод Post, в поле "Enter request URL" вписать http://162.55.220.72:5005/user_info_3*  
*2. выбрать "Body" в нем "from-data"*  
*2.1. в столбец "KEY" добавить три строки с именами "name", "age" и "salary"*  
*2.2. в столбец "VALUE" добавить значения "Marg0sh", "34" и "50000" напротив ключей "name", "age" и "salary" соответственно*  
*3. нажать Save и Send* 

response:  
*ответ*  
```json
{   
    "age": "34",
    "family": {"children": [["Alex", 24], ["Kate", 12]],
               "u_salary_1_5_year": 200000},
    "name": "Marg0sh",
    "salary": 50000
}
```
  
*в поле "Enter request URL" URL не изменяется*  
  
  
  
-----
  
## EP_3  <a name="4"></a>
Method: GET
EndPoint: /object_info_1
request url params: 
 name: str
 age: int
 weight: int
  
*В коллекции Marg0sh создать "New Request" и переименовать его в "EP3"*  
*1. Выбрать метод Get, в поле "Enter request URL" вписать http://162.55.220.72:5005/object_info_1*  
*2. выбрать "Params"*  
*2.1. в столбец "KEY" добавить три строки с именами "name", "age" и "weight"*  
*2.2. в столбец "VALUE" добавить значения "Marg0sh", "34" и "70" напротив ключей "name", "age" и "weight" соответственно*  
*3. нажать Save и Send*
  
response:  
*ответ*  
```json
{
    "age": 34,
    "daily_food": 0.84,
    "daily_sleep": 175.0,
    "name": "Marg0sh"
}
```
  
*в поле "Enter request URL" будет отображаться URL http://162.55.220.72:5005/object_info_1?name=Marg0sh&age=34&weight=70*  
  
  
  
-----
  
## EP_4  <a name="5"></a>
Method: GET  
EndPoint: /object_info_2  
request url params:  
 name: str  
 age: int  
 salary: int  
  
*В коллекции Marg0sh создать "New Request" и переименовать его в "EP4"*  
*1. Выбрать метод Get, в поле "Enter request URL" вписать http://162.55.220.72:5005/object_info_2*  
*2. выбрать "Params"*  
*2.1. в столбец "KEY" добавить три строки с именами "name", "age" и "salary"*  
*2.2. в столбец "VALUE" добавить значения "Marg0sh", "34" и "50000" напротив ключей "name", "age" и "salary" соответственно*  
*3. нажать Save и Send*  
  
response: 
*ответ*  
```json
{   
    "person": {"u_age": 34,
               "u_name": ["Marg0sh", 50000, 34],
               "u_salary_5_years": 210000.0},
    "qa_salary_after_1.5_year": 165000.0,
    "qa_salary_after_12_months": 135000.0,
    "qa_salary_after_3.5_years": 190000.0,
    "qa_salary_after_6_months": 100000,
    "start_qa_salary": 50000
}
```
  
*в поле "Enter request URL" будет отображаться URL http://162.55.220.72:5005/object_info_2?name=Marg0sh&age=34&salary=50000*  
  
  
  
-----
## EP_5  <a name="6"></a>
Method: GET  
EndPoint: /object_info_3  
request url params:  
 name: str  
 age: int  
 salary: int  
  
*В коллекции Marg0sh создать "New Request" и переименовать его в "EP5"*  
*1. Выбрать метод Get, в поле "Enter request URL" вписать http://162.55.220.72:5005/object_info_3*  
*2. выбрать "Params"*  
*2.1. в столбец "KEY" добавить три строки с именами "name", "age" и "salary"*  
*2.2. в столбец "VALUE" добавить значения "Marg0sh", "34" и "50000" напротив ключей "name", "age" и "salary" соответственно*  
*3. нажать Save и Send*  
  
response:  
*ответ*
```json
{
    "age": "34",
    "family": {"children": [["Alex", 24], ["Kate", 12]],
               "pets": {"cat": {"age": 3, "name": "Sunny"},
                        "dog": {"age": 4, "name": "Luky"}},
               "u_salary_1_5_year": 200000},
    "name": "Marg0sh",
    "salary": 50000
}
```
   
*в поле "Enter request URL" будет отображаться URL http://162.55.220.72:5005/object_info_3?name=Marg0sh&age=34&salary=50000*  
  
  
  
-----
  
## EP_6  <a name="7"></a>
Method: GET  
EndPoint: /object_info_4  
request url params:  
 name: str  
 age: int  
 salary: int  
  
*В коллекции Marg0sh создать "New Request" и переименовать его в "EP6"*  
*1. Выбрать метод Get, в поле "Enter request URL" вписать http://162.55.220.72:5005/object_info_4*  
*2. выбрать "Params"*  
*2.1. в столбец "KEY" добавить три строки с именами "name", "age" и "salary"*  
*2.2. в столбец "VALUE" добавить значения "Marg0sh", "34" и "50000" напротив ключей "name", "age" и "salary" соответственно*  
*3. нажать Save и Send*  
  
response:  
*ответ*
```json
{
    "age": 34,
    "name": "Marg0sh",
    "salary": [50000, "100000", "150000"]
}
```
   
*в поле "Enter request URL" будет отображаться URL http://162.55.220.72:5005/object_info_4?name=Marg0sh&age=34&salary=50000*  
  
  
  
-----
  
## EP_7  <a name="8"></a>
Method: POST  
EndPoint: /user_info_2  
request form data:  
 name: str  
 age: int  
 salary: int    
  
*В коллекции Marg0sh создать "New Request" и переименовать его в "EP7"*  
*1. Выбрать метод Post, в поле "Enter request URL" вписать http://162.55.220.72:5005/user_info_2*  
*2. выбрать "Body" в нем "from-data"*  
*2.1. в столбец "KEY" добавить три строки с именами "name", "age" и "salary"*  
*2.2. в столбец "VALUE" добавить значения "Marg0sh", "34" и "50000" напротив ключей "name", "age" и "salary" соответственно*  
*3. нажать Save и Send* 

response:  
*ответ*  
```json
{
    "person": {"u_age": 34,
               "u_name": ["Marg0sh", 50000, 34],
               "u_salary_5_years": 210000.0},
    "qa_salary_after_1.5_year": 165000.0,
    "qa_salary_after_12_months": 135000.0,
    "qa_salary_after_3.5_years": 190000.0,
    "qa_salary_after_6_months": 100000,
    "start_qa_salary": 50000
}
```
  
*в поле "Enter request URL" URL не изменяется*  
  
  
  
=====

# HW_2 Postman  <a name="9"></a>

## (EP) http://162.55.220.72:5007/first   <a name="10"></a>
*Create new collection - New request  
метод GET  
в поле "Enter request URL" вписать http://162.55.220.72:5007/first и нажать Save*  

1. Отправить запрос.  
  
*Нажать Send*  
*ответ*  
```
This is the first responce from server!
```
2. Статус код 200  
  
*перейти в поле Tests  
выбрать из списка справа Status Code is 200  
в поле ввода кода тестов:*  
```javascript
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
```
*Save - Send  
во вкладке Test Results*  
```
PASS Status code is 200
```

3. Проверить, что в body приходит правильный string.  
  
*ответ в body*
```
This is the first responce from server!
```
*в поле ввода кода тестов:*  
```javascript
    pm.test("в body приходит правильный string", function () {
    pm.response.to.have.body("This is the first responce from server!");
});  
```
*Save - Send  
во вкладке Test Results*  
```
PASS в body приходит правильный string
```
  
  
## (EP2 из HW_1) http://162.55.220.72:5005/user_info_3 <a name="11"></a>
  
*Add request  
метод POST  
в поле "Enter request URL" вписать http://162.55.220.72:5005/user_info_3 и нажать Save*  
  
  
1. Отправить запрос.  
  
*нажать Send*  
  
  
2. Статус код 200  
  
*перейти в поле Tests  
выбрать из списка справа Status Code is 200  
в поле ввода кода тестов:*  
```javascript
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
```
*Save - Send  
во вкладке Test Results*  
```
PASS Status code is 200
```
  
  
3. Спарсить response body в json.  
  
*из списка справа выбрать Response body: JSON value check  
в окне редактирования тестов оставить код:*  
```javascript
let responseData = pm.response.json();  
console.log(responseData);
```
*Проверить содержимое переменной, выводя ее в Console:*  
```
{age: "34", family: {…}, name: "Marg0sh"…}
```
  
  
4. Проверить, что name в ответе равно name s request (name вбить руками.)  
  
*из списка справа выбрать Response body: JSON value check  
в окне редактирования тестов оставить код:*  
```javascript
pm.test("name в запросе равен name в ответе", function () {
    pm.expect(responseData.name).to.eql("Marg0sh");
});
```
*во вкладке Test Results*  
```
PASS name в запросе равен name в ответе
```
  
  
5. Проверить, что age в ответе равно age s request (age вбить руками.)  
  
*в окне редактирования тестов код:*  
```javascript
pm.test("age в запросе равен age в ответе", function () {
    pm.expect(responseData.age).to.eql("34");
});
```
*во вкладке Test Results*  
```
PASS age в запросе равен age в ответе
```
  
  
6. Проверить, что salary в ответе равно salary s request (salary вбить руками.)  
  
*в окне редактирования тестов код:*  
```javascript
pm.test("salary в запросе равен salary в ответе", function () {
    pm.expect(responseData.salary).to.eql(50000);
});
```
*во вкладке Test Results*  
```
PASS salary в запросе равен salary в ответе
```
  
  
7. Спарсить request.  
  
*в окне редактирования тестов код:*  
```javascript
let requestData = request.data;  
console.log('request data:', requestData);
```
*Save - Send*  
*проверить содержимое переменной, выводя ее в Console:*  
```
request data: {name: "Marg0sh", age: "34", salary: "50000"}
```
  
  
8. Проверить, что name в ответе равно name s request (name забрать из request.)  
  
*в окне редактирования тестов код:*  
```javascript
pm.test("значения name в ответе и в запросе совпадают", function () {
pm.expect(responseData.name).to.eql(requestData.name);  
});
```
*во вкладке Test Results*  
```
PASS значения name в ответе и в запросе совпадают
```
  
  
9. Проверить, что age в ответе равно age s request (age забрать из request.)  
  
*в окне редактирования тестов код:*  
```javascript
pm.test("значения age в ответе и в запросе совпадают", function () {
pm.expect(responseData.age).to.eql(requestData.age);  
});
```
*во вкладке Test Results*  
```
PASS значения age в ответе и в запросе совпадают
```
  
  
10. Проверить, что salary в ответе равно salary s request (salary забрать из request.)  
  
*в окне редактирования тестов код:*  
```javascript
pm.test("значения salary в ответе и в запросе совпадают", function () {
pm.expect(responseData.salary).to.eql(Number(requestData.salary));  
});
```
*во вкладке Test Results*  
```
PASS значения salary в ответе и в запросе совпадают
```
  
  
11. Вывести в консоль параметр family из response.  
  
*в окне редактирования тестов код:*  
```javascript
console.log('Family: ', responseDate.family)
```
*проверить содержимое переменной, выводя ее в Console:*  
```
Family: {children: [2], u_salary_1_5_year: 200000}
```
  
  
12. Проверить что u_salary_1_5_year в ответе равно salary*4 (salary забрать из request)  
  
*в окне редактирования тестов код:*  
```javascript
pm.test("u_salary_1_5_year в ответе равно salary*4", function () {  
pm.expect(responseData.family.u_salary_1_5_year).to.eql(requestData.salary*4);   
});  
```
*во вкладке Test Results*
```
PASS u_salary_1_5_year в ответе равно salary*4
```  
  
  
  
  
## (EP_5 из HW_1) http://162.55.220.72:5005/object_info_3  <a name="12"></a>
  
*Add request  
метод GET  
в поле "Enter request URL" вписать http://162.55.220.72:5005/object_info_3?name=Marg0sh&age=34&salary=50000 и нажать Save*  
  
  
1. Отправить запрос.  
  
*нажать Send*
  
  
2. Статус код 200  
  
*перейти в поле Tests  
выбрать из списка справа Status Code is 200*  
```javascript
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS Status code is 200
```
  
  
3. Спарсить response body в json.  
  
*в окне редактирования тестов код:*  
```javascript
let responseData = pm.response.json();
console.log('Response Data:', responseData)
```
*Save - Send  
в Console:*  
```
Response Data: {age: "34", family: {…}, name: "Marg0sh"…}
```
  
  
4. Спарсить request.  
  
*в окне редактирования тестов код:*  
```javascript
let requestData = pm.request.url.query.toObject()  
console.log('Request Data:', requestData);
```
*Save - Send  
в Console:*  
```
Request Data: {name: "Marg0sh", age: "34", salary: "50000"}
```
  
  
5. Проверить, что name в ответе равно name s request (name забрать из request.)  
  
*из списка справа выбрать Response body: JSON value check*  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("name в запросе равен name в ответе", function () {
    pm.expect(responseData.name).to.eql(requestData.name)
});
```
*во вкладке Test Results*  
```
PASS name в запросе равен name в ответе
```
  
  
6. Проверить, что age в ответе равно age s request (age забрать из request.)  
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("age в запросе равен age в ответе", function () {
    pm.expect(responseData.age).to.eql(requestData.age)
});
```
*во вкладке Test Results*  
```
PASS age в запросе равен age в ответе
```
  
  
7. Проверить, что salary в ответе равно salary s request (salary забрать из request.)  
  
*в окне редактирования тестов оставить код:*
```javascript
m.test("salary в запросе равен salary в ответе", function () {
    pm.expect(responseData.salary).to.eql(Number(requestData.salary))
});
```
*во вкладке Test Results*
```
PASS salary в запросе равен salary в ответе
```
  
  
8. Вывести в консоль параметр family из response.  
  
*в окне редактирования тестов оставить код:*
```javascript
console.log('Family: ', responseData.family)
```
*в Console:*  
```
Family: {children: [2], pets: {…}, u_salary_1_5_year: 200000}
```
  
  
9. Проверить, что у параметра dog есть параметры name.  
  
*в окне редактирования тестов оставить код:*
```javascript
pm.test("у параметра dog есть параметры name", function () {  
    pm.expect(responseData.family.pets.dog).to.haveOwnProperty('name');   
});
```
*во вкладке Test Results*  
```
PASS у параметра dog есть параметры name
```


10. Проверить, что у параметра dog есть параметры age.  
  
*в окне редактирования тестов оставить код:*
```javascript
pm.test("у параметра dog есть параметры age", function () {  
    pm.expect(responseData.family.pets.dog).to.haveOwnProperty('age');   
});
```
*во вкладке Test Results*  
```
PASS у параметра dog есть параметры age
```
  
  
11. Проверить, что параметр name имеет значение Luky.
  
*в окне редактирования тестов оставить код:*
```javascript
pm.test("параметр name имеет значение Luky", function () {
    pm.expect(responseData.family.pets.dog.name).to.eql('Luky')
});
```
*во вкладке Test Results*  
```
PASS параметр name имеет значение Luky
```
12. Проверить, что параметр age имеет значение 4.
  
*в окне редактирования тестов оставить код:*
```javascript
pm.test("параметр age имеет значение 4", function () {
    pm.expect(responseData.family.pets.dog.age).to.eql(4)
});
```
*во вкладке Test Results*  
```
PASS параметр age имеет значение 4
```
  
  
  
  
## (EP_6 из HW_1) http://162.55.220.72:5005/object_info_4  <a name="13"></a>
  
*Add request  
метод GET  
в поле "Enter request URL" вписать http://162.55.220.72:5005/object_info_4?name=Marg0sh&age=34&salary=50000 и нажать Save*  
  
  
1. Отправить запрос.  
  
*нажать Send*
  
  
2. Статус код 200  
  
*перейти в поле Tests  
выбрать из списка справа Status Code is 200*  
```javascript
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS Status code is 200
```
  
  
3. Спарсить response body в json.  
  
*в окне редактирования тестов оставить код:*
```javascript
let responseData = pm.response.json();
console.log ('Response Data', responseData)
```
*Save - Send  
в Console:*  
```
Response Data {age: 34, name: "Marg0sh", salary: [3]}
```
  
  
4. Спарсить request.
  
*в окне редактирования тестов оставить код:*
```javascript
let requestData = pm.request.url.query.toObject();
console.log ('Request Data', requestData)
```
*Save - Send  
в Console:*  
```
Request Data: {name: "Marg0sh", age: "34", salary: "50000"}
```
  
  
5. Проверить, что name в ответе равно name s request (name забрать из request.)
  
*в окне редактирования тестов оставить код:*
```javascript
pm.test("name в ответе равно name в request ", function () {
    pm.expect(responseData.name).to.eql(requestData.name)
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS name в ответе равно name в request
```
  
  
6. Проверить, что age в ответе равно age из request (age забрать из request.)
  
*в окне редактирования тестов оставить код:*
```javascript
pm.test("age в ответе равно age из request ", function () {
    pm.expect(responseData.age).to.eql(Number(requestData.age))
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS age в ответе равно age из request 
```
  
  
7. Вывести в консоль параметр salary из request.
  
*в окне редактирования тестов оставить код:*
```javascript
console.log(requestData.salary)
```
*Save - Send  
в Console:*  
```
50000
```
  
  
8. Вывести в консоль параметр salary из response.
  
*в окне редактирования тестов оставить код:*
```javascript
console.log(responseData.salary)
```
*Save - Send  
в Console:*  
```
(3) [50000, "100000", "150000"]
```
  
  
9. Вывести в консоль 0-й элемент параметра salary из response.
  
*в окне редактирования тестов оставить код:*
```javascript
console.log(responseData.salary[0])
```
*Save - Send  
в Console:*  
```
50000
```
  
  
10. Вывести в консоль 1-й элемент параметра salary параметр salary из response.
  
*в окне редактирования тестов оставить код:*
```javascript
console.log(responseData.salary[1])
```
*Save - Send  
в Console:*  
```
"100000"
```
  
  
11. Вывести в консоль 2-й элемент параметра salary параметр salary из response.
  
*в окне редактирования тестов оставить код:*
```javascript
console.log(responseData.salary[2])
```
*Save - Send  
в Console:*  
```
"150000"
```
  
  
12. Проверить, что 0-й элемент параметра salary равен salary из request (salary забрать из request.)
  
*в окне редактирования тестов оставить код:*
```javascript
pm.test("0-й элемент параметра salary равен salary из request ", function () {
    pm.expect(responseData.salary[0]).to.eql(Number(requestData.salary))
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS 0-й элемент параметра salary равен salary из request
```
  
  
13. Проверить, что 1-й элемент параметра salary равен salary*2 из request (salary забрать из request.)
  
*в окне редактирования тестов оставить код:*
```javascript
pm.test(" 1-й элемент параметра salary равен salary*2 из request ", function () {
    pm.expect(+responseData.salary[1]).to.eql(requestData.salary*2)
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS 1-й элемент параметра salary равен salary*2 из request
```
  
  
14. Проверить, что 2-й элемент параметра salary равен salary*3 из request (salary забрать из request.)
  
*в окне редактирования тестов оставить код:*
```javascript
pm.test("2-й элемент параметра salary равен salary*3 из request ", function () {
    pm.expect(+responseData.salary[2]).to.eql(requestData.salary*3)
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS 2-й элемент параметра salary равен salary*3 из request
```
  
  
15. Создать в окружении переменную name
  
*в меню слева выбирать Environment - New Environment - Marg0sh_HW2 
В строку Variable внести название переменной name, в Current value - Marg0sh*  
  
  
16. Создать в окружении переменную age
  
*в меню слева выбирать Environment - Marg0sh_HW2  
В строку Variable внести название переменной age, в Current value - 34*  
  
  
17. Создать в окружении переменную salary
  
*в меню слева выбирать Environment - Marg0sh_HW2   
В строку Variable внести название переменной salary, в Current value - 50000*  
  
  
18. Передать в окружение переменную name
  
*вернуться в коллекции, в EP_6 object_info_4, во вкладку Tests, прописать код:*  
```javascript
pm.environment.set('Name', responseData.name);
```
  
  
19. Передать в окружение переменную age  
  
*прописать код:*  
```javascript
pm.environment.set('Age', responseData.age);
```
  
  
20. Передать в окружение переменную salary  
  
*прописать код:*  
```javascript
pm.environment.set('Salary', responseData.salary[0]);
```
  
  
21. Написать цикл который выведет в консоль по порядку элементы списка из параметра salary.  
  
*прописать код:*  
```javascript
for (let i of responseData.salary) {  
console.log('элементы списка из параметра salary:',i);  
	}
```
*Save - Send  
в Console:*  
```
элементы списка из параметра salary: 50000
 
элементы списка из параметра salary: "100000"
 
элементы списка из параметра salary: "150000"
```




## (EP_7 из HW_1) http://162.55.220.72:5005/user_info_2  <a name="14"></a>
  
*Add request  
метод POST 
в поле "Enter request URL" вписать http://162.55.220.72:5005/user_info_2 и нажать Save*  
  
  
1. Вставить параметр salary из окружения в request  
  
*перейти во вкладку Body - from-data в столбце Value напротив 'salary' написать {{Salary}}*  
  
  
2. Вставить параметр age из окружения в age  
  
*в столбце Value напротив 'age' написать {{Age}}*  
  
  
3. Вставить параметр name из окружения в name  
  
*в столбце Value напротив 'name' написать {{Name}}*  
  
  
4. Отправить запрос.  
  
*Save - Send*  
  
  
5. Статус код 200  
  
*перейти во вкладку Tests, в окне редактирования тестов оставить код:*  
```javascript
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS Status code is 200
```
  
  
6. Спарсить response body в json.  
  
*в окне редактирования тестов оставить код:*  
```javascript
let responseData = pm.response.json();
console.log ('Response Data', responseData)
```
*в Console*
```
Response Data {person: {…}, qa_salary_after_1.5_year: 165000, qa_salary_after_12_months: 135000…}
```
  
  
7. Спарсить request.  
  
*в окне редактирования тестов оставить код:*    
```javascript
let requestData = request.data
console.log ('Request Data', requestData)
```
*в Console*
```
Request Data {name: "Marg0sh", age: "34", salary: "50000"}
```
  
  
8. Проверить, что json response имеет параметр start_qa_salary    
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("json response имеет параметр start_qa_salary", function () {  
    pm.expect(responseData).to.haveOwnProperty('start_qa_salary');   
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS json response имеет параметр start_qa_salary
```
  
  
9. Проверить, что json response имеет параметр qa_salary_after_6_months    
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("json response имеет параметр qa_salary_after_6_months", function () {  
    pm.expect(responseData).to.haveOwnProperty('qa_salary_after_6_months');   
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS json response имеет параметр qa_salary_after_6_months
```
  
  
10. Проверить, что json response имеет параметр qa_salary_after_12_months    
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("json response имеет параметр qa_salary_after_12_months", function () {  
    pm.expect(responseData).to.haveOwnProperty('qa_salary_after_12_months');   
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS json response имеет параметр qa_salary_after_12_months
```
  
  
11. Проверить, что json response имеет параметр qa_salary_after_1.5_year    
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("json response имеет параметр qa_salary_after_1.5_year", function () {  
    pm.expect(responseData).to.haveOwnProperty('qa_salary_after_1.5_year');   
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS json response имеет параметр qa_salary_after_1.5_year
```
  
  
12. Проверить, что json response имеет параметр qa_salary_after_3.5_years    
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("json response имеет параметр qa_salary_after_3.5_years", function () {  
    pm.expect(responseData).to.haveOwnProperty('qa_salary_after_3.5_years');   
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS json response имеет параметр qa_salary_after_3.5_years
```
  
  
13. Проверить, что json response имеет параметр person    
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("json response имеет параметр person", function () {  
    pm.expect(responseData).to.haveOwnProperty('person');   
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS json response имеет параметр person
```
  
  
14. Проверить, что параметр start_qa_salary равен salary из request (salary забрать из request.)    
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("параметр start_qa_salary равен salary из request", function () {
    pm.expect(responseData.start_qa_salary).to.eql(requestData.Salary)
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS параметр start_qa_salary равен salary из request
```
  
  
15. Проверить, что параметр qa_salary_after_6_months равен salary*2 из request (salary забрать из request.)  
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("параметр qa_salary_after_6_months равен salary*2 из request", function () {
    pm.expect(responseData.qa_salary_after_6_months).to.eql(requestData.salary*2)
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS параметр qa_salary_after_6_months равен salary*2 из request
```
  
  
16. Проверить, что параметр qa_salary_after_12_months равен salary*2.7 из request (salary забрать из request.)    
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("параметр qa_salary_after_12_months равен salary*2.7 из request", function () {
    pm.expect(responseData.qa_salary_after_12_months).to.eql(requestData.salary*2.7)
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS параметр qa_salary_after_12_months равен salary*2.7 из request
```
  
  
17. Проверить, что параметр qa_salary_after_1.5_year равен salary*3.3 из request (salary забрать из request.)  
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("параметр qa_salary_after_1.5_year равен salary*3.3 из request", function () {
    pm.expect(responseData['qa_salary_after_1.5_year']).to.eql(requestData.salary*3.3)
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS параметр qa_salary_after_1.5_year равен salary*3.3 из request
```
  
  
18. Проверить, что параметр qa_salary_after_3.5_years равен salary*3.8 из request (salary забрать из request.)  
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("параметр qa_salary_after_3.5_years равен salary*3.8 из request", function () {
    pm.expect(responseData['qa_salary_after_3.5_years']).to.eql(requestData.salary*3.8)
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS параметр qa_salary_after_3.5_years равен salary*3.8 из request
```
  
  
19. Проверить, что в параметре person, 1-й элемент из u_name равен salary из request (salary забрать из request.)  
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("параметре person, 1-й элемент из u_name равен salary из request", function () {
    pm.expect(responseData.person.u_name[1]).to.eql(Number(requestData.salary))
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS параметре person, 1-й элемент из u_name равен salary из request
```
  
  
20. Проверить, что что параметр u_age равен age из request (age забрать из request.)  
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("параметр u_age равен age из request", function () {
    pm.expect(responseData.person.u_age).to.eql(Number(requestData.age))
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS параметр u_age равен age из request
```
  
  
21. Проверить, что параметр u_salary_5_years равен salary*4.2 из request (salary забрать из request.)  
  
*в окне редактирования тестов оставить код:*  
```javascript
pm.test("параметр u_salary_5_years равен salary*4.2 из request", function () {
    pm.expect(responseData.person.u_salary_5_years).to.eql(requestData.salary*4.2)
});
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS параметр u_salary_5_years равен salary*4.2 из request
```
  
   
22. ***Написать цикл который выведет в консоль по порядку элементы списка из параметра person.  
  
*в окне редактирования тестов оставить код:*   
```javascript
for (let i in responseData.person) {  
console.log('элементы списка из параметра person:',i);  
	}
```
*в Console*  
```
элементы списка из параметра person: u_age
элементы списка из параметра person: u_name
элементы списка из параметра person: u_salary_5_years
```
  
  
-----
  
## HW_2* Postman <a name="15"></a>  
  
## EP_7 /user_info_2 <a name="16"></a>   
1. (ОБЯЗАТЕЛЬНОЕ И ВАЖНЕЙШЕЕ ЗАДАНИЕ) http://162.55.220.72:5005/user_info_2
Необходимо провести тестирование API данного эндпоинта на валидацию входных параметров. Суть задания: проверить валидации каждого поля, подаваемого в эндпоинт на возможные значения. Будем УСЛОВНО считать, что негативная проверка должна возвращать какой угодно статус НО НЕ 200! Ваша задача написать тест кейсы в постмане таким образом, что одна негативная проверка - один запрос, позитивные проверки можно объединять в 1. Ваша задача протестировать исходя из требований на все возможные аспекты. В каждом запросе тест ТОЛЬКО НА СТАТУС КОД (200 - позитивное значение, не 200 - негативное).   
P.S. ЗАДАНИЕ НЕ ПОДРАЗУМЕВАЕТ, ЧТО ЭНДПОИНТ РАБОТАЕТ СОГЛАСНО НАПИСАННЫМ ТРЕБОВАНИЯМ. МЫ УЧИМСЯ ПИСАТЬ ТЕСТЫ НА API!  
Требования:  
1) Name: 3-40 символов включительно, запрещены префиксные и постфиксные пробелы. Поле обязательное  
2) Age: только целые цифры в диапазоне 18-120 включительно. Поле обязательное  
3) Salary: только целые цифры в диапазоне 1-1000000 включительно. Поле обязательное  
  
1****. Преобразовать задание 1 таким образом, чтобы вы отправляли параметры через CSV файл. У вас будет ровно 1 запрос в коллекции, который будет повторяться столько раз, сколько строк в CSV файле. Также должна быть написана функция в тестах, которая проверяет валидность входящих данных, и в зависимости от этого проверяет на статус 200 или НЕ 200.  
  
  
## 2.EP_6 /object_info_4 <a name="17"></a>  
http://162.55.220.72:5007/object_info_4  
Преобразовать пункты 12-13-14 (salary из реквеста и респонса равны) таким образом, чтобы проверка производилась циклом, в котором будет всего ОДИН тест. Имя теста должно меняться в зависимости от значения в Salary.    
  
*12. Проверить, что 0-й элемент параметра salary равен salary из request (salary из request.)*  
*13. Проверить, что 1-й элемент параметра salary равен salary*2 из request (salary из request.)*    
*14. Проверить, что 2-й элемент параметра salary равен salary*3 из request (salary из request.)*  
  
```javascript
let reqSal = pm.request.url.query.get('salary')
let respSal = pm.response.json().salary

for(let i = 0; i <= respSal.length-1; i++){
    pm.test(`Request salary ${reqSal} *${i+1} == response salary ${respSal[i]}`, function(){
        pm.expect(+reqSal*(i+1)).to.eql(+respSal[i])
        // console.log('reqSal*(i+1): ', reqSal*(i+1))
    })
}
```
*или*  
```javascript
respSal.forEach((element, i) =>{
    pm.test(`Request salary ${reqSal} *${i+1} == response salary ${element}}}`, function(){
        pm.expect(+reqSal*(i+1)).to.eql(+element)
    })
})
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS Request salary 50000 *1 == response salary 50000
PASS Request salary 50000 *2 == response salary 100000
PASS Request salary 50000 *3 == response salary 150000
```
  
## 3. EP_5 /object_info_3 <a name="18"></a>  
http://162.55.220.72:5005/object_info_3  
Преобразовать задания 5-7 (сравнить идентичные поля в реквесте и респонсе) таким образом, чтобы это делалось ЗА ОДИН ТЕСТ (сразу все 3 поля) БЕЗ ЦИКЛОВ! (глубокое сравнение объектов).  
  
*5. Проверить, что name в ответе равно name s request (name забрать из request.)*  
*6. Проверить, что age в ответе равно age s request (age забрать из request.)*  
*7. Проверить, что salary в ответе равно salary s request (salary забрать из request.)*  
  
```javascript
let reqSal = +pm.request.url.query.get('salary')
let reqName = pm.request.url.query.get('name')
let reqAge = +pm.request.url.query.get('age')
// console.log (reqSal)
// console.log (reqName)
// console.log (reqAge)

const reqObj ={
    name : reqName,
    age : reqAge,
    salary : reqSal
}
// console.log (reqObj)

let respSal = +pm.response.json().salary
let respAge = +pm.response.json().age
let respName = pm.response.json().name

const respObj ={
    name : respName,
    age : respAge,
    salary : respSal
}
// console.log (respObj)

pm.test('RespObj == ReqObj', function(){
    pm.expect(reqObj).to.deep.eql(respObj)
})
```
*или*   
```javascript
let reqSal = +pm.request.url.query.get('salary')
let reqName = pm.request.url.query.get('name')
let reqAge = +pm.request.url.query.get('age')

const reqObj ={
    name : reqName,
    age : reqAge,
    salary : reqSal
}

const respObj = {}
for (const key in reqObj){
    if(!isNaN(pm.response.json()[key])){
        respObj[key] = +pm.response.json()[key]
    }else
        respObj[key] = pm.response.json()[key]
    }

pm.test('RespObj == ReqObj', function(){
    pm.expect(reqObj).to.deep.eql(respObj)
})
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS RespObj == ReqObj
```
   
## 4. EP_7 /user_info_2 <a name="19"></a>  
http://162.55.220.72:5005/user_info_2  
1)  Преобразовать задания 8 - 13 (проверить что в json имеется нужный параметр) таким образом, чтобы все проверки делались в цикле (1 проверка в цикле, в которую попадают нужные параметры). Название теста должно видоизменяться исходя из подаваемых данных. ( ${}  или другим способом)  
  
*8. Проверить, что json response имеет параметр start_qa_salary*  
*9. Проверить, что json response имеет параметр qa_salary_after_6_months*  
*10. Проверить, что json response имеет параметр qa_salary_after_12_months*  
*11. Проверить, что json response имеет параметр qa_salary_after_1.5_year*  
*12. Проверить, что json response имеет параметр qa_salary_after_3.5_years*  
*13. Проверить, что json response имеет параметр person*  
  
```javascript
let arr = []
const resp = pm.response.json()

for(const key in resp){
    arr.push(key)
}
console.log(arr)
```
*в Console:*  
```
(6):
0: "person"
1: "qa_salary_after_1.5_year"
2: "qa_salary_after_12_months"
3: "qa_salary_after_3.5_years"
4: "qa_salary_after_6_months"
5: "start_qa_salary"
```
*в поле кода:*  
```javascript
arr.forEach((element) => {
    pm.test(`Response has a ${element}`, function(){
        pm.expect(resp).to.have.property(element)
    })
})
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS Response has a person
PASS Response has a qa_salary_after_1.5_year
PASS Response has a qa_salary_after_12_months
PASS Response has a qa_salary_after_3.5_years
PASS Response has a qa_salary_after_6_months
PASS Response has a start_qa_salary
```
  
2) ** Преобразовать задания 14 - 18 (проверить что параметр равен salary умножить на коэффициент) таким образом, чтобы все проверки делались в цикле (1 проверка в цикле, в которую попадают нужные параметры). Название теста должно видоизменяться исходя из подаваемых данных. ( ${}  или другим способом)  
  
*14. Проверить, что параметр start_qa_salary равен salary из request (salary забрать из request.)*  
*15. Проверить, что параметр qa_salary_after_6_months равен salary * 2 из request (salary забрать из request.)*  
*16. Проверить, что параметр qa_salary_after_12_months равен salary * 2.7 из request (salary забрать из request.)*  
*17. Проверить, что параметр qa_salary_after_1.5_year равен salary * 3.3 из request (salary забрать из request.)*  
*18. Проверить, что параметр qa_salary_after_3.5_years равен salary * 3.8 из request (salary забрать из request.)*  
  
```javascript
let arr = []
const resp = pm.response.json()

for(const key in resp){
    arr.push(key)
}

const count = [
    '',
    3.3,
    2.7,
    3.8,
    2,
    1
]

arr.forEach((element, i) => {
    if (element !=='person') {
    pm.test(`Response_has_a ${element}`, function(){
        pm.expect(+resp[element]).to.eql(50000*count[i])
    })}
})
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS Response_has_a qa_salary_after_1.5_year
PASS Response_has_a qa_salary_after_12_months
PASS Response_has_a qa_salary_after_3.5_years
PASS Response_has_a qa_salary_after_6_months
PASS Response_has_a start_qa_salary
```
   
3) *** Преобразовать описанные выше задания 1 и 2 для данного эндпоинта в ОДИН ЦИКЛ, в котором будут проходить ОБА теста.  
  
```javascript
let arr = []
const resp = pm.response.json()
const salary = 50000

const counters = {
    'person': '',
    'start_qa_salary': 1,
    'qa_salary_after_6_months': 2,
    'qa_salary_after_12_months': 2.7,
    'qa_salary_after_1.5_year': 3.3,
    'qa_salary_after_3.5_years': 3.8
}

for (const key in counters){
    pm.test(`Response_Has_ ${key}`, () =>{
        pm.expect(resp).to.have.property(key)
    })
    if (key !== 'person'){
        pm.test(`${key} = ${salary} * ${counters[key]}`, () =>{
        pm.expect(resp[key]).to.eql(counters[key]*salary)
    })
    }
}
```
*Save - Send*  
*во вкладке Test Results*  
```
PASS Response_Has_ person
PASS Response_Has_ start_qa_salary
PASS start_qa_salary = 50000 * 1
PASS Response_Has_ qa_salary_after_6_months
PASS qa_salary_after_6_months = 50000 * 2
PASS Response_Has_ qa_salary_after_12_months
PASS qa_salary_after_12_months = 50000 * 2.7
PASS Response_Has_ qa_salary_after_1.5_year
PASS qa_salary_after_1.5_year = 50000 * 3.3
PASS Response_Has_ qa_salary_after_3.5_years
PASS qa_salary_after_3.5_years = 50000 * 3.8
```
  
