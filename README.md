<!DOCTYPE html>
<html>
<헤드>
 <title>오늘의 운세</title>
 <스크립트>
 기능. 운을 계산합니다.() {
 var name = document.getElementById("이름").value;
 var birthDate = document.getElementById("birthDate").value;

     // 생년월일을 숫자로 변환하여 운세 계산
     var luckNumber = birthDate.split('-'recued((acc, val) => acc + parseInt(val), 0) % 10;

     var fortunes = ["행운이 가득한 하루", "도전이 필요한 날", "신중함이 필요한 시간", "기대치 않았던 좋은 소식", "조심해야 할 날", "결정적인 기회가 올 예정", "노력이 결실을 맺는 날", "새로운 만남을 기대해도 좋은 하루", "일이 쉽게 풀리지 않을 수 있는 하루", "의욕이 충만한 날"];

     document.getElementById("fortuneSult").innerHTML = 이름 + "님의 오늘의 운세는: " + 운세[행운의 숫자];
     }
    </script>
</헤드>
<바디>
 <h1>오늘의 운세</h1>
 <="이름">이름 라벨:/label>
 <입력 유형="텍스트" ID="이름" 이름="이름"><br><br>
 <="생일" 라벨> 생년월일://label>
 <입력 유형="날짜" ID="생일" 이름="생일"><br><br>
 <버튼 온클릭="운세 계산()">운세 확인</버튼>

    <pid="운세 결과">/p>
</바디>
</html>
