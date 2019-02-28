---
layout: post
title:  "[JQuery] Using CheckBox"
date:   2019-02-25
categories: jjlee update
---

sample post

~~~
<!doctype html>
<html lang="ko">
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script>
// name으로 제어

//	$('[name=chk]').prop("checked", true);				// name으로 전체체크
//	$('[name=chk]').prop("checked", false);				// name으로 전체해제
//  $('[name=chk]').eq(0).prop("checked");				// 해당index(0)의 checked여부 확인
//  $('[name=chk]').eq(0).prop("checked", "checked");	// 해당index(0) checked

// id로 값 가져오기
//	$('#chk1').prop("checked"); // id로 체크여부 가져오기

</script>
  <title>Document</title>
</head>
<body>
	
	[name=chk]
	<input type="checkbox" name="chk" id="chk1">chk1
	<input type="checkbox" name="chk" id="chk2">chk2
	<input type="checkbox" name="chk" id="chk3">chk3
	<input type="checkbox" name="chk" id="chk4">chk4
	<input type="checkbox" name="chk" id="chk5">chk5
	<br>
	<br>
	[name=chk2]
	<input type="checkbox" name="chk2" id="chk21">chk21
	<input type="checkbox" name="chk2" id="chk22">chk22
	<input type="checkbox" name="chk2" id="chk23">chk23
	<input type="checkbox" name="chk2" id="chk24">chk24
	<input type="checkbox" name="chk2" id="chk25">chk25
	
</body>
</html>

~~~

* attr을 사용하는 경우 index값으로 checked값을 가져올때 undefined로 넘어와서 prop로 처리.
* attr로도 checked값을 set하는데에는 문제가 없는데 왜 위 경우에서 안되는지 모르겠음.

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
