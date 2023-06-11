---
title: 라이브 디버깅
layout: docs.hbs
---

# 라이브 디버깅

* [라이브 디버깅](#live-debugging)
  * [응용 프로그램이 예상대로 작동하지 않을 때](#my-application-doesnt-behave-as-expected)
    * [증상](#symptoms)
    * [디버깅](#debugging)

이 문서를 통해 Node.js 프로세스를 라이브 디버그하는 방법을 배울 수 있습니다.

## 응용 프로그램이 예상대로 작동하지 않을 때

### 증상

사용자는 응용 프로그램이 특정 인풋에 대해 예상되는 아웃풋을 제공하지 않는 것을 발견할 수 있습니다. 예를 들어, HTTP 서버가 특정 필드가 비어있는 JSON 응답을 리턴하는 것처럼요. 프로세스 중 많은 오류가 발생할 수 있지만 이 사용 사례에서 우리는 응용 프로그램 로직과 그 정확성을 중점적으로 다룹니다.

### 디버깅

이 사용 사례에서, 사용자는 들어오는 HTTP 요청과 같은 특정한 트리거에 대해 응용 프로그램이 실행하는 코드 경로를 이해하고자 합니다. 또한 코드를 따라가며 메모리에 저장된 변수의 값을 검사할 뿐아니라 실행을 제어하길 원할 수도 있습니다.

* [검사기 사용하기](/en/docs/guides/diagnostics/live-debugging/using-inspector)