# EP1 메소포타미아 — Google Flow 이미지 프롬프트

카드뉴스 8장용. 문구는 `01-mesopotamia.md`의 표를 따른다.

## 작업 요령
- **글자는 이미지에 넣지 말 것.** AI 이미지는 한글·숫자 렌더링이 자주 깨진다. 프롬프트에 `no text`를 넣어 생성하고, 제목·본문은 Canva 등에서 얹는다.
- **비율:** Flow에서 세로 3:4로 생성하고, 인스타 규격(1080×1350, 4:5)으로 위아래를 살짝 크롭한다. 제목이 들어갈 위쪽 30%는 비워 두도록 프롬프트에 넣었다.
- **일관성:** 모든 장에 아래 **공통 스타일 블록**을 그대로 붙인다. 첫 장이 마음에 들면 그 이미지를 참조 이미지로 올려 나머지를 생성하면 톤이 맞는다.
- 실제 유물 사진(YBC 7289 등)은 AI가 정확히 재현하지 못한다. 6장은 "유물을 닮은 일러스트"로 만들고, 정확성이 필요하면 예일대·대영박물관의 공개 이미지로 교체한다.

## 공통 스타일 블록 (모든 프롬프트 끝에 붙이기)
```
Flat editorial illustration with subtle clay and paper texture, warm earthy palette of terracotta, sand beige, deep indigo and muted gold, soft lighting, clean composition, generous empty space at the top third for a title, vertical 3:4, no text, no letters, no numbers, no watermark
```

## 장별 프롬프트

**1장 · 1시간은 왜 60분일까?**
```
A close-up of a vintage analog wristwatch lying on a sandy clay surface, ancient clay tablet fragment blurred in the background, curious and mysterious mood, [공통 스타일 블록]
```

**2장 · 점토판에 새긴 수학**
```
A hand-sized ancient Mesopotamian clay tablet covered with abstract wedge-shaped cuneiform-like marks, resting on a woven mat, a reed stylus beside it, warm side light, [공통 스타일 블록]
```

**3장 · 10이 아니라 60**
```
An abstract diagram-style illustration of sixty small clay tokens arranged in a neat grid of ten columns and six rows, one group highlighted in gold, calm and orderly, [공통 스타일 블록]
```

**4장 · 왜 하필 60?**
```
Sixty clay tokens being split into equal groups: halves, thirds, quarters, fifths and sixths shown side by side as tidy colored clusters, simple infographic feeling, [공통 스타일 블록]
```

**5장 · 어디에 썼을까**
```
Ancient Mesopotamian scribe sitting cross-legged writing on a clay tablet, behind him workers measuring a field and digging a canal, granary sacks in the foreground, wide scene, [공통 스타일 블록]
```

**6장 · √2를 알고 있었다**
```
A round clay tablet with a square drawn on it and its diagonal line crossing the square, small wedge-shaped marks along the lines, shown from slightly above on a dark indigo background, inspired by an ancient Babylonian geometry tablet, [공통 스타일 블록]
```

**7장 · 이자 계산도 했다**
```
Small silver ingots stacked in a doubling pattern: one, two, four, eight, beside a clay tablet and a scribe's hand, golden glow, symbolic of growth over time, [공통 스타일 블록]
```

**8장 · 지금도 쓰고 있다**
```
A modern analog clock face overlapped with a faint circular sundial-like diagram, ancient clay tablet texture fading into the clock, sense of ancient past meeting present, [공통 스타일 블록]
```

## 영상(숏폼)용 장면 아이디어
영상도 Flow(Veo)로 만들 경우 위 프롬프트의 이미지를 첫 프레임으로 쓰고, 동작만 짧게 추가한다.
- 1장: `slow push-in on the wristwatch, dust particles floating, ticking motion of the second hand`
- 5장: `scribe writes on the tablet, workers slowly move in the background, gentle camera drift`
- 8장: `the clay texture dissolves into the clock face, hands of the clock move smoothly`
