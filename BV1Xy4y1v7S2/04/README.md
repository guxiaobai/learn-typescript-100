# 04_TS中类型（2）

|本期版本|上期版本
|:---:|:---:
`Sat Jul  1 15:29:04 CST 2023` | 

**object**

> [Optional Properties](https://www.typescriptlang.org/docs/handbook/2/objects.html#optional-properties), 可选属性


```typescript
let b: {name: string, age?: number}
```

> [Index Signatures](https://www.typescriptlang.org/docs/handbook/2/objects.html#index-signatures)， 索引签名

```typescript
let c: {name:string, [propName: string]: any}

```

**Function**


```typescript
let d:(a:number, b:number) =>number;
```


**数组**

```typescript
let e:string[];
let e:Array<number>
```

**元组, 固定长度的数组**

```typescript
let h: [string, string ]
```

**枚举**

```typescript
enum Gender {
	Male,
	Female
}

let gender: Gender
```


```typescript
{name:string} & {age: number}
```

**类型别名**

```
type myType = string
type myType = 1 | 2 | 3
```