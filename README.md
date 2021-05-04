# 상대 주소
현재 열려있는 html의 위치를 기준으로 상대적인 컨텐츠의 위치를 지정
현재위치는 ‘.’, 상위 폴더의 위치는 ‘..’, 그리고 폴더의 구분은 ‘/’으로 한다.

html의 현재 위치가 C:\test 라면, 실제로 접근하는 주소는 다음과 같다.
>./images/img.jpg
>>c:/test/images/img.jpg

>../images/img.jpg
>>c:/images/img.jpg
