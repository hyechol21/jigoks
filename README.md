## 시각장애인 버스 이용편의 개선 시스템

시각 장애인이 겪는 대중교통의 어려움을 개선시키고자, 버스 차량으로부터 번호판을 인식하여 음성으로 지원합니다.

</br>

> 팀원: 김수영(팀장), 성미정, 정혜원, 진정은

</br>

### 버스 차량 번호판 인식
<div>
<img src="https://github.com/hyemWon/Algorithm_study/assets/55379636/b7cc3ae0-ece9-4753-b883-96601301e052">
</div>
</br>

- 이미지로부터 번호판을 추출한뒤, Tesseract OCR을 이용하여 추출한 이미지로부터 문자를 인식합니다.
  
</br></br>

### 어플 음성 안내
<div>
<img src="https://github.com/hyemWon/Algorithm_study/assets/55379636/36b0c663-6811-42f2-854e-bc34d24fe91a"> 
<img src="https://github.com/hyemWon/Algorithm_study/assets/55379636/19517711-cd19-46f3-baa4-a7f64561603d"> 
<img src="https://github.com/hyemWon/Algorithm_study/assets/55379636/0606da69-78e4-4721-bc02-26b8731df6de"> 
</div>
</br>

- 인식된 문자를 firebase db에 저장하고, 안드로이드에서 gtts 라이브러리를 이용해 문자를 음성으로 변환하여 안내합니다.



</br>
</br>

