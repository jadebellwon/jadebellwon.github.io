---
title: "Hextra 테마 기능 가이드"
date: 2025-05-21T10:00:00+09:00
draft: true
description: "Hextra 테마에서 사용할 수 있는 다양한 UI 요소들을 소개합니다."
tags: ["Hextra", "Guide", "Markdown"]
---

1. Callouts (강조 박스)

중요한 내용을 강조하고 싶을 때 사용합니다.

{{<callout type="info">}}
ℹ️ 정보: 이것은 정보(Info) 박스입니다. 독자에게 유용한 팁을 줄 때 사용하세요.
{{</callout>}}

{{<callout type="warning">}}
⚠️ 주의: 이것은 경고(Warning) 박스입니다. 주의해야 할 사항을 적으세요.
{{</callout>}}

{{<callout type="error">}}
🚫 에러: 이것은 에러(Error) 박스입니다. 치명적인 문제를 알릴 때 사용합니다.
{{</callout>}}

2. Tabs (탭 메뉴)

여러 언어의 코드나 옵션을 보여줄 때 유용합니다.

{{<tabs items="Python, JavaScript, Go">}}
{{<tab>}}

print("Hello, Hextra!")


{{</tab>}}
{{<tab>}}

console.log("Hello, Hextra!");


{{</tab>}}
{{<tab>}}

fmt.Println("Hello, Hextra!")


{{</tab>}}
{{</tabs>}}

3. Cards (카드 링크)

다른 페이지나 외부 링크를 카드 형태로 예쁘게 보여줍니다.

{{<cards>}}
{{<card link="https://github.com" title="GitHub 바로가기" icon="github">}}
{{<card link="/docs" title="문서 페이지로 이동" icon="book-open">}}
{{</cards>}}

4. Steps (단계별 설명)

튜토리얼을 작성할 때 순서대로 따라오게 만들기 좋습니다.

{{<steps>}}

1단계: 설치

터미널을 열고 설치 명령어를 입력합니다.

2단계: 설정

설정 파일을 열어 필요한 옵션을 수정합니다.

3단계: 실행

서버를 실행하여 결과를 확인합니다.

{{</steps>}}

5. 수식 (Math Support)

수학 공식을 깔끔하게 렌더링합니다. (KaTeX 사용)

인라인 수식: $E = mc^2$

블록 수식: