# 🕰️ Steins;Gate Divergence & Flip Clock

비쥬얼노벨 게임 **<슈타인즈 게이트(Steins;Gate)>** 의 감성을 담은 웹 기반 디지털 시계 프로젝트입니다. 상단에는 세계선 변동률을 나타내는 다이버전스 미터기(닉시관)를, 하단에는 타임 리프를 연상시키는 스플릿-플립(Split-Flap) 시계를 구현했습니다.

## 🌐 라이브 데모 (웹에서 바로 보기)
다운로드 없이 아래 링크를 클릭하면 브라우저에서 시계가 바로 작동합니다.
👉 **[슈타인즈 게이트 다이버전스 시계 실행하기](https://clearspecific.github.io/steinsgate-style-clock/steinsgate-style-clock.html)**

## ✨ 주요 기능 (Features)
* **닉시관 다이버전스 미터기**: CSS Glow 효과를 이용해 진공관 특유의 주황색 네온 불빛을 구현했습니다.
* **스플릿-플립 시계 (Split-Flap Clock)**: CSS 3D Transform(`rotateX`) 속성을 활용하여 숫자가 반으로 갈라지며 넘어가는 역동적인 애니메이션을 적용했습니다. (월/일/요일/시/분/초 지원)
* **세계선 변동 애니메이션 (리딩 슈타이너 효과)**: 
  * 상단의 다이버전스 미터기를 **클릭**하면 숫자가 무작위로 회전하며 새로운 세계선(난수)으로 이동합니다.
  * 매 1분이 넘어가는 정각(00초)마다 자동으로 세계선 변동 애니메이션이 실행됩니다.
* **OS 시간 강제 동기화**: `setTimeout`과 `setInterval`을 조합하여 브라우저와 운영체제(OS) 시계 간의 1초(밀리초) 오차를 완벽하게 보정했습니다.

## 🛠️ 기술 스택 (Tech Stack)
* **HTML5** : 시계의 레이아웃 및 뼈대 구성
* **CSS3** : 3D 애니메이션, 그림자 효과(Box/Text Shadow)를 활용한 입체감 구현
* **JavaScript (Vanilla JS)** : 실시간 시간 동기화, 난수 생성 로직, DOM 조작 애니메이션 제어

## 🚀 실행 방법 (How to Run)
1. 이 저장소의 코드를 다운로드합니다.
2. 폴더 내의 `steinsgate-style-clock.html` 파일을 웹 브라우저(Chrome, Safari 등)로 엽니다.
3. 별도의 서버 구축이나 설치 없이 즉시 작동합니다.

## 📝 개발자 노트 (Developer's Note)
* 본 프로젝트는 프론트엔드(HTML/CSS/JS) 기술의 원리를 학습하기 위해 기획된 미니 프로젝트입니다.
* UI 레이아웃 설계 및 자바스크립트 애니메이션 로직은 AI(Gemini)와의 **페어 프로그래밍(Pair Programming)** 을 통해 학습하며 작성했습니다. 
* 이것은 슈타인즈 게이트의 선택이다. 엘 프사이 콩그루!

---

# 🕰️ Steins;Gate Divergence & Flip Clock (English)

A web-based digital clock project capturing the essence of the visual novel game **Steins;Gate**. The top section features a Divergence Meter (Nixie tube) representing the worldline divergence ratio, while the bottom section features a Split-Flap clock reminiscent of time leaping.

## 🌐 Live Demo
Click the link below to see the clock in action directly in your browser!
👉 **[Run Steins;Gate Divergence Clock](https://clearspecific.github.io/steinsgate-style-clock/steinsgate-style-clock.html)**

## ✨ Key Features
* **Nixie Tube Divergence Meter**: Implemented the signature orange neon glow of vacuum tubes using CSS Glow effects.
* **Split-Flap Clock**: Applied dynamic animations where numbers split and flip over using CSS 3D Transform (`rotateX`). (Supports Month / Date / Day / Hour / Minute / Second)
* **Worldline Shift Animation (Reading Steiner Effect)**: 
  * **Clicking** the Divergence Meter randomly rotates the numbers, shifting to a new worldline (random number generation).
  * Automatically triggers the worldline shift animation at the top of every minute (00 seconds).
* **OS Time Forced Synchronization**: Flawlessly compensated for the 1-second (millisecond) delay between the browser and the operating system (OS) clock by combining `setTimeout` and `setInterval`.

## 🛠️ Tech Stack
* **HTML5** : Structuring the clock layout and skeleton.
* **CSS3** : Implementing 3D animations and depth using Box/Text Shadow effects.
* **JavaScript (Vanilla JS)** : Real-time clock synchronization, random number generation logic, and DOM manipulation for animation control.

## 🚀 How to Run
1. Download or clone this repository.
2. Open the `steinsgate-style-clock.html` file in any web browser (Chrome, Safari, etc.).
3. It works instantly without any additional server setup or installation.

## 📝 Developer's Note
* This mini-project was designed to learn the fundamentals of frontend development (HTML/CSS/JS).
* The UI layout design and JavaScript animation logic were written while learning through **Pair Programming** with AI (Gemini).

* This is the choice of Steins;Gate. El Psy Kongroo!
