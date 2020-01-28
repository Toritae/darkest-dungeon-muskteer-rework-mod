# darkest-dungeon-muskteer-rework-mod 설명

다키스트 던전의 총사를 리워크하기 위한 프로젝트.

글쎄요... github 사용은 처음이라 괴수들의 지원이 필요할수도 있습니다.

닼던의 총사를 다음과 같이 리워크하고, 그에 걸맞는 장신구를 쥐어주기 위한 프로젝트입니다. 많은 참여 부탁드립니다.

현재까지의 변경점을 다 열거하자면 다음과 같습니다. 추가하실 경우, Readme를 수정하거나 commit할 때 기록을 남기시기 바랍니다.

1. 우선 공격력을 노상강도와 일치하게 올립니다.
2. 스킬을 5레벨 기준 다음과 같이 설정합니다.

    집중 사격  
    o o x x - x o o o  
    명중률 115  
    공격력 +20% - 5%에서 시작  
    크리율 +9%  
    명중 +10("표식 찍힘" 대상)  
    방어력 관통 +40%("표식 찍힘" 대상) - 20%에서 시작  

    연막탄  
    o o o o  
    3턴 은신  
    강화: 속도 +4(+2에서 시작)  
    약화: 명중 -10(-18에서 시작)  

    신호탄  
    o o x x - x o o o  
    명중률 120  
    공격력 -40% (-50%에서 시작)  
    크리율 -2%  
    표식 찍음(3턴)  
    적 약화: 크리티컬 당할 확률 최대 +10% (140% 기반)

    샷건  
    x o o o - o x x x  
    명중률 115  
    공격력 -20%  
    크리율 +4%  
    뒤로 3 (140% 기반)  

    권총 사격  
    x x o o - x o o o  
    명중률 100  
    공격력 -25%  
    크리율 0%  

    응급처치  
    o o o o  
    최대체력의 15% 회복  

    스키트 사격  
    o o x x - x o o o (변경 가능)  
    명중률 115  
    은신 무시 및 해제  
    방어 무시 및 해제  
    적 약화: 받는 데미지 최대 +25% (130% 기반)  
    적 약화: 방어 불가능 디버프 (130% 기반)  
    표식 찍음(3턴)  

    //자신 명중 15, 크리율 6 증가시키는 버프 추가 가능. 너무 사기적일 수 있어 보류

3. 장신구는 다음과 같이 설정되었습니다.

    튼튼한 신발  

    기존과 동일합니다.  

    복수의 신발(일반 -> 고급)  

    (체력 50% 이하일 시)데미지 15% 증가  
    (체력 50% 이하일 시)크리티컬 확률 12% 증가  

    의무병의 신발(고급 -> 희귀)  

    "응급처치" 스킬이 "중독", "출혈" 대상에게 치유량 +50%.  

    백발백중의 모자(불스아이 모자)  

    명중 +10  
    최소 데미지 +3 //최대 데미지는 영향이 없다  
    크리티컬 확률 +5%  
    받는 피해 +25%  

    격노의 모자  

    (3열에서) 데미지 +25%  
    (3열에서) 스피드 +5  
    명중 -10  
    회피 -15  
    죽음의 문턱 저항 -15%  

4. 캠핑 스킬은 다음과 같습니다.

    응급 치료

    3TC

    타인 1명

    (75% 확률) 체력 25% 치료  
    (25% 확률) 체력 50% 치료  
    출혈 저항 30%  
    중독 저항 30%  

    행군 계획

    5TC

    자신에게

    적이 기습할 확률 -20%  
    아군이 기습할 확률 +20%  

    모두에게

    이동 저항 +30%

    화승총 손질

    5TC

    자신에게

    원거리 공격력 +30%  
    원거리 크리율 +12%  
    속도 +4  

    부상자 분류  

    6TC  

    모두에게  

    체력 20% 치료  
    필멸의 약화 제거  

5. 크리가 터진 경우, 2턴간 "속도 +2, 데미지 +20%"의 보너스를 받습니다.

향후 계획은 다음과 같습니다.

1. 스킬들이 꿀잼이 될 때 까지 지속적으로 수정한다. //문제 다량 발견으로 재작업 중.
2. 스킬들을 보조할 수 있는 장신구들을 추가한다. // 이런저런 수정을 가하는 중. CC와 COM은 아직 미완성
3. 차별화된 캠핑 스킬을 제공한다. //완료.
4. 크리가 터졌을 때 제공할 보너스를 정한다. //기본적으로는 완료. 그러나 반격으로 변경될 수 있습니다.
5. 테스트가 아닌 본 편으로 제공한다.

개발중인 모드입니다. 기여할 능력자들의 많은 기여 부탁드립니다 꾸벅-

+ 기여자 가이드

글 작성 이후 완성합니다.
