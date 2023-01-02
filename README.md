$git tag
v1.0


# font

Spoqa Han Sans를 웹폰트로 사용하시려면 2가지 방법이 있습니다.

스타일 시트에 아래의 코드를 넣거나,

@import url(//spoqa.github.io/spoqa-han-sans/css/SpoqaHanSansNeo.css);
@import url(//spoqa.github.io/spoqa-han-sans/css/SpoqaHanSans-jp.css);
혹은 HTML의 <head> 태그 안에 아래의 코드를 넣어주세요.

<link href='//spoqa.github.io/spoqa-han-sans/css/SpoqaHanSansNeo.css' rel='stylesheet' type='text/css'>
<link href='//spoqa.github.io/spoqa-han-sans/css/SpoqaHanSans-jp.css' rel='stylesheet' type='text/css'>
그후 <style> 태그 안에 font-family 를 설정해주세요.

* {
  font-family: 'Spoqa Han Sans Neo', 'Spoqa Han Sans JP', sans-serif;
}
