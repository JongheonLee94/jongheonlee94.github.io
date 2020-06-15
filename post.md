---
layout: default
title: Post
---
# Post page
---



## Try jekyll tutorial 
### 2020/06/13
Jekyll 튜토이얼 사이트

https://jekyllrb-ko.github.io/docs/step-by-step/01-setup/


1. 루비 2.6.6 을 설치한다.

2. CMD를 열어 "gem install jekyll bundler"을 입력하여 jekyll과 bundler를 설치한다.

3. 프로젝트 폴더에서 "bundle init"입력하여 Gemfile을 만든다.

4. Gemfile 안에 "gem "jekyll"을 추가한다. 

5. 원하는 페이지를 만듭니다.

6. "jekyll build"로 빌드하거나 "jekyll serve"를 이용합니다. 전자는 빌드하여 _site 디렉토리에 정적 페이지 생성하고 후자는 빌드와 로컬서버를 구동합니다.

7. http://localhost:4000/페이지이름.html 
         -index.html이라면 페이지이름.html 제거


---

## 2~3 Liquid

Liquid 태그를 실행시키기 위해선 반드시 위쪽에

"---

---"
가 있어야 함.


-태그설명 -  https://jekyllrb-ko.github.io/docs/liquid/tags/

---

## 4.레이아웃

_layouts 폴더를 만들고 그 안에 레이아웃으로 쓸 페이지를 만든다.
바뀔부분에 {{ content }} 를 넣는다.

사용할 페이지에 아래에 내용을 입력한다.

"--- 

layout: default

---"

쓸내용

---


## Try jekyll tutorial 
### 2020/06/15

## 5.조각파일
 
 include 태그이용

1. _includes 폴더 생성하고 html 파일생성

2. {% include 파일명.html %} 원하는 _includes 하위 파일명을 가져다 쓴다.

