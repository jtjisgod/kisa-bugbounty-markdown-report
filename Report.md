<style>
  table {
    font-size: 12pt;
  }
  table > thead > tr > th {
    text-align: center;
    background: #dddddd;
    font-size: 16pt
  }
  table > tbody > tr > td:nth-child(2n-1) {
    font-weight: bold;
    width: 120px;
  }
  table > tbody > tr > td {
    background: #fff;
    text-align: center;
  }
  div{
    font-size: 9pt;
    text-align: left;
    font-weight: normal;
  }
  th:empty {
    font-size: 0px;
    margin: 0;
    padding: 0;
    border: 0;
  }
</style>
<table class="report_header">
  <thead>
    <tr><th colspan=5>S/W 신규 취약점 신고서</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>성  명</td><td colspan=2>{성명}</td>
      <td>소  속</td><td>{소속}</td>
    </tr>
    <tr>
      <td>이메일</td><td colspan=2>{이메일}</td>
      <td>전화번호</td><td>{전화번호}</td>
    </tr>
		<tr>
      <td>주  소</td><td colspan=4>{주소}</td>
    </tr>
    <tr>
      <td rowspan=2>명예의 전당</td>
      <td colspan=4 style="text-align:left;">
        <div>
          <b>KrCERT&amp;보호나라 홈페이지 실명 게시 동의여부</b>
          <b style="float:right;">동의 ■     미동의 □</b>
        </div>
        <div>o 해당 내용은 보호나라&KrCERT 홈페이지의 “명예의 전당” 페이지에 게시됩니다.</div>
        <div>※ 아래 닉네임과 웹사이트 주소를 작성해 주실 경우, 실명과 함께 게시됩니다.</div>
        <div>※ 게시 대상은 포상금을 수령한 신고자에 한하여 게시됩니다.</div>
      </td>
    <tr>
      <td style="width:60px;font-weight:bold;">닉네임</td>
      <td style="font-weight:normal;">{닉네임}</td>
      <td style="width:60px;font-weight:bold;">웹사이트 주소</td>
      <td style="font-weight:normal;">{웹주소}</td>
    </tr>
		<tr>
      <td colspan=5>
        <div>
          <b>o 본 취약점을 KISA 신고 전에 공개, 다른 기관 신고, 해당업체 통보 등 여부</b>
        </div>
        <div style="padding-left: 15px;">
          <b>□ 예 ( 대상 및 일자 : OOOOOOOO 0000.00.00 )  /  ■ 아니요</b>
        </div>        
      </td>
		</tr>
		<tr>
      <td colspan=5>
        <div>
          <b>o 본 취약점이 정부 지원 사업*을 통해 발굴된 취약점인지에 대한 여부</b>
          <b style="float:right;">예 □     아니요 ■</b>
        </div>
        <div style="margin-left:15px;">* 정부 예산이 투입된 연구과제 또는 프로젝트</div>
      </td>
		</tr>
		<tr>
      <td colspan=5 style="font-size:9pt;padding:20px;">
        <div style="font-size:11pt;text-align: center;">
          <b>&lt;취약점 정보 활용 및 비밀유지&gt;</b>
        </div>
        <div>
          <div>o 신고된 취약점은 포상 관련 평가, 취약점을 보완한 제품 개발(보안 업데이트 개발)을 위해 활용됩니다.</div>
          <div>o 포상은 비공개된 취약점을 대상으로 하며(공개된 취약점은 포상 대상에서 제외), 신고 후에도 아래와 같이 그 어떠한 목적으로도 KISA를 제외한 제3자(제조사 포함)에게 공개할 수 없습니다.</div>
          <div>- KISA 포상 취약점: 제조사가 보안패치 한 날로부터 120일(4개월) 이전에 외부 공개 불가</div>
          <div>- 공동운영사 포상 취약점: 영구 공개 불가</div>
          <div>o 신고서에 작성한 내용이 사실과 다르게 작성되거나, KISA를 제외한 제3자에게 취약점을 공개한 경우, 비밀유지 의무 등을 위반한 사실이 밝혀진 경우 다음과 같은 불이익을 당할 수 있습니다.</div>
          <div>- 밝혀진 날로부터 1년 동안 평가 및 포상 대상에서 제외</div>
          <div>- 해당 취약점으로 이미 포상 받은 경우 포상 취소 및 지급 포상금 전액 환수</div>
        </div>
        <br/>
        <div style="text-align:center;font-weight:bold;">
          ▷취약점 정보 활용 및 비밀유지 동의여부
					<span style="float:right;">동의 ■ 비동의 □</span>
        </div>
      </td>
		</tr>
    <tr>
      <td colspan=5 style="padding:20px;font-size:9pt;">
	      <div style="font-size:11pt;text-align:center;"><b>&lt;정보통신망 이용촉진 및 정보보호에 관한 법률 위반행위 관련 안내&gt;</b></div>
        <div>o <u>실제 서비스 중인 웹사이트나 시스템(서버, 네트워크, 보안장비 등)에 특정 데이터를 전송하여 영향을 줄 우려가 있는 서비스 취약점은 평가 및 포상 대상에서 제외됨은 물론, 법에 의해 처벌 받을 수 있습니다.</u></div>
        <div style="background:#dddddd;padding:5px 30px;font-size:10pt;">｢정보통신망 이용촉진 및 정보보호에 관한 법률｣ 제71조 제10호 및 제48조 제3항에 따라 정보통신망의 안정적 운영을 방해할 목적으로 대량의 신호 또는 데이터를 보내거나 부정한 명령을 처리하도록 하는 등의 방법으로 정보통신망에 장애를 발생하게 하였다면 5년 이하의 징역 또는 5천만원 이하의 벌금에 처한다.</div>
      </td>
		</tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td style="padding:20px;">
        <div style="font-size:11pt;text-align:center;"><b>&lt;개인정보 수집·이용 동의&gt;</b></div>
        <div style="line-height: 25px;">
          <div>o 개인정보 수집 이용 목적 : 신규 취약점 신고포상제 운영 및 포상금 지급, 신고포상제 명예의 전당 게시</div>
          <div>o 수집하는 개인정보 항목 : 성명, 소속, 이메일, 연락처, 주소, 닉네임, 웹사이트 주소</div>
          <div>o 보유 및 이용기간 : 소득세법 등 관련법령에 따른 보유기간 또는 3년 / (명예의 전당) 사업 종료 시 파기</div>
          <div>o 개인정보의 수집·이용을 거부할 수 있으며, 이 경우 기념품 또는 포상금 지급, 명예의 전당 게시 및 상위 신고자 선정 시, 불이익이 발생할 수 있음을 알려드립니다.</div>
        </div>
        <br/>
        <div style="text-align:center;font-weight:bold;">
          ▷ 개인정보 수집·이용 동의여부
					<span style="float:right;">동의 ■ 비동의 □</span>
        </div>
      </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr><th>취약점 상세 설명 작성 시 준수 사항</th></tr>
  </thead>
  <tbody>
  <tr>
    <td>
      <div style="font-size: 11.5pt;font-weight:bold;">o 취약점 신고자는 다음 작성 방법을 준수하여 각 항목을 작성해야 하며, 내용이 불충분할 경우 재작성을 요청드릴 수 있습니다.</div>
      <div style="margin-left:10px;font-size:10pt;">
          <div>- 취약점을 증명/검증할 수 있는 개념증명코드(Proof Of Concept Code)는 별도 파일로 제출(필수) 바랍니다.</div>
          <div>- 취약점을 신고한 소프트웨어는 별도 파일로 제출 바랍니다.</div>
          <div>※ 상용 소프트웨어의 경우 해당 제조사 URL 기술해 주시기 바랍니다.</div>
          <div>- 신고 문서 내용이 사실과 불일치할 경우 문서완성도 평가 시 감점될 수 있습니다.</div>
          <div>- 취약점을 이용한 공격(계산기 팝업 등)이 포함된 공격코드(Exploit Code) 별도 제출 시, 기술 가산점을 부여합니다.</div>
          <div>- 실장비가 아닌 가상환경에서 발생하는 IoT 취약점일 경우, 특정 평가항목에서 감점될 수 있습니다.</div>
          <div> (보호기법 적용 환경 등 고려)</div>
      </div>
      <div style="color:red;font-size:11pt;">※ 취약점 상세 설명과 PoC 또는 공격코드에 신고자 정보가 노출되지 않도록 주의 부탁 드립니다.</div>
    </td>
  </tr>
	<tr>
    <td style="line-height:18pt;">
      <div style="font-size:11pt;"><b>1. 취약점 발견 방법</b></div>
      <div style="font-size:10pt;padding-left:20px;">
        <div>- 취약점을 어떻게 발견하였는지에 대한 기술 설명(크래시 발생, 퍼징 도구 활용, 코드 진단 등)</div>
      </div>
      <div style="font-size:11pt;"><b>2. 취약점 발생 원인</b></div>
      <div style="font-size:10pt;padding-left:20px;">
        <div>- 취약점 발생 입력 데이터 설명(문자열, 이미지 등의 파일)</div>
        <div>- 취약점 발생 위치 설명(함수, 어셈블리코드, 프로그램 주소 위치 등)</div>
        <div>- 취약점 발생 원인 설명(소스코드 분석, 리버싱 결과 등으로 취약점 발생 원인을 파악한 내용 기술)</div>
      </div>
      <div style="font-size:11pt;"><b>3. 취약점 증명/검증</b></div>
      <div style="font-size:10pt;padding-left:20px;">
        <div>- 취약점에 대한 상세 분석 결과 기술</div>
        <div>※ 취약점 분석 결과 스크린샷 및 설명, POC 디버깅 과정 설명 , 보호 기법 우회 기술, 취약점 발생 동영상 첨부 등</div>
      </div>
      <div style="font-size:11pt;"><b>4. 취약점 악용 시나리오</b></div>
      <div style="font-size:10pt;padding-left:20px;">
        <div>- 취약점이 악용될 수 있는 공격 시나리오와 관련 서비스(또는 시스템)에 미칠 수 있는 영향 </div>
      </div>
      <div style="font-size:11pt;"><b>5. 조치 방안</b></div>
      <div style="font-size:10pt;padding-left:20px;">
        <div>- 취약점을 해결할 수 있는 효과적인 방법 제시</div>
      </div>
      <div style="font-size:11pt;"><b>6. 기타</b></div>
      <div style="font-size:10pt;padding-left:20px;">
        <div>- 취약점 관련하여 참고할 수 있는 자료(웹사이트 주소 등)</div>
        <div>- 발견한 취약점을 악용하고 있는 사례가 있다면 이에 대한 설명</div>
        <div>- 첨부한 각 파일에 대한 설명(파일명 : 파일에 대한 설명)</div>
      </div>
    </td>
  </tr>
  </tbody>
</table>



<div style="font-size:13pt;text-align:center;font-weight:bold;margin-top:100px;">&lt;취약점 개요&gt;</div>

<table style="font-size:12px;">
  <tbody>
    <tr>
      <td>취약점 제목</td>
      <td style="text-align:left">
<pre>
Mollit exercitation magna aliquip esse ullamco nostrud ullamco mollit.
</pre>
      </td>
    </tr>
    <tr>
      <td>취약점 요약</td>
      <td style="text-align:left;height:600px;vertical-align:top;line-height:17pt;">
<pre>
Cupidatat ex magna consectetur proident velit enim aliqua sint proident. Labore ullamco commodo consectetur excepteur eiusmod. Tempor sit pariatur ea reprehenderit duis cupidatat ex consequat exercitation id tempor veniam. Ex consequat commodo reprehenderit ullamco ad Lorem. Sunt aliquip irure est anim eu dolor laboris sint.
Est anim sunt tempor eu veniam dolor sunt veniam ex consectetur. Eu ad anim eu amet laborum aliquip velit labore et. Culpa consectetur non duis cupidatat fugiat et dolor sunt nisi velit incididunt pariatur nulla.
Proident elit in commodo ea. Et cupidatat fugiat qui Lorem cupidatat anim sunt eiusmod laboris ex. Occaecat aliquip magna in et ut labore sunt consequat consectetur irure mollit aliquip. Laboris dolore nulla sint laborum occaecat cillum pariatur quis deserunt eu laboris. Sunt consectetur ullamco irure qui culpa minim deserunt deserunt Lorem mollit culpa cillum consequat laboris. Voluptate anim fugiat fugiat ea nostrud Lorem reprehenderit ea non nostrud.
Incididunt cupidatat ad deserunt pariatur anim incididunt commodo incididunt cupidatat. Irure tempor minim cupidatat culpa cillum enim ullamco non et. Ipsum ut quis adipisicing ea sit duis culpa adipisicing cillum irure. Officia proident irure laborum consequat duis culpa. Pariatur duis anim irure enim et culpa. Eu labore mollit mollit culpa ex pariatur sunt esse nisi anim exercitation laboris adipisicing elit. Aute laborum cupidatat ullamco culpa excepteur magna do enim ullamco est Lorem.
</pre>
      </td>
    </tr>
    <tr>
      <td>취약한 S/W의 버전</td>
      <td style="text-align:left">
<pre>
lorem ipsum v1.0.0
</pre>
      <div>※ 반드시 본인이 테스트한 버전만 명시</div>
      </td>
    </tr>
    <tr>
      <td>취약점 발생환경</td>
      <td style="text-align:left">
<pre>
lorem v1.0.0
ipsum OS v1.2.1
</pre>
        <div> ※ 취약점 테스트 시 사용된 운영체제 버전 정보, 어플리케이션, 별도로 설치가 필요한 프로그램(웹서버, 플러그인) 등 환경 구성에 대한 구체적인 정보 제시(단, 특정 환경에서만 발생하는 취약점의 경우 해당 환경에 대한 상세 설명 반드시 기재)</div>
        <div style="color:red;"> ※ 취약점 상세 설명과 PoC 또는 공격코드에 신고자 정보가 노출되지 않도록 주의 </div>
        </div>
      </td>
    </tr>
  </tbody>
</table>



<div style="font-size:13pt;text-align:center;font-weight:bold;margin-top:100px;">&lt;취약점 상세 설명&gt;</div>

## 1. 취약점 발견 방법

Duis commodo laboris laboris aliquip exercitation quis consequat labore. Dolor nisi velit elit Lorem magna magna ad cillum qui Lorem. Laborum cillum cupidatat exercitation ipsum ipsum nostrud. Amet incididunt velit anim esse non laboris. Sunt tempor et tempor ipsum veniam quis occaecat dolore exercitation velit pariatur culpa aliqua minim. Est elit sunt magna culpa proident fugiat pariatur consectetur. Adipisicing excepteur quis non culpa voluptate sunt Lorem. Voluptate irure excepteur velit est consequat dolore cupidatat ex sit est ipsum. Exercitation sit cupidatat labore eiusmod non adipisicing exercitation est tempor. Nisi ad occaecat laborum ut anim dolore aliqua. Ex veniam consequat enim anim quis eu anim dolore anim enim ex eu eu. Est ipsum cupidatat labore consectetur excepteur ex dolore ullamco deserunt consequat sunt. Nulla do aliqua adipisicing commodo est sunt ex. Laborum in velit ex ex esse reprehenderit laborum nulla reprehenderit magna in. Incididunt fugiat id dolor mollit veniam et sint incididunt laborum quis est amet.



## 2. 취약점 발생 원인

Duis commodo laboris laboris aliquip exercitation quis consequat labore. Dolor nisi velit elit Lorem magna magna ad cillum qui Lorem. Laborum cillum cupidatat exercitation ipsum ipsum nostrud. Amet incididunt velit anim esse non laboris. Sunt tempor et tempor ipsum veniam quis occaecat dolore exercitation velit pariatur culpa aliqua minim. Est elit sunt magna culpa proident fugiat pariatur consectetur. Adipisicing excepteur quis non culpa voluptate sunt Lorem. Voluptate irure excepteur velit est consequat dolore cupidatat ex sit est ipsum. Exercitation sit cupidatat labore eiusmod non adipisicing exercitation est tempor. Nisi ad occaecat laborum ut anim dolore aliqua. Ex veniam consequat enim anim quis eu anim dolore anim enim ex eu eu. Est ipsum cupidatat labore consectetur excepteur ex dolore ullamco deserunt consequat sunt. Nulla do aliqua adipisicing commodo est sunt ex. Laborum in velit ex ex esse reprehenderit laborum nulla reprehenderit magna in. Incididunt fugiat id dolor mollit veniam et sint incididunt laborum quis est amet.

Consectetur sunt reprehenderit exercitation ea dolore qui duis incididunt esse enim. Sit ex magna consectetur in pariatur consectetur amet duis. Nostrud ea nisi mollit Lorem cupidatat irure.

Laboris nulla labore ullamco enim pariatur eu eiusmod non consequat id sunt labore voluptate consequat. Excepteur quis culpa enim id commodo id tempor sunt enim duis. Ullamco duis aute quis eiusmod labore enim non. Cillum duis ad deserunt ex. Nostrud adipisicing enim ad exercitation nostrud amet ad nostrud aliqua minim aute eiusmod. Adipisicing sit nostrud exercitation laborum nisi non laboris elit nostrud aliqua commodo proident.



## 3. 취약점 증명 / 검증

Duis commodo laboris laboris aliquip exercitation quis consequat labore. Dolor nisi velit elit Lorem magna magna ad cillum qui Lorem. Laborum cillum cupidatat exercitation ipsum ipsum nostrud. Amet incididunt velit anim esse non laboris. Sunt tempor et tempor ipsum veniam quis occaecat dolore exercitation velit pariatur culpa aliqua minim. Est elit sunt magna culpa proident fugiat pariatur consectetur.

## 4. 취약점 악용 시나리오

Consectetur sunt reprehenderit exercitation ea dolore qui duis incididunt esse enim. Sit ex magna consectetur in pariatur consectetur amet duis. Nostrud ea nisi mollit Lorem cupidatat irure.

Laboris nulla labore ullamco enim pariatur eu eiusmod non consequat id sunt labore voluptate consequat. Excepteur quis culpa enim id commodo id tempor sunt enim duis. Ullamco duis aute quis eiusmod labore enim non. Cillum duis ad deserunt ex. Nostrud adipisicing enim ad exercitation nostrud amet ad nostrud aliqua minim aute eiusmod. Adipisicing sit nostrud exercitation laborum nisi non laboris elit nostrud aliqua commodo proident.



## 5. 조치 방안

Consectetur sunt reprehenderit exercitation ea dolore qui duis incididunt esse enim. Sit ex magna consectetur in pariatur consectetur amet duis. Nostrud ea nisi mollit Lorem cupidatat irure.



## 6. 기타

lla labore ullamco enim pariatur eu eiusmod non consequat id sunt labore voluptate consequat. Excepteur quis culpa enim id commodo id tempor sunt enim duis. Ullamco duis aute quis eiusmod labore enim non. Cillum duis ad deserunt ex. Nostrud adipisicing enim ad exercitation nostrud amet ad nostrud aliqua minim aute eiusmod. Adipisicing sit nostrud exercitation laborum nisi non laboris elit nostrud aliqua commodo proident.



<div><center>KISA Bugbounty markdown report creator - Jangtaejin &lt;jtjisgod@gmail.com&gt;</center></div>
