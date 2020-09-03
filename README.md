# JS Style Guide


### 1. ����� � �������
>����� � ������� ������ �������������� ����� ������� ���������, ���� ���� ��, �������� ��, ����� ����������.

```javascript
// �����
alert('������') 

// ������
alert('���');
```

### 2. �����������
>�� �������� ��������� ���������� �� ������� � �������. ��������� ������������� ��������� �����������, ������� �� ���������, ��� ������ ��� � ������. 
������������ ����������� ���������� � ������� ����� ����� // 
������������� ����������� ���������� ����� ������ �� ��������� /* � ������������� ��������� � ����� ������ */. 

```javascript
// �����
alert('���'); /* ���� ����������� ������� �� ����������� */

// ������ � ����� �����������. 
��� - ������������� �����������.
alert('������'); 

// ������
alert('���');// ���� ����������� ������� �� ����������� 

/* ������ � ����� �����������. 
��� - ������������� �����������. */ 
alert('������'); 
```

### 3. ����������� �������� ����� ���������� � �������
>��� ������� ����� ������, ����� ��� ��� ��������� ���������� ��������, ������������ ����� ������� � ����������. 

```javascript
// �����
function avg (a) {
	let s = a.reduce((x, y) => x + y)
	return s / a.length
}

// ������
function averageArray (array) {
	let sum = array.reduce((number, currentSum) => number + currentSum)
	return sum / array.length
}
```

### 4. ������������ ���������� � �������
>����������� Camel case (���������� �������) ��� ��������� ���� ���������� � �������.

```javascript
// �����
examplefunctionname

// ������
exampleFunctionName
```

### 5.���������� ����������
>������ var ����������� const � ���� ��������� ����������, ��� let � ���� ���������� ���������� ��������������.

```javascript
// �����
var a = '������';
var b = 1;

// ������
let a = '������';
const = 2;
```

### 6. �������������� ������
>��� ���������� ���������� ���� ����������� ������������� ������

```javascript
// �����
const users = [
{ name: "Bob", id: 1 },
{ name: "Jane", id: 2 },
{ name: "Fred", id: 3 }
];
const usernames = [];

// ������
const users = [
        { name: "Bob", id: 1 },
        { name: "Jane", id: 2 },
        { name: "Fred", id: 3 }
    ];
const usernames = [];
```

### 7. ������� ���������
>������������� �������� ��������� == ����� ������� ��������. �������� �������� ��������� === ��������� ��������� ��� ���������� �����.

```javascript
// �����
alert( 0 == false ); // true 

// ������
alert( 0 === false ); // false, ��� ��� ������������ ������ ���� 
```

### 8. ����� ����
>����������� �������� ������ ��� ����, ����������� ����� ����� ������


```javascript
// �����
function sum() 
	return false;

// ������
function sum() {
	return false;
}
```

### 9.�������
>��� �������� ������� ����������� ����������� �������
 
```javascript
// �����
const user = new Object();

// ������
const user = {};
```

### 10. ���������� �������
>��������� ������������ ���������� ��������, ��� �������  ��������� ����������

```javascript
// �����
[1, 2, 3].map(function (x) {
  const y = x + 1;
  return x * y;
});

// ������
[1, 2, 3].map((x) => {
  const y = x + 1;
  return x * y;
});
```
---


 