<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>แบบสอบถาม</title>
<h2>แบบสอบถาม</h2>
<style>
body {
font-family: Arial, sans-serif;
margin: 20px;
background-color: #f3f3f3;
}
.container {
border: 1px solid #000000;
padding: 20px;
max-width: 600px;
background-color: #f1ddb8;
margin: 0 auto;
} 
h2 {
text-align: center;
}
hr {
border: 1px solid #000;
}
.form-group {
margin-bottom: 15px;
}
/* .form-group label {
display: flex;
margin-bottom: 5px;
}*/
.form-inline {
display: flex;
flex-wrap: wrap;
gap: 10px;
}
select {
width: 100%;
}
.form-inline label {
margin-left: 5px;
}
</style>
</head>
<body>
<div class="container">
<hr>
<form action="#" method="post">
<label for="name"><b>ข้อมูลผู้ตอบแบบสอบถาม</b></label>
<!-- ชื่อ-นามสกุล -->
<div class="form-group">
<label for="name"><b>ชื่อ-นามสกุล:</b></label>
<input tag type="text" id="name" name="name" style="width: 81%;">
</div>

<div class="form-group">
<label for="student-id"><b>รหัสนักศึกษา:</b></label>
<input type="text" id="student-id" name="student-id" style="width: 80%;">
</div>

<div class="form-group">
<label><b>เพศ:</b></label>
<div class="form-inline">
<input type="radio" id="male" name="gender" value="male">
<label for="male">ชาย</label>
<input type="radio" id="female" name="gender" value="female">
<label for="female">หญิง</label>
</div>
</div>

<div class="form-group">
<label for="faculty"><b>สังกัดคณะ:</b></label>
<select id="faculty" name="faculty" size="11">
<option value="science">วิทยาศาสตร์</option>
<option value="engineering">วิทยาการคอมพิวเตอร์</option>
<option value="engineering">ครุศาสตร์</option>
<option value="business">บริหารธุรกิจและการจัดการ</option>
<option value="humanities">มนุษยศาสตร์</option>
<option value="ict">เทคโนโลยีอุตสาหกรรม</option>
<option value="medicine">เกษตรศาสตร์</option>
<option value="engineering">พยาบาลศาสคร์</option>
<option value="engineering">สาธารณสุขศาสตร์</option>
<option value="engineering">แพทย์แผนไทยและทางเลือก</option>
<option value="engineering">นิติศาสตร์</option>
</select>
</div>

<div class="form-group">
<label><b>แม่สีที่ชอบ:</b></label>
<div class="form-inline">
<input type="checkbox" id="red" name="favorite_color" value="red">
<label for="red">สีแดง</label>
<input type="checkbox" id="blue" name="favorite_color" value="blue">
<label for="blue">สีเขียว</label>
<input type="checkbox" id="green" name="favorite_color" value="green">
<label for="green">สีน้ำเงิน</label>
</div>
</div>

<div class="form-group">
<label><b>ผลไม้ที่ชอบ:</b></label>
<div class="form-inline">
<input type="checkbox" id="mango" name="favorite_fruit" value="mango">
<label for="mango">มะม่วง</label>
<input type="checkbox" id="orange" name="favorite_fruit" value="orange">
<label for="orange">มะพร้าว</label>
<input type="checkbox" id="banana" name="favorite_fruit" value="banana">
<label for="banana">ทุเรียน</label>
<input type="checkbox" id="grap" name="favorite_fruit" value="grape">
<label for="grap">ลำใย</label>
<input type="checkbox" id="grae" name="favorite_fruit" value="grape">
<label for="grae">ฝรั่ง</label>
<input type="checkbox" id="grpe" name="favorite_fruit" value="grape">
<label for="grpe">แตงโม</label>
</div>
</div>

<div class="form-group">
<label><b>อาหารที่ชื่นชอบ:</b></label>
<div class="form-inline">
<input type="checkbox" id="spicy" name="favorite_food" value="spicy">
<label for="spicy">ต้มยำกุ้ง</label>
<input type="checkbox" id="fried" name="favorite_food" value="fried">
<label for="fried">ไข่เจียวหมูสับ</label>
<input type="checkbox" id="papaya" name="favorite_food" value="papaya">
<label for="papaya">ข้าวมันไก่</label>
<input type="checkbox" id="thai_curry" name="favorite_food" value="thai_curry">
<label for="thai_curry">กะเพรา</label>
<input type="checkbox" id="thai_curr" name="favorite_food" value="thai_curry">
<label for="thai_curr">ผัดไทย</label>
<input type="checkbox" id="thai_urry" name="favorite_food" value="thai_curry">
<label for="thai_urry">ราดหน้าหมี่กรอบ</label>
</div>
</div>

<div class="form-group" style="text-align: center;">
<button type="submit">บันทึก</button>
</div>
</form>
</div>
</body>
</html>

