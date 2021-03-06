---
title: 진행상황
class: hideable
hide: false
hidedesc: "대회가 시작되면 업데이트 됩니다."
layout: default
pagetype: updates
navselect: updates
permalink: /updates
---

## Phase 1. 두번째 과제

<center>
우여곡절 끝에 사내 동아리 홈페이지는 잘 운영되었습니다. <br>
직원들의 만족도도 상당하네요! <br>
<br>
그런데 동아리 홈페이지가 운영되기 시작한지 며칠 지나지않아 개발자와 서버 관리자가 조용히 찾아옵니다.<br>
<br>
<b> "아무래도 외부에서... 악의적인 접속이 있었던듯 합니다..."</b><br>
<br>
자세히 이야기를 들어보니 파일 공유 게시판에서 침해흔적이 발견되었답니다.<br>
어휴!... 그렇게 조심하라고 경고했었건만... <br>
아무 문제 없을거라며 자신만만하던 개발자는 서버 관리자 뒤에서 말없이 고개만 숙이고 있네요.<br>
<br>
개발자와 서버 관리자가 찾아온 이유는 무언가 침입이 있었다는건 알겠는데<br>
어디로 어떻게, 그리고 무엇이 털렸는지(?) 자기들은 도저히 다 파악을 못하겠다합니다.<br>
그래서 정보보안전문가인 여러분을 찾아왔다네요.<br>
<br>
이러한 침해사고의 가장 중요한 것들 중 하나는 현재 시스템의 상태를 가능한 빨리 확보하고 보존하는겁니다.<br>
여러분은 외장하드를 챙겨서 서버실에 한달음 달려가, <br>
침해가 발생한 웹서버의 이미지를 지금 막 확보하였습니다! <br>
<br>
자, 여기 그 이미지를 가상머신을 통해 작동 가능한 상태로 만들어두었습니다. <br>
<br>
지금부터 공격자가 어떻게 침입을 했는지 부터, 무엇이 털렸는지 피해 정도를 식별해보고,<br>
이를 방지하기 위한 방법들을 고민해 봅시다.<br>

<p></p><hr style="width:50%;"><p></p>
<b style="font-weight: 700;color:#1154FF"> 웹서버의 침해를 파악하고 대응책을 고민해보세요. </b>
</center>

1. 첨부된 링크는 1단계 문제를 작동시키던 웹서버의 가상머신 이미지입니다. 
2. 해당 웹서버에 파일 공유 게시판을 중심으로 침해가 있었습니다!
3. 공격자의 침해 경로 및 행위등을 분석하고, 피해 정도를 파악해주세요.
4. 상세한 내용은 문제 파일의 보고서에 안내되어있습니다.
   
* 기대 결과물: 진단 보고서, 환경구성을 위한 스크립트 또는 프로그램 코드
  
* 문제 다운로드: ['두번째 과제'](https://src-jnu.myDS.me:38881/sharing/HE9NbD1Vl)  
    - 링크에 접속하면 가상머신의 이미지와 보고서 양식등이 들어있습니다. 
    - 파일의 비밀번호는 참가자들에게 개별로 전달됩니다. 
    - 링크의 비밀번호와 내부 압축파일의 비밀번호는 동일합니다.
  
* 제출기한: **2022년 7월 31일 일요일 오후 18시 00분.** 
   - 제출 기한을 초과하면 패널티가 있으니 기한을 엄수해주세요.
  
* 대회와 관련된 각종 질문들은 별도로 안내해드릴 채널을 통해 해주시면 됩니다.

* 본 문제의 서버의 이야기는 다음 단계에서도 죽 이어집니다!

<p></p><hr style="width:90%;"><p></p>

## Phase 1. 첫번째 과제

<center>
호남지역의 우수한 인재들이 모여 만들어낸 HCC Company (HCCC)는 자그마한 스타트업부터 시작해 지금은 대한민국 국민이라면 누구나 주목할만한 회사로 성장하였습니다. <br>
<br>
회사가 커진 만큼, HCCC는 사내 복지의 일환으로 동아리 활동을 지원하기로 결정하였으며,<br>
이에 HCCC는 동아리 내부에서 원할한 커뮤니케이션이 이루어질 수 있도록 '공지사항, 게시판, 자료실 등'의 기능을 가진 웹사이트를 자체 제작 하였습니다.  <br>
<br>
여러분은 HCCC의 새내기 정보보안전문가로서, <br>
제작된 웹사이트에 대한 보안성 검토를 요청을 의뢰받았습니다.  <br>
<br>
<b> 이런...! </b><br>
<br>   
보안성 검토를 해야한다고 개발자에게 협조를 부탁하니, 개발자는 귀찮다는 듯이 소스코드와 간단한 설정파일만 던져주고 나머지는 알아서 하라고 합니다. 아무 이상 없다는 말을 덧붙이면서요...!  <br>
개발 과정에서 정보보안이란 그저 일정만 지연시키는 불필요한 단계라 여겨지는 듯 합니다.  <br>
<br>
아무래도 보안에 대한 고려 없이 만들어진 웹페이지가 얼마나 위험할 수 있을지 알려주고, <br>
정보보안의 중요성을 확실하게 보여줘야 할 듯 합니다. <br>
<br>
뭐...그러려면 일단 웹페이지에 대한 테스트 환경을 구축하는 것 부터 시작하긴 해야하겠네요! <br>
<p></p><hr style="width:50%;"><p></p>
<b style="font-weight: 700;color:#1154FF"> 첨부된 파일의 웹페이지를 구성하고 취약점을 진단하세요. </b>
</center>

1. 제공된 웹페이지 파일들(i.e., 소스코드와 설정파일)을 사용해 테스트 환경을 구축하고 실행하세요.
2. 웹페이지에 어떤 취약점이 있는지 파악하세요. 취약점은 Client-side, Server-side 모두를 포함합니다.
3. 취약점이 존재하는 경우 해당 취약점에 대한 대응방안 또는 패치를 제시하세요.
4. 상세한 내용은 문제 파일의 보고서에 안내되어있습니다.
   
* 기대 결과물: 진단 보고서, 취약점이 패치된 웹페이지 파일들 또는 환경구성을 위한 스크립트 등. 
  
* 문제 다운로드: ['첫번째 과제'](pds/hccc2022_p11.zip)  
    - 압축을 풀면 웹페이지의 압축, 보고서 양식등이 들어있습니다. 
    - 파일의 비밀번호는 참가자들에게 개별로 전달됩니다. 
  
* 제출기한: **2022년 7월 14일 오전 11시 59분.** 
   - 제출 기한을 초과하면 패널티가 있으니 기한을 엄수해주세요.
  
* 대회와 관련된 각종 질문들은 별도로 안내해드릴 채널을 통해 해주시면 됩니다.

* 본 문제의 웹페이지 이야기는 다음 단계에서도 죽 이어집니다!
  
<p></p><hr style="width:90%;"><p></p>