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