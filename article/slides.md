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
- do not afraid debug, enjoy it!

---     
##   Why Clean Code 
<div style = "text-align: center; margin-top: 1em">
	“
	      程式碼寫給誰看？ 
	   			” 
</div>  

---   

<div style="font-size:1.5em;">
    <h1>人</h1>
</div>	
  
<!-- the vote chart of hardest thing in coding   -->

}}}  
  
{{{  
  
## 變數命名
  
---  
永遠是最難的部分  
fragment   
黑人問號圖  

---   

```java  
//	bad  
String a = "Hello";  
for (i = 0; i < 3; i++ ){  
	for (j = 0; j < 3; j++){  
		//	do something  
	}  
}  
  
//	good  
String greet = "Hello";  
for (row = 0; row < 3; row++ ){  
	for (column = 0; column < 3; column++){  
		//	do something  
	}  
}  
```  


}}}   
  
{{{    



不要變魔術

```js
// this is a swap
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