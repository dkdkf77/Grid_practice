# grid_practice

콜로소 디자이너를 위한 코딩 : 가변 그리드(유체 그리드)에 대한 공부

# grid_practice.html 과 grid_practice.css 를 참고

### 유체 그리드란?

    	- 브라우저의 크기에 따라 레이어 등이 깨지지 않고 자연스럽게 정렬 되는 것
    	- 고정 레이아웃을 쓰면 width에 따라 값이 고정이 되고 유체 그리드가 되지 않는다
    	- 가변 그리드를 사용하면 각 종 기기에 적용이 가능하다

### 가변 그리드 웹 만들기

    	- 처음에는 header와 content 그리고 foot으로 나눠서 진행 한다.
    	- 다 완료 하면 css를 입혀 준다
    	- calc()를 쓰면 쉽게 너비 등을 계산 가능하다
    	- ⭐️ rem에 calc() 함수를 사용하는 방법 = font-size : calc(24/16 * 1rem)

    	- rem은 고정 값이라서 창 크기가 커진다고 폰트 사이즈가 같이 커지고 작아지고 하지는 않는다 그럴때는 5vw 을 쓰면 된다.
    	- 브라우저의 변화에 따라 폰트 폭도 변하게 된다/
    	- 100vw가 브라우저 폭 100%

    	(title) font-size : 5vw 동영상
   ![Hnet com-image (5)](https://user-images.githubusercontent.com/88579497/140596088-f3db2701-c2cf-4829-bbc2-bc168bf1a506.gif)
