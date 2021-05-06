# 상대 주소
현재 열려있는 html의 위치를 기준으로 상대적인 컨텐츠의 위치를 지정
현재위치는 ‘.’, 상위 폴더의 위치는 ‘..’, 그리고 폴더의 구분은 ‘/’으로 한다.

html의 현재 위치가 C:\test 라면, 실제로 접근하는 주소는 다음과 같다.
>./images/img.jpg
>>c:/test/images/img.jpg

>../images/img.jpg
>>c:/images/img.jpg

# target
a태그에는 열리는 링크시킨 웹사이트를 어디서 열리게 할 것인지 정하는 target이라는 속성이 존재한다.

>target = "test"
>><iframe name="test"> test라는 name속성 값을 가지는 iframe에서 창이 열린다.

>target = "_top"
>>html 문서의 최상위창에서 열린다. (프레임 무시)

>target = "_parent"
>>클릭한 문서창의 부모의 관계를 가지고 있는 페이지에서 열린다.

>target = "_self"
>>디폴트 값이며, 클릭한 문서창에서 열린다.

>target = "_blank"
>>가장 자주 사용되는 값이며, 새로운 창에서 문서를 연다.

