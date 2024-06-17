# 함께, 하나?

## Project Introduction
> Meteor의 Gold rounge에서는 PB와 VIP가 소통하는 프리이빗한 디지털 라운지를 제공합니다
> 
> 1대1 화상 상담을 통해 시공간의 제약 없이 자산 관리가 가능합니다

## Team Composition
<div align="center">

| **[팀장] 이상민** | **신지연** | **이고은** | **이지후** | **정찬수** |
| :------: | :------: | :------: | :------: | :------: |
| [<img src="https://avatars.githubusercontent.com/tkdalsss" height=150 width=150> <br/> @tkdalsss](https://github.com/tkdalsss) | [<img src="https://avatars.githubusercontent.com/jiyeoon00" height=150 width=150> <br/> @jiyeoon00](https://github.com/jiyeoon00) | [<img src="https://avatars.githubusercontent.com/egon6018" height=150 width=150> <br/> @egon6018](https://github.com/egon6018) | [<img src="https://avatars.githubusercontent.com/lee010207" height=150 width=150> <br/> @lee010207](https://github.com/lee010207) | [<img src="https://avatars.githubusercontent.com/iamcharles98" height=150 width=150> <br/> @iamcharles98](https://github.com/iamcharles98) |

</div>

## Project Structure
추후 업로드

## Project Rules
### Prettier
- prettier를 활용한 코드 포맷팅을 통해 정해진 규칙에 따라 자동적으로 코드 스타일을 정리해 코드의 일관성을 유지하고자 했습니다

### Branch Management Stage
1) Issue 생성 → Issue에 해당하는 Branch 생성
3) 해당 branch로 이동 후 개발 진행 → push
4) Pull&Request 생성
5) code review & approve → merge to main branch

### Commit Message Convention
- :tiger: 커밋 메시지 구조
  ```
  type: subject

  body

  footer
  ```
- :snowman: 커밋 타입
  ```
  * feat: 새로운 기능 추가
  * fix: 버그 수정
  * docs: 문서 수정
  * style: 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
  * test: 테스트 코드, 리팩토링 테스트 코드 추가
  * chore: 빌드 업무 수정, 패키지 매니저 수정
  ```
- :frog: Subject
  ```
  제목은 50자를 넘기지 않고, 대문자로 작성하며 마침표를 붙이지 않는다
  
  과거 시제를 사용하지 않고 명령어로 작성
  > "Fixed" -> "Fix", "Added" -> "Add"
  ```
- :panda_face: Body
  ```
  선택사항이기 때문에 모든 커밋에 본문내용을 작성할 필요는 없음
  부연설명이 필요하거나 커밋의 이유를 설명할 경우 작성
  72자를 넘기지 않고 제목과 구분되기 위해 한칸을 띄워 작성
  ```
- :umbrella: footer
  ```
  선택사항이므로 모든 커밋에 꼬리말을 작성할 필요는 없다
  issue tracker id를 작성할 때 사용
  ```
