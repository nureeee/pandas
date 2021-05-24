수업내용 정리

# 210518 수업 내용 정리

2**8    256                     1byte
2**16   65536                   2byte	
2**32	  4294967296              4byte
2**64   18446744073709551616	   8byte


numpy는 연속적인 배열을 사용하여 파이썬보다 빠르게 실행할 수 있다.

np1.nbytes   ## 전체 바이트
np1.itemsize  ##하나하나의 바이트 
np2.T  ## 행과 열의 구조를 바꿈
 eg. np13 = np.array([2, 4, 5], dtype = 'uint')  ## 데이터를 저장할  음의 부분을 양의 부분에 추가하여 생각
 
 
 ##210521 수업내용 정리
 
 scalar 3       

vector [2, 3, 4] + 5
  [2, 3, 4] + [5, 5, 5]

matrix [ [1, 2], [3, 4] ]

tensor [ [[1,2], [3,4]], [[5,6],[7,8]] ]

n-tensor

정규표현식  
처음 ^   : ^a, ^ac
끝  $  : exe$
0번 이상 중복 * : ab*,   괴랄하다  like '이%'    
한 문자 와일드카드 _ : a_b, a__b,   
 
$ls a*
$ls  ^ap*
 


 
join : 여러 테이블에서 필요한 내용만 추출 
merge : 합친다. - 병합


