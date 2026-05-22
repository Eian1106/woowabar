# woowabar

우아한테크코스 링크와 캘린더를 macOS 상단바에서 바로 확인하는 메뉴바 앱입니다.
<img width="175" height="31" alt="image" src="https://github.com/user-attachments/assets/b294ecd3-7512-42cc-ad0f-ef13dea0ab3c" />


## 설치 및 실행

1. GitHub에서 `woowabar.dmg`를 다운로드합니다.
2. 다운로드한 `woowabar.dmg`를 더블클릭합니다.
3. 열린 창에서 `woowabar.app`을 `Applications` 폴더로 드래그합니다.
4. 터미널을 열고 아래 명령어를 실행합니다.

```bash
xattr -cr /Applications/woowabar.app
```

5. `/Applications/woowabar.app`을 실행합니다.
6. Dock에는 표시되지 않고, macOS 상단바에 행성 아이콘이 표시됩니다.
7. 상단바 아이콘을 클릭하면 우아한테크코스 링크와 캘린더를 확인할 수 있습니다.

## 실행이 안 될 때

macOS에서 "손상되었기 때문에 열 수 없습니다" 또는 "확인되지 않은 개발자" 경고가 뜨면, `woowabar.app`을 `Applications` 폴더로 옮긴 뒤 아래 명령어를 다시 실행하세요.

```bash
xattr -cr /Applications/woowabar.app
```

그 다음 `/Applications/woowabar.app`을 다시 실행하면 됩니다.

## 요구 사항

- macOS 13 Ventura 이상
- Intel Mac, Apple Silicon Mac 모두 지원
