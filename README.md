# 개요

Jekyll을 이용한 블로그 만들기

## 순서
1. Chirpy 테마 fork
https://github.com/cotes2020/jekyll-theme-chirpy/fork

2. 로컬 clone

3. chirpy 초기화 하기

4. 로컬에서 실행해 보기
bundle
jekyll serve or jekyll serve -host 0.0.0.0

5. github action 변경
settings --> Pages --> Github actions으로 변경

6. 로컬에서 레포지토리로 올리기
git pull
git rm _posts/2019-08-08-write-a-new-post.md
git rm _posts/2019-08-09-getting-started.md
git commit -n -m "11111"



## (이미지 처리)
page내에서 image_path: /assets/images/ 정의하고
![이미지2]({{ page.image_path }}/apple-touch-icon.png)

또는

_config.yml 내에서 image_path: /assets/images/ 정의하고

![이미지2]({{ site.image_path }}/apple-touch-icon.png)


이미지 사이즈 줄이기
![이미지2](/assets/images/apple-touch-icon.png){: width="70%"}


