# github action 개념
event, workflow, job, actions, runners 

- events: = trigger, 예시) on: push
- workflow: event trigger 되었을 때, 하는 동작 명시
- jobs: workflow 안에서 실행되는 단위.
예시) 하나의 workflow 안에서 unit test 실행 + e2e 테스트 실행. 병렬적 혹은 순차적으로 실행하는거 가능. 
- job 안에서는 step으로 명령어 실행할 수 있습니다.
- action: github action 에서 제공하는 공개된 명령어
- runners: job 을 실행하는 주체, VM machine 혹은 docker container

---

