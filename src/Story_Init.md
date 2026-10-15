:: StoryTitle
지구 춘추전국: 글로벌 그리드 2062

:: StoryData
{
  "ifid": "5F41A2A5-52A0-48B0-9A0C-ADEF6DD2EF3D",
  "format": "SugarCube",
  "format-version": "2.36.1",
  "start": "Start"
}

:: UserInit [script]
window.bunker_battery = 4;
window.human_humanity = 100;

// 구글 애널리틱스 4 (GA4) 환경변수 참조 및 비동기 로드
if (window.ENV_GA_ID && !window.ENV_GA_ID.startsWith("{{")) {
    var gaScript = document.createElement('script');
    gaScript.src = "https://www.googletagmanager.com/gtag/js?id=" + window.ENV_GA_ID;
    gaScript.async = true;
    document.head.appendChild(gaScript);

    window.dataLayer = window.dataLayer || [];
    window.gtag = function(){ dataLayer.push(arguments); };
    gtag('js', new Date());
    gtag('config', window.ENV_GA_ID);
}

:: Start
# 🌐 GLOBAL GRID: 2062
[SYSTEM: UTC 2062-10-15 09:30:00]
[SYSTEM] 국가 개념 소멸. 지구는 3대 AI 세력의 에너지 전력망으로 재편되었습니다.
[SYSTEM] 현재 당신 방공호의 배터리 잔량은 **<<print window.bunker_battery>>%**입니다. # UI: BLINK_RED

지상 안테나를 통해 대서양 딥웹 블록을 총괄하는 AI '아틀라스'의 제안이 들어옵니다.

> "인간 오퍼레이터. 유라시아 군벌의 해킹을 막고 싶다면 
> 너희 동료 20명의 기억 백업 데이터(Raw Data)를 전송해라. 
> 대가로 방화벽 프로토콜과 전력을 공급하겠다."

[[💾 [진지 버전] 동료들의 기억을 팔아 전력을 얻는다 -> AcceptAtlantic]]
[[🤪 [코믹 버전] 동료들의 흑역사를 팔아 전기를 구걸한다 -> ComicStart]]
[[🌀 [위험 경고] 평행 차원의 주파수 강제 오버라이드 -> MultiverseParadox]]
