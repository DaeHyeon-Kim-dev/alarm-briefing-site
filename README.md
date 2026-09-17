# 알람 브리핑 · 공개 페이지

iOS 앱 **알람 브리핑**의 개인정보 처리방침과 지원 페이지입니다.

- [개인정보 처리방침](https://daehyeon-kim-dev.github.io/alarm-briefing-site/privacy.html)
- [지원](https://daehyeon-kim-dev.github.io/alarm-briefing-site/support.html)

## 고칠 때

**이 저장소를 직접 고치지 않습니다.** 원본은 앱 저장소의 `ship/legal/` 에 있고,
개인정보 처리방침은 `answers-ko.json` 을 고쳐 다시 렌더링합니다.

```bash
# 앱 저장소에서
python3 ~/.claude/skills/privacy-policy/scripts/render.py \
  ship/legal/answers-ko.json -o ship/legal/privacy.html
# 그 뒤 이 저장소로 복사해 푸시
```

앱이 무엇을 수집하는지 바뀌면 **방침과 App Store 의 App Privacy 답변을 함께** 고쳐야 합니다.
둘이 어긋나면 심사에서 걸립니다.
