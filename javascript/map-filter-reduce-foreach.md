# mapやfilterなどのメモ

## 参考文献
https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference/Global_Objects/Arra://developer.mozilla.org/ja/docs/Web/JavaScript/Reference/Global_Objects/Array

## これらは何？
Arrayオブジェクトに実装されているメソッド。  
Arrayの特定の値を探索したい場合に楽になる。  

## map
配列内のすべての要素に対して与えられた関数を呼び出し、その結果を格納した新しい配列を生成する。  
写像。  
  
arrayは元の配列。  
index, arrayは省略可能。  

```javascript

var square = [1, 2, 3, 4, 5].map(function(element, index, array) {
  return element * element;
});

// [1, 4, 9, 16, 25] が出力される。
console.log(square);

```

## filter
指定したフィルタリング関数が true を返す、配列中の要素を格納した新しい配列を生成。  
条件に合うものを抽出する。  

arrayは元の配列。  
index,arrayは省略可能。  

```javascript

var filtered = [5, 10, 229, 41, 78].filter(function(element, index, array) {
  return (element >= 50);
});

// [229, 78] が出力される。
console.log(filtered);

```

## reduce
アキュムレータと配列内のすべての要素に対して (左から右の順で) 関数を適用し、単一の値に還元します。  

```javascript



```

## forEach
配列中のそれぞれの要素について関数を呼び出します。  

```javascript



```