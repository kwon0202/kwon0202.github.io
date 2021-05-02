---
layout: post
title: "깃허브만으로 Github Blog 만들기 (Long Haul 테마)-1. 블로그 만들기"
date:   2021-05-02
categories: [blog]
---


<p>
<div style="text-align:justify">개미 코딱지만한 코딩 수준으로 왜 인지 깃허브 블로그에 꽂혀서 "나도 깃허브 블로그 갖고 싶다"는 코딩쪼랩을 위한 깃허브만으로 Github Blog 만들기!</div><br />
<div style="text-align:center">※ 블로그 주인 코딩 수준 : only '생활코딩 html 기초' 수료 ※</div><br />
<div style="text-align:right"><small>Jekyll 몰라서 못 쓰는거 아님<br />
   Jekyll 설치하다 못 알아먹어서 그런거 아님<br />
  코딩 쪼랩이라 틀릴 수 있음 기술적인 설명 못함 왜그런지 모름<br />
  얘보단 잘 한다라면 누구나 가능하다! 내 깃허브 블로그 만들기!</small></div>
</p>
<br />

<p>
<div style="text-align:center">블로그에 적용할 테마보기 - LONG HAUL 테마</div>
<br />
<img src="{{ '/assets/210502/1.png' | prepend: site.baseurl }}" alt="LONG HAUL 테마"></p>

<p>
<br />
<div style="text-align:center">깔끔하죠?</div><br />
<br />
<div style="text-align:right"><small>블로그 주인의 수준이 개미 코딱지만하기 때문에 다른 테마는 할 수가 없어요<br />
(이미 다른 테마로 만들었다가 실패실패실패. 성공한게 LONG HAUL테마)</small></div>
</p>

<br />
<p><div style="text-align:center">[그럼 START!]</div></p>

<ol>
    <li>아래의 홈페이지에 들어가기</li>
<br />
<a href=" http://jekyllthemes.org/themes/long-haul/" target="_blank">http://jekyllthemes.org/themes/long-haul/</a>

<br /><br />
 <li>Homepage 버튼을 누르기</li> 
<br />
<img src="{{ '/assets/210502/2.jpg' | prepend: site.baseurl }}" alt="">


<br />
 <li>왼쪽 깃허브 고양이 밑에 저장소 이름 확인</li><br />
brianmaierjr / long-haul 인지 확인! 
<img src="{{ '/assets/210502/3.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>오른쪽 fork 버튼 누르기</li> 
<br />
<img src="{{ '/assets/210502/4.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>저장소 이름 바뀐거 확인 후 setting 누르기</li>
 <br />
본인 깃허브 아이디 / long-haul 로 바뀜 
<br />
<img src="{{ '/assets/210502/5.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>저장소 이름(Repository name) 바꿔 깃허브 블로그 주소 받기 </li> 
 <br />
Repository name 아래에 <br />
본인 깃허브 아이디.github.io   →  Rename 버튼 누르기 
<br />
<img src="{{ '/assets/210502/6.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>저장소 주소 확인 </li> <br />
본인 깃허브 아이디 / 본인 깃허브 아이디.github.io 
<br />
<img src="{{ '/assets/210502/7.jpg' | prepend: site.baseurl }}" alt="">

<br /><br />
<div style="text-align:center">이제 블로그가 만들어졌어요 <br />
블로그 확인하러 가고 싶잖아요? 가봅시다</div><br />

<br />

<br />
 <li>setting 누르기 </li> 
<br />
<img src="{{ '/assets/210502/8.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>setting 페이지에서 아래로 쭉 내려와<br/> 
   GitHub Pages 찾기  →  Check it out here! 누르기 </li> 
<br />
<img src="{{ '/assets/210502/9.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>본인 블로그 링크 누르기</li> <br />
https://본인 깃허브 아이디.github.io/
<br />
<img src="{{ '/assets/210502/10.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>Long Haul 테마 적용은 됐지만 에러난 거 확인하고 절망하기</li> 
<br />
<img src="{{ '/assets/210502/11.png' | prepend: site.baseurl }}" alt="">

<br /><br />
<div style="text-align:center">URL 주소가 맞지 않기 때문에 테마가 제대로 적용이 안된 거에요<br /> 
파일 하나만 바꾸면 됩니다!<br />
url 주소를 바꾸러 갑시다.</div><br />

<br />
 <li>다시 깃허브 저장소로 돌아와서 아래로 쭉 내려와 _config.yml 파일 열기 </li> 
<br />
<img src="{{ '/assets/210502/12.jpg' | prepend: site.baseurl }}" alt="">
<br />
아래로 아래로<br /><br />
<img src="{{ '/assets/210502/13.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>url / baseurl 수정하기 위해 오른쪽 수정(연필버튼) 누르기</li> 
<br />
 url 과 baseurl 이 우리 블로그 주소가 아니라서 그런거에요 
<br />
요녀석들만 바꿔주면 됩니다  
<br />
<img src="{{ '/assets/210502/14.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>url /baseurl 주소 수정하기</li><br /> 
url: https://본인 깃허브 아이디.github.io/<br /> 
baseurl: "/" 
<br />
(baseurl은 두번째 주소라고 생각하시면 됩니다.<br />
하지만 우리는 baseurl이 없기때문에 공백으로 둡니다)
<br />
<img src="{{ '/assets/210502/15.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>아래로 내려와 Commit change 하기</li><br /> 

커밋을 한다<br /> 
= 현재에서 과거로 돌아갈 수 있는 시간의 문을 심는다.<br />  
= 언제든 그때로 돌아갈 수 있다.<br /> 
저는 "Change URL" 이라고 commit 제목을 정했지만 "url 바꿈" 이라고 하던지 "고양이 최고" 라던지 하셔도 상관없어요<br /> 
하지만 무얼 바꿨는지 단번에 알아볼 수 있게 해야 <br />
나중에 에러가 나서 다시 이때로 돌리고 싶을 때 쉽게 찾을 수 있어요!<br /> 
그래서 제목을 보고 무얼 바꿨는지 알 수 있게 적어놓는 겁니다</div><br />

<img src="{{ '/assets/210502/16.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>_congif.yml 파일 바뀐 것 확인하기</li> 
     _config.yml &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;본인이 쓴 커밋 제목 
<br />
<img src="{{ '/assets/210502/17.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>setting 누르기 </li> 
<br />
<img src="{{ '/assets/210502/8.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>setting 페이지에서 아래로 쭉 내려와<br/> 
   GitHub Pages 찾기  →  Check it out here! 누르기 </li> 
<br />
<img src="{{ '/assets/210502/9.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>본인 블로그 링크 누르기</li> <br />
https://본인 깃허브 아이디.github.io/
<br />
<img src="{{ '/assets/210502/10.jpg' | prepend: site.baseurl }}" alt="">

<br />
 <li>???? 바뀐게 없음을 확인하고 다시 절망하기 블로그 주인 원망하기 </li> 
<br />
<img src="{{ '/assets/210502/11.png' | prepend: site.baseurl }}" alt="">

<br />
 <li>조금 기다렸다가 새로고침(f5) 후 행복해하기</li> 
<br />
<img src="{{ '/assets/210502/18.jpg' | prepend: site.baseurl }}" alt="">


</ol>

<p><div style="text-align:center">이제 블로그가 만들어 졌습니다 축하합니다!<br />  
하지만 이렇게 블로그를 쓸 수는 없잖아요?<br />  
사진도 내맘대로 바꾸고 타이틀도 바꾸고 정말 내 블로그로 만들어 봅시다<br />
   <br />
   2탄에서는<br />
   사진바꾸기<br />
   타이틀 변경하기<br />
   카테고리 넣기<br /> 
   head 변경하기<br /> 
   about에 내 소개하기 등등<br /> 

그럼 2탄으로 돌아오겠습니다 이만</div> 
</p>

<br />  <br />  <br />  
참고 블로그 
<br />
<a href="https://blog.webjeda.com/jekyll-issues/" target="_blank">https://blog.webjeda.com/jekyll-issues/</a>


