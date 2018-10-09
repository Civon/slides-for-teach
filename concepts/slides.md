{{{
  
# Coding Style  

## ( Clean Code )  

---  

- naming variable
- fortmat align
- variable case
- easy to understand
- comment & doc  
- use tools as well  
- don't afraid debug, enjoy it!

---  

## Why Clean Code  

<div style = "text-align: center; margin-top: 1em">
  “
        程式碼寫給誰看？  
           ”  
</div>  

---  

<div style="font-size:1.5em;">
    <h1>人</h1>
</div>  
  
---  

增進理解，養成好習慣  
  
<!-- the vote chart of hardest thing in coding  put last? -->  
  
}}}  

{{{  

## 命名東西  
  
永遠是最難的部分  
  
---  
  
![bl](./black-quation.jpg)  

---  

``` java  

// bad  
String a = "Hello";  
for (i = 0; i < 3; i++ ){  
  for (j = 0; j < 3; j++){  
    // do something  
  }  
}  
  
// good  
String greet = "Hello";  
for (row = 0; row < 3; row++ ){  
  for (column = 0; column < 3; column++){
        // do something  
  }  
}  

```  

}}}  
  
{{{  
  
## 格式對齊  

}}}  
  
{{{  

不要變魔術

```js
// swap foo & bar
foo = 2;
bar = 3;

// bad
foo ^= bar ^= foo ^= bar ;  

// good enough
temp = foo;
foo = bar;
bar = temp;  

```

}}}  
