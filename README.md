# woowa-techcourse-record
우아한 테크 코스 8기의 프리코스를 진행하며 공부한 내용을 주차별로 정리한 레포입니다.

## 작성한 과제 코드
[1주차 - java-calculator](https://github.com/bloodmoon3929/java-calculator-8/tree/bloodmoon3929)


## 회고록 & 후기

## 주차별 피드백
[1주차 피드백](./feedback/1Week_feedback.md)
[2주차 피드백](./feedback/2Week_feedback.md)
[3주차 피드백](./feedback/3Week_feedback.md)

## 공부한 내용



# git
## 기능 구현을 위한 브랜치 생성
```
git checkout -b bloodmoon3929
```

## 기능 구현 후 add, commit
```
git status
git add -A
git commit -m "{원하는 메시지}"
```

## 브랜치 merge (A에 B의 내용을 병합)
```
git checkout A
git merge B
```

## github에 업로드
```
git push origin bloodmoon3929
```

## 과제 제출
브랜치 오른쪽에 있는 "New pull request"
[$미션제목] $이름 미션 제출합니다. 형식으로 Pull request

Pull request 주소 복사 후 https://apply.techcourse.co.kr/applications/me 로 제출

# test
## 헤더파일
```java
import org.junit.jupiter.api.BeforeEach;
import org.junit.jupiter.api.DisplayName;
import org.junit.jupiter.api.Nested;
import org.junit.jupiter.api.Test;

import static org.assertj.core.api.Assertions.*;
```
