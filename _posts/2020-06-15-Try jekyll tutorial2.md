---
layout: post
author: Jongheon
---
## 5.조각파일
 
 include 태그이용

_includes 폴더 생성하고 html 파일생성


```
{% raw %}
 {% include 파일명.html %}
{% endraw %}
```
원하는 _includes 하위 파일명을 가져다 쓴다.

설명을 하기 위해 쓴
{% raw %}
  {% include 파일명.html %}
{% endraw %}
가 문제를 발생

{% raw %}
    {% raw %}
{% endraw %}
와 endraw

를 사용해서 해결

## 6.데이터
_data 하위에 yml 을 만들고 추후 site.data.navigation으로 이용가능합니다.

## 7.에셋
에셋 하위에는 css images js 를 넣는다
scss를 assets/css하위에 만들고 이용한다. 추후 jekyll이 이 파일을 css로 바꿔준다.

## 8.블로깅
데이터베이스 없이 블로그 기능을 만드는 것
