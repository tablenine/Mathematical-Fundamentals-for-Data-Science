### 2. Linear Algebra(I)

#### 2-1 Basics Elements of Linear Algebra

+ 행렬의 곱은 결합 법칙이 성립하지 않음
+ 행렬의 몇가지 속성
  + A(B+C) = AB + AC
  + A(BC) = (AB)C
  + (AB)<sup>T</sup> = B<sup>T</sup>A<sup>T</sup>
+ Linear Equation
  + a<sub>1</sub>x<sub>1</sub> + a<sub>2</sub>x<sub>2</sub> + ... a<sub>n</sub>x<sub>n</sub> = b
  + a<sub>1</sub> ... a<sub>n</sub>, b는 알려진 숫자 x<sub>1</sub>...x<sub>n</sub>은 알려지지 않은 숫자
  + Ax = b => x = A<sub>-1</sub>b
  + A가 역변환이 되지 않는 경우는 solution이 없거나 매우 많은 솔루션이 존재하며 고유 솔루션은 없다.
+ Rectangular Matrix A in Ax = b
  + 행 < 열 :
    +  방정식보다 많은 변수를 가지고 있으며 
    + 자유롭게 선택할 수 있는 많은 변수를 가짐 
    + 무한히 많은 방정식의 솔루션을 가짐
    + 불확실한 시스템 (under-determined system)
  + 행 > 열 :
    + 변수보다 많은 방정식을 가지고 있으며 
    + 솔루션이 전혀 없다.
    + over-determined system

