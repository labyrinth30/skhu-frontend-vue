&& || 연산자가 포함된 표현식에서, 실행할 필요가 없는 부분을 실행하지 않는 것을 lazy evaluation 이라고 한다. 

C, Java, Javascript 등 대부분의 언어는 lazy evalution 한다.  
|| 연산자 (OR 연산자)  
&& 연산자 (&& 연산자)  

표현식1 || 표현식2  
표현식1 값이 true 이면, 결과는 true 이다. 이때 표현식2는 실행되지 않는다.  
표현식1 값이 false 이면, 결과는 표현식2의 값이다. 이때는 당연히 표현식2가 실행된다.  

표현식1 && 표현식2  
표현식1 값이 flase 이면, 결과는 false 이다. 이때 표현식2는 실행되지 않는다.  
표현식1 값이 true 이면, 결과는 표현식2의 값이다. 이때는 당연히 표현식2가 실행된다.  
