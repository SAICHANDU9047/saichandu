{% load static %}

<!DOCTYPE html>

<html lang="en">

<head>

<title>IRIS BASED RECOGNITION SYSTEM</title>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1">

<!--

================================================================

===============================-->

<link rel="icon" type="image/png" href="{% static 'mages/icons/favicon.ico' %}"/>

<!--

================================================================
===============================-->

<link	rel="stylesheet"	type="text/css"	href="{%	static 'vendor/bootstrap/css/bootstrap.min.css' %}">
<!--

================================================================

===============================-->
 
<link rel="stylesheet" type="text/css" href="{% static 'fonts/font-awesome-4.7.0/css/font- awesome.min.css' %}">
<!--

================================================================

===============================-->

<link rel="stylesheet" type="text/css" href="{% static 'fonts/Linearicons-Free-v1.0.0/icon- font.min.css' %}">
<!--

================================================================

===============================-->

<link rel="stylesheet" type="text/css" href="{% static 'vendor/animate/animate.css' %}">

<!--

================================================================

===============================-->

<link	rel="stylesheet"	type="text/css"	href="{%	static	'vendor/css- hamburgers/hamburgers.min.css' %}">
<!--
================================================================

===============================-->

<link	rel="stylesheet"	type="text/css"	href="{%	static 'vendor/animsition/css/animsition.min.css' %}">
 
<!--

================================================================

===============================-->

<link rel="stylesheet" type="text/css" href="{% static 'vendor/select2/select2.min.css'

%}">

<!--

================================================================

===============================-->

<link	rel="stylesheet"	type="text/css"	href="{%	static 'vendor/daterangepicker/daterangepicker.css' %}">
<!--

================================================================

===============================-->

<link rel="stylesheet" type="text/css" href="{% static 'css/util.css' %}">

<link rel="stylesheet" type="text/css" href="{% static 'css/main.css' %}">

<!--
================================================================
===============================-->

</head>

<body style="background-color: #666666;">



<div class="limiter">

<div class="container-login100">
 
<div class="wrap-login100">

<form action='output' method="POST" enctype="multipart/form- data" class="login100-form validate-form">
{% csrf_token %}

<span class="login100-form-title p-b-43">

<p><font  size="5"  color="#00ff00">Upload  the

image </font></p>

</span>





<div class="wrap-input100 validate-input" data-validate = "Valid email is required: ex@abc.xyz">
<input class="input100" type="file" name="file">

<span class="focus-input100"></span>

<span class="label-input100">Image</span>

</div>





<div	class="wrap-input100	validate-input"	data- validate="Password is required">
<select class="input100" name="algo">

<option value='cnn'>CNN</option>

<option value='mobilenet'>MOBILENET</option>
 
<!-- <option value='resnet50'>ResNet50</option> --

>

<!-- <option value='svm'>Linear SVM</option> -->

</select>



</div>



<div class="flex-sb-m w-full p-t-3 p-b-32">

<div class="contact100-form-checkbox">







</label>

</div>



<div>
<a href="#" class="txt1">



</a>

</div>

</div>
 
<div class="container-login100-form-btn">

<button class="login100-form-btn"> Predict
</button>

</div>



<div class="text-center p-t-46 p-b-20">

<span class="txt2">



</span>

</div>

<!--

<div class="login100-form-social flex-c-m">

<a href="#" class="login100-form-social-item flex-

c-m bg1 m-r-5">

<i	class="fa	fa-facebook-f"	aria-
hidden="true"></i>
</a>



<a href="#" class="login100-form-social-item flex-

c-m bg2 m-r-5">

<i	class="fa	fa-twitter"	aria-

hidden="true"></i>
 
</a>

</div>

-->

</form>



<div class="login100-more" style="background-image: url({% static 'images/02.jpg' %});">
</div>

</div>

</div>

</div>











<!--
================================================================

===============================-->

<script src="{% static 'vendor/jquery/jquery-3.2.1.min.js' %}"></script>

<!--

================================================================

===============================-->
 
<script src="{% static 'vendor/animsition/js/animsition.min.js' %}"></script>

<!--

================================================================

===============================-->

<script src="{% static 'vendor/bootstrap/js/popper.js' %}"></script>

<script src="{% static 'vendor/bootstrap/js/bootstrap.min.js' %}"></script>

<!--

================================================================

===============================-->

<script src="{% static 'vendor/select2/select2.min.js' %}"></script>

<!--

================================================================

===============================-->

<script src="{% static 'vendor/daterangepicker/moment.min.js' %}"></script>

<script src="{% static 'vendor/daterangepicker/daterangepicker.js' %}"></script>

<!--
================================================================
===============================-->

<script src="{% static 'vendor/countdowntime/countdowntime.js' %}"></script>

<!--

================================================================

===============================-->

<script src="{% static 'js/main.js' %}"></script>
 
</body>

</html>


