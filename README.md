# darkest-dungeon-muskteer-rework-mod

다키스트 던전의 총사를 리워크하기 위한 프로젝트.

글쎄요... github 사용은 처음이라 괴수들의 지원이 필요할수도 있습니다.

닼던의 총사를 다음과 같이 리워크하고, 그에 걸맞는 장신구를 쥐어주기 위한 프로젝트입니다. 많은 참여 부탁드립니다.

현재까지의 변경점을 다 열거하자면 다음과 같습니다. 추가하실 경우, Readme를 수정하거나 commit할 때 기록을 남기시기 바랍니다.

1. 우선 공격력을 노상강도와 일치하게 올립니다.
2. 스킬을 5레벨 기준 다음과 같이 설정합니다.

    집중 사격
    o o x x - x o o o
    명중률 105
    공격력 +10%
    크리율 +9%
    명중 +15("표식 찍힘" 대상)
    방어력 관통 +40%("표식 찍힘" 대상) - 20%에서 시작

    연막탄
    o-o x x
    2턴 은신
    강화: 속도 +4(+2에서 시작)
    약화: 명중 -10(-18에서 시작)

    신호탄
    o o x x - x o o o
    명중률 120
    공격력 -50%
    크리율 -2%
    표식 찍음(3턴)

    샷건
    x o o o - o x x x
    명중률 115
    공격력 -20%
    크리율 +4%
    뒤로 3 (140% 기반)

    권총 사격
    x o o o - x o o o //수정 장신구에 부여할 효과와 충돌하고 있으므로, 3열에서 공격 불가능하게 수정할 계획입니다.
    명중률 100
    공격력 -25%
    크리율 0%

    응급처치
    o o o o
    체력 3 회복
    추가로 최대체력의 10% 회복

    스키트 사격
    o o x x - x o o o (변경 가능)
    명중률 115
    은신 무시 및 해제
    방어 무시 및 해제
    대상 회피 -20(130% 기반)
    방어 불가능 디버프(130% 기반)

    //자신 명중 15, 크리율 6 증가시키는 버프 추가 가능. 너무 사기적일 수 있어 보류

3. 장신구는 다음과 같이 설정되었습니다.

    튼튼한 신발
    
    기존과 동일합니다.

    복수의 신발(일반 -> 고급)

    (체력 50% 이하일 시)데미지 15% 증가
    (체력 50% 이하일 시)크리티컬 확률 12% 증가

    의무병의 신발(고급 -> 희귀)

    "응급처치" 스킬이 "중독", "출혈"을 제거함.

    백발백중의 모자(불스아이 모자)

    명중 +10
    최소 데미지 +40% //최대 데미지는 영향이 없다
    크리티컬 확률 +5%
    받는 피해 +15%

    격노의 모자

    (3열에서) 데미지 +25%
    (3열에서) 스피드 +5
    명중 -10
    회피 -15
    죽음의 문턱 저항 -15%

향후 계획은 다음과 같습니다.

1. 스킬들이 꿀잼이 될 때 까지 지속적으로 수정한다. //일단은 된 듯. 그러나 문제가 발견될 시 재작업 가능
2. 스킬들을 보조할 수 있는 장신구들을 추가한다. // 바닐라 변경 완료. 피드백이 들어올 시 수정. CC 및 COM 장신구 아직 미변경.
3. 차별화된 캠핑 스킬을 제공한다. //미완
4. 크리가 터졌을 때 제공할 보너스를 정한다. //완료
5. 테스트가 아닌 본 편으로 제공한다.

개발중인 모드입니다. 기여할 능력자들의 많은 기여 부탁드립니다 꾸벅-
