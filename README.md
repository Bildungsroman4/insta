# 
@import url('https://fonts.googleapis.com/css?family=Roboto&display=swap');

*{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	outline: none;
	list-style: none;
	text-decoration: none;
	font-family: 'Roboto', sans-serif;
}

body{
	background: #fafafa;
	font-size: 14px;
}

.wrapper .header{
	max-width: 350px;
	width: 100%;
	height: auto;
	margin: 50px auto;
}

.wrapper .header .top,
.wrapper .signup{
	background: #fff;
    border: 1px solid #e6e6e6;
    border-radius: 1px;
    padding: 40px 40px 20px;
}

.wrapper .header .logo img{
	display: block;
	margin: 0 auto 35px;
}

.wrapper .header .form .input_field{
	margin-bottom: 5px;
}

.wrapper .header .form .input_field .input{
	width: 100%;
	background: #fafafa;
	border: 1px solid #efefef;
	font-size: 12px;
	border-radius: 3px;
	color: #262626;
	padding: 10px;
}

.wrapper .header .form .input_field .input:focus{
	border: 1px solid #b2b2b2;
}

.wrapper .header .form .btn{
	margin: 10px 0;
	background-color: #3897f0;
    border: 1px solid #3897f0;
    border-radius: 4px;
    text-align: center;
    padding: 5px;
}

.wrapper .header .form .btn a{
	color: #fff;
	display: block;
}

.wrapper .header .or{
	display: flex;
	justify-content: space-between;
	align-items: center;
	height: 15px;
	margin: 15px 0 20px;
}

.wrapper .header .or .line{
	width: 105px;
	height: 2px;
	background: #efefef
}

.wrapper .header .or p{
	color: #999;
	font-size: 12px;
}

.wrapper .dif .fb{
	display: flex;
	justify-content: center;
	align-items: center;
}

.wrapper .dif .fb img{
	width: 16px;
	height: 16px;
}

.wrapper .dif  .fb p{
	color: #385185;
	font-weight: 500;
	margin-left: 10px;
}

.wrapper .dif .forgot{
	font-size: 12px;
	text-align: center;
	margin-top: 20px;
}

.wrapper .dif .forgot a{
	color: #003569;
}

.wrapper .signup{
	margin: 10px 0 20px;
	padding: 25px 40px;
	text-align: center;
	color: #262626;
}

.wrapper .signup a{
	color: #3897f0;
}

.wrapper .apps{
	text-align: center;
	color: #262626;
}

.wrapper .apps p{
	margin-bottom: 20px;
}

.wrapper .apps a img{
	width: 135px;
	height: 40px;
	margin: 0 5px;
}

.footer{
	max-width: 935px;
	width: 100%;
	margin: 0 auto;
	padding: 40px 0;
	display: flex;
	justify-content: space-between;
}

.footer .links ul li{
	display: inline-block;
	margin-right: 10px;
}

.footer .links ul li a{
	color: #003569;
	font-size: 12px;
}

.footer .copyright{
	color: #999;	
}
