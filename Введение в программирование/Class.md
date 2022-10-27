[[Method]]
[[Object (Instance)]]

`Класс` -  программная `абстракция`, объединяющая состояние и поведение (`свойства` и `методы`) своих экземпляров (`инстансов`). 

```js
class Point {
  constructor(x, y) {
    this.x = x;
    this.y = y;
  }

  static from(point) {
    return new Point(point.x, point.y);
  }
}
```

```js
class Rect {
  move(x, y) {
    this.x += x;
    this.y += y;
  }
}

class Square extends Rect {
  constructor(x, y, m) {
    super(x, y, m, m);
  }
}
```