[[Literal]]

`Объект или Экземпляр` - структура данных, содержащая состояние и методы, связанные с этим состоянием.
`Объект` может быть создан как литерал `{}` или экземпляр класса `new ClassName()` или как экземпляр прототипа `new Constructor()` или возвращен из фабрики.
```js
const person = {
  name: 'Marcus',
  city: 'Roma',
  born: 121,
};

const person = new Person('Marcus', 'Roma', 121);
```
