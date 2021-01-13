UI CREATE


test1
test2

셀렉트 박스 : {
	jquery fn 을 이용해서 제작
	최초 이벤트 삽입
	기본적인 디자인 CSS 필요
	radio를 이용한 구성

	기능 : {
		동적 생성된 객체를 위해 클릭시 셋팅값이 없을 경우 설정 기능 실행
		동적으로 옵션 추가 함수 제공
		동적으로 옵션 추가시 셋팅값 체크 후 없으면 설정 실행 후 리프레시 함수 실행
		클릭, 포커스 오픈
		오픈시 리스트에 on된 객체 확인 후 on 처리
		클릭 및 체인지 이벤트 발생
		코드 축소를 위한 초기 리스팅 코드 : {

			<div data-init="init">
				<a href='#'>선택3</a>
				<ul>
					<li><label><input type="radio" name="radio" value="선택1">선택1</label></li>
					<li><label><input type="radio" name="radio" value="선택2">선택2</label></li>
					<li class="on"><label><input type="radio" name="radio" value="선택3" checked="checked">선택3</label></li>
					<li><label><input type="radio" name="radio" value="선택4">선택4</label></li>
					<li><label><input type="radio" name="radio" value="선택5">선택5</label></li>
					<li><label><input type="radio" name="radio" value="선택6">선택6</label></li>
					<li><label><input type="radio" name="radio" value="선택7">선택7</label></li>
					<li><label><input type="radio" name="radio" value="선택8">선택8</label></li>
					<li><label><input type="radio" name="radio" value="선택9">선택9</label></li>
					<li><label><input type="radio" name="radio" value="선택10">선택10</label></li>
				</ul>
			</div>

		}
	}
}


객제.함수();
객체.add({value:1,txt:선택11}); //add 함수 실행시 셋팅값 체크, 없으면 셋팅실행
객체.select({value:1}); //select 함수 실행시 셋팅값 체크, 없으면 셋팅실행
test1
test2
test3
TEMP
