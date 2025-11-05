# woowa-techcourse-record
우아한 테크 코스 8기의 프리코스를 진행하며 공부한 내용을 주차별로 정리한 레포입니다.

## 작성한 과제 코드

## 회고록 & 후기

## 참고 레퍼런스







# intellij
## 한글 깨짐
vm 옵션에 다음을 삽입
```
-Dfile.encoding="UTF-8" -Dsun.stderr.encoding="UTF-8" -Dsun.stdout.encoding="UTF-8" 
```

# 다이어그램
## 링크
https://mermaid.live/edit#pako:eNq1V91OG0cUfpXRXhnFRjb-CV0JKpSSKlJLKkdtpQIXE3sw29iz29nZBIKQiOSobmwpTQstQZiShpaozYUVQAWJvpB3_A49s8uu7d21sSvhC1vjOb_fOd-ZmQ2loBeJoiom-c4itEA-0XCJ4coSRfDBBa4z9KVJmLs2MONaQTMw5WjOMMpaAXNNp-HNPC5otHRHp5zp5XKU-j1qWDz891e4rBUxeA1v3bd4pEoe06Je-ZRQwqIVIRgZgbshk0nMzvZEr6LOdtV-s9_-59w-eIdE_ajzyw-ucI8U6ASTUhGzaGzCFXW_F3ROkP6YsBACcTd8FbU__CveXooWeGqe2n9WkTh4bh_-gez6u_ZJ1TUTVAbnnrpGNe75dP-DTZmUipYU13Zn5xCM_mi_fN31Ipqeo87Orqiei73tJaUPEacg0oihP9TiT3Sqxb-1qCfk7HalGMHFzzRKvEi8bb98KlrF5nzF4OsPOINcYu7P4vKVAi5zZF_UkP3-HEIVv54i8eZUHLx3d-XHN5Xour0HYJRweY6VrAqhfH6tQIxuA3YD8SFZnM_n7-eXfRBO-526eoQWB2Zh0SJhd7XHJCqBLFhB4rTWPrm8obhDHobFWrT8bl3AlciIxdEr--TshrF2fESGG0kiL0xEIWhzTDaJ-r79soo6e7-J2u6YVMLmo7vMHXvrAynlOpCUcn3YL7aR_df3sGqI5nm7tQVM-ngQlbL_nz4wwEyyYFUeEnZVyN4y1v6GxgDnSOxU7fruTVUy0s2wFtTMBXDFJV80ynsjbjYAvBtjd9f4KB0HoaEVr_IjNpxziMjp3RAHMEqPtuyL6zsMzoc8Ma0yH9Je8rQBsy1JcWWgxXASFfyIzDGG14M8L-u6gdqtZ1dDzz6u2fWjLobRxqVFSp64Z2VMMnGiT4WwaCidLfDWFB-C03RcSI-r_rk7EgCmxi1n2MUcQ4vLcdTtOQcEv8Yed48bnWeX10DRd5mQVOUWoy7QZUJLfLUPmD7pgd0Gw405otD2ljfjRq80wOfWpTdRv959NfdvF8Gye0TsiQPNzqBMv8TwBpGBxCYiNXrFTI65Zd661S_o90VoMYRAoRqPnbPPuKvgSoQ7h2MgDb_FPc8uqZwz6VqDD5yErzUpx46LzQCL3lCQTpGKEomENxFCmAV0YvJaI46qE-Ny0D9H91rixYW8bcAoEoc7Y_BwRaPFrzVKu_05Mab253jtCx1KHa7z9TUe3K2RhRkyyoLl8UEcKQ9xtm83fm63foI5DhG_Fs2t3qt-bVccvxo1J8lTNxI0MwOD3kcn1GCDUx_a5IMuYYF29xEYBoXXQQYY4Fd9EDiRwqfe2b74_XlP04G6fHWgnhfHAIfBtxvYsd82ws8131v_486RVuJKiWlFReXMInGlQlgFy6WyIe0sKXyVAAyKjLRIVjCc3zKoTVCD9-Q3ul7xNJlulVYVdQWXTVhZBtxovAe0L0LkC-KOblGuqJnM1G3HiKJuKGuKmpqaTKdT6WQum0xnpqaT2XRcWVfURCqdy05mctlMJjWdSU7lNuPKU8dtejI1ncvezqVAOJn9aDqV2fwPUarOpg
### 플로우 차트
### 클래스 다이어그램
### 시퀀스 다이어그램

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
