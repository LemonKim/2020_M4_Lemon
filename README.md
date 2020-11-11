---
Date 11/11

## 2020_M4_레몬 

## 인터넷은 어떻게 동작하는가

1. 사용자가 웹 브라우저를 통해 찾고 싶은 웹 페이지를 검색한다.
2. 사용자가 입력한 주소를 DNS에서 IP로 바꾼다. 
3. 웹 페이지 정보와 전달받은 IP 주소를 찾아 사용자가 입력한 정보와 함께 전달한다.
4. 웹 페이지 정보와 전달받은 IP 주소는 HTTP 프로토콜을 사용하여 HTTP 리퀘스트를 생성한다.
5. 위와 같은 과정으로 만들어진 리퀘스트는 TCP 프로토콜을 사용하여 인터넷을 거쳐 해당 IP 주소의 컴퓨터로 전송된다.
6. 이렇게 도착한 HTTP 요청 메세지는 HTTP 프로토콜을 사용해 웹페이지 정보로 변환된다.
7. 웹 서버에 도착한 정보에 해당하는 데이터를 검색한다.
8. 검색된 웹 페이지 데이터는 다시 HTTP 프로토콜을 사용하여 HTTP 리시브(응답 메세지)를 생성한다.
9. 이렇게 생성된 HTTP 리시브는 TCP 프로토콜을 사용해, 인터넷을 거쳐 윈래 컴퓨터로 전송된다. 
10. 도착한 HTTP 리시브는 HTTP 프로토콜을 사용해 웹 페이지 데이터로 변환된다.
11. 변환된 웹 페이지 데이터는 웹 브라우저에 의해 출력되어 사용자가 볼 수 있게 된다.

- __[프로토콜](https://ko.wikipedia.org/wiki/%ED%86%B5%EC%8B%A0_%ED%94%84%EB%A1%9C%ED%86%A0%EC%BD%9C)__ -  컴퓨터나 원거리 통신 장비 사이에서 메시지를 주고 받는 양식과 규칙의 체계

## HTML 맛보기
``` html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>연습</title>
</head>
<body>
<h1>
hello world!
</h1>

<h2>
hello world!
</h2>

<h3>
hello world!
</h3>

<input type="button" id="button1" onclick="button1_click();" value="버튼" />

</body>
</html>
```
## CSS 맛보기
```css
@font-face { font-family: 'GmarketSansLight'; src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2001@1.1/GmarketSansLight.woff') format('woff'); font-weight: normal; font-style: normal; }


h1 {
  color: red;
  font-family: 'GmarketSansLight';
}

h2 {
  color: pink;
  font-family: 'GmarketSansLight';
}

#button1 {
  color: blue;
}
```
## JavaScript 맛보기

``` js
function button1_click() {
	alert("버튼을 누르셨습니다.");
}
```
