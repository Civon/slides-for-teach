{{{   
  
# Coding Style  (Clean Code)

- naming variable
- fortmat aligan
- variable case
- easy to understand
- comment & doc 
- use tools as well
- do not afraid debug, enjoy it!

---     
##   Why Clean Code 
	“
	      程式碼寫給誰看？ 
	   			” 

---   

<div style="font-size:1.5em;">
    <h1>人</h1>
</div>	

}}}  
   \
{{{  

##  變數命名    
  
```java  
// bad  
String a = "Hello";  
for (i = 0; i < 3; i++ ){  
	for (j = 0; j < 3; j++){  
		//	do something  
	}  
}    
  
// good  
String greet ç= "Hello";    
for (row = 0; row < 3; row++ ){  
	for (column = 0; column < 3; column++){  
		//	do something  
	}  
}     
```  
abbr. r => row	or  c => column   is acceptable     
	

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