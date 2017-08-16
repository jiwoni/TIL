> ## 알고리즘 
>
>
> ```markdown
>
> #컴퓨터 알고리즘 정의 : 효율적으로, 단계적으로 문제를 해결하는 방법
> keyword: 효율성, 단계적, 문제, 해결방법
> 							
> 								
> #컴퓨터 알고리즘을 설명하기 위한 4단계
>
> -문제 정의: ex) 해결하고자 하는 문제는 무엇인가? 
> -알고리즘 설명: 컴퓨터가 수행해야 할 내용은 하나씩 차례대로 정의한 과정
> -정확성 증명: ex)과정대로 수행하면 출력으로 항상 올바른 답을 내보내는가? , 잘못된 답을 내보내는 경우는 없는가? , 올바른 출력을 내보내고 정상적으로 죵료되는가?
> -성능 분석: 수행시간(Running time), 사용공간(Space consumption)
>
> ##알고리즘 수행시간 분석
> -수행연산의 횟수를 비교하는 방식으로 성능을 분석
>
> ex) 10번 고정(연산 횟수 동일): 공정한 비교
>     android 10s => 1s * 10번 
>     pc 1s => 0.1s * 10번 
>     server 0.1s => 0.01s * 10번
> 좋은 알고리즘은 연산의 횟수를 줄이는 것
>
> ###성능 분석의 비교 대상
> -산술 연산(Arithmetic Calculation) : Add, Multiply, Exponent, Modular...
> -데이터 입출력 (Data Movement) : Copy, Move, Sava, Load...
> -제어 연산(Access Control): if, while, Register....
					
> ```


- 점근적 표기법(Asymptotic notation)
 
     $
     O-notation(빅오 표기): 
     $

<img src="images/bigo-notation.PNG" alt="" />

![Alt text](images/bigo-notation.PNG)

     $
     \Omega-notation(오메가 표기)\\
     $
     
     $
     \Theta-notation(쎄타 표기)\\
     $