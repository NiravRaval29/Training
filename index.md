<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Demo</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css">
<style>
body {
    float: left;
    width: 100%;
    /*background: url(./image/test.jpg);*/
    background-color: #f1f1f1;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
    margin: 0px;
    display: block;
    overflow-x: hidden;
}
.outer {
	margin: 120px auto 2%;
    display: block;
    width: 80%;
    padding: 2%;
    background: rgba(255,255,255,0.7);
    min-height: 738px;
    position: relative;
    background-color: #fff;
    box-shadow:0 8px 16px 0 rgba(0,0,0,0.2),0 6px 20px 0 rgba(0,0,0,0.19);
}
.inner {
    height: 200px;
    width: 200px;
    display: block;
    position: absolute;
    top: -100px;
    left: 50%;
	-ms-transform: translateX(-50%);
    -webkit-transform: translateX(-50%);
    transform: translateX(-50%);
}
.inner img {
    max-width: 100%;
    display: block;
    border-radius: 50%;

}
.userName {
    /*border : 3px solid red;*/
    margin-top: 70px;
    font-style: oblique;
}

.card1 {
    padding : 3%;
}

.sub-card-heading {
    margin: 5px auto 2%;
    color: #636369;
    font-family: Verdana, Geneva, sans-serif;

}

.sub-card-box {
    margin: 20px auto 2%;
    display: block;
   /* width: 80%;*/
    padding: 2%;
    background: rgba(255,255,255,0.7);
    min-height: auto;
    position: relative;
    background-color: #fff;
    box-shadow:0 8px 16px 0 rgba(0,0,0,0.2),0 6px 20px 0 rgba(0,0,0,0.19);
}
.sub-card-detail {
    /*margin : 15px;*/
    padding-left: 0px;
   /*line-height:25px;*/
}
.sub-card-image{
    padding: 2px;
}
.card2-half{
    
    padding: 2%;
    
}
.card-box-half {
   
    /*width: 50%;*/
   /* width: 80%;*/
   /*display: inline-block;*/

    padding: 2%;
    background: rgba(255,255,255,0.7);
    min-height: auto;
    position: relative;
    background-color: #fff;
    box-shadow:0 8px 16px 0 rgba(0,0,0,0.2),0 6px 20px 0 rgba(0,0,0,0.19);
}

/*added */
.progress1{
    width: 150px;
    height: 150px;
    line-height: 150px;
    background: none;
    margin: 0 auto;
    box-shadow: none;
    position: relative;
}
.progress1:after{
    content: "";
    width: 100%;
    height: 100%;
    border-radius: 50%;
    border: 12px solid #fff;
    position: absolute;
    top: 0;
    left: 0;
}
.progress1 > span{
    width: 50%;
    height: 100%;
    overflow: hidden;
    position: absolute;
    top: 0;
    z-index: 1;
}
.progress1 .progress1-left{
    left: 0;
}
.progress1 .progress1-bar{
    width: 100%;
    height: 100%;
    background: none;
    border-width: 12px;
    border-style: solid;
    position: absolute;
    top: 0;
}
.progress1 .progress1-left .progress1-bar{
    left: 100%;
    border-top-right-radius: 80px;
    border-bottom-right-radius: 80px;
    border-left: 0;
    -webkit-transform-origin: center left;
    transform-origin: center left;
}
.progress1 .progress1-right{
    right: 0;
}
.progress1 .progress1-right .progress1-bar{
    left: -100%;
    border-top-left-radius: 80px;
    border-bottom-left-radius: 80px;
    border-right: 0;
    -webkit-transform-origin: center right;
    transform-origin: center right;
    animation: loading-1 1.8s linear forwards;
}
.progress1 .progress1-value{
    width: 90%;
    height: 90%;
    border-radius: 50%;
    background: #44484b;
    font-size: 24px;
    color: #fff;
    line-height: 135px;
    text-align: center;
    position: absolute;
    top: 5%;
    left: 5%;
}
.progress1.blue .progress1-bar{
    border-color: #049dff;
}
.progress1.blue .progress1-left .progress1-bar{
    animation: loading-2 1.5s linear forwards 1.8s;
}
.progress1.yellow .progress1-bar{
    border-color: #fdba04;
}
.progress1.yellow .progress1-left .progress1-bar{
    animation: loading-3 1s linear forwards 1.8s;
}
.progress1.pink .progress1-bar{
    border-color: #ed687c;
}
.progress1.pink .progress1-left .progress1-bar{
    animation: loading-4 0.4s linear forwards 1.8s;
}
.progress1.green .progress1-bar{
    border-color: #1abc9c;
}
.progress1.green .progress1-left .progress1-bar{
    animation: loading-5 1.2s linear forwards 1.8s;
}
@keyframes loading-1{
    0%{
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg);
    }
    100%{
        -webkit-transform: rotate(180deg);
        transform: rotate(180deg);
    }
}
@keyframes loading-2{
    0%{
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg);
    }
    100%{
        -webkit-transform: rotate(144deg);
        transform: rotate(144deg);
    }
}
@keyframes loading-3{
    0%{
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg);
    }
    100%{
        -webkit-transform: rotate(90deg);
        transform: rotate(90deg);
    }
}
@keyframes loading-4{
    0%{
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg);
    }
    100%{
        -webkit-transform: rotate(36deg);
        transform: rotate(36deg);
    }
}
@keyframes loading-5{
    0%{
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg);
    }
    100%{
        -webkit-transform: rotate(126deg);
        transform: rotate(126deg);
    }
}
@media only screen and (max-width: 990px){
    .progress1{ margin-bottom: 20px; }
}
.profileImage {
    /*border: 2px solid;*/
    box-shadow:0 8px 16px 0 rgba(0,0,0,0.2),0 6px 20px 0 rgba(0,0,0,0.19);
}

</style>
</head>

<body>
<div class="outer">
	<div class="inner"><img src="./image/niravProfile1.jpg" alt="user" class="profileImage" /></div>
    
    <div class="userName">
        <center><h1>Nirav Raval </h1></center>
    </div>
    <div class="card1">
        <div class="sub-card-heading">
            <H3>PERSONAL INFO & CONTACT</H3>
        </div>
        <div class="sub-card-box">
            <div class="sub-card-detail">
                <div class="row">
                    <div class="col-md-6">
                        <div class="col-md-3">
                            <img src="./image/location.png" width="30px" height="30px" align="left" class="sub-card-image">
                        </div>
                        <div class="col-md-9">
                           <p style="padding-left: 40px !important; "><small>C.G ROAD, NEAR LAW GARDER, AHMEDABAD 380009</small></p>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="col-md-3">
                            <img src="./image/call.ico" width="30px" height="30px" align="left" class="sub-card-image">
                        </div>
                        <div class="col-md-9">
                            <p style="padding-left: 40px !important; ">9408549600</p>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-6">
                        <div class="col-md-3">
                            <img src="./image/email.png" width="30px" height="30px" align="left" class="sub-card-image">
                        </div>
                        <div class="col-md-9">
                           <p style="padding-left: 40px !important; ">nirav.raval@devitpl.com</p>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="col-md-3">
                            <img src="./image/blogger.png" width="30px" height="30px" align="left" class="sub-card-image">
                        </div>
                         <div class="col-md-9">
                            <p style="padding-left: 40px !important;"><a  href="http://niravravalblogs.blogspot.com/" style="color: #000 !important; text-decoration: none;">niravravalblogs</a></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="card1">
        <div class="sub-card-heading">
            <H3>EDUCATION</H3>
        </div>
        <div class="sub-card-box">
            <div class="sub-card-detail">
                <div class="row" >
                    <div class="col-md-4">
                        <div class="col-md-12">
                            <h3 style="color: #636369;">SCHOOL</h3>
                            
                            <img src="./image/school.png" width="30px" height="30px" align="left" class="sub-card-image">
                            <p style="padding-left: 40px !important; ">L.D.Muni High School</p>
                            <img src="./image/location.png" width="30px" height="30px" align="left" class="sub-card-image"><p style="padding-left: 40px !important; ">Shihor, Bhavnagar</p>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="col-md-12">
                            <h3 style="color: #636369;">UNIVERSITY(BCA)</h3>
                             <img src="./image/college.png" width="30px" height="30px" align="left" class="sub-card-image"><p style="padding-left: 40px !important; ">C.O.Jani Bca College</p>
                            <img src="./image/location.png" width="30px" height="30px" align="left" class="sub-card-image"><p style="padding-left: 40px !important; ">Shihor, Bhavnagar</p>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="col-md-12">
                            <h3 style="color: #636369;">UNIVERSITY(MCA)</h3>
                            <img src="./image/college.png" width="30px" height="30px" align="left" class="sub-card-image"><p style="padding-left: 40px !important; ">GLS University</p>
                            <img src="./image/location.png" width="30px" height="30px" align="left" class="sub-card-image"><p style="padding-left: 40px !important; ">AHMEDABAD, GUJARAT</p>
                        </div>
                    </div>
                </div>
               
            </div>
        </div>
    </div>

    <div class="card1">
        <div class="sub-card-heading">
            <H3>WORK EXPERIENCE</H3>
        </div>
        <div class="sub-card-box">
            <div class="sub-card-detail">
                <div class="row" >
                    <div class="col-md-4">
                        <div class="col-md-12">
                            <h3 style="color: #636369;">AERONIC</h3>
                            <img src="./image/designation.png" width="30px" height="30px" align="left" class="sub-card-image">
                            <p style="padding-left: 40px !important; ">FRONTEND DEVELOPER</p>
                            <img src="./image/date.png" width="30px" height="30px" align="left" class="sub-card-image"><p style="padding-left: 40px !important; ">01 JAN 2016 - 30 JUL 2016</p>
                        </div>
                    </div>
                     <div class="col-md-4">
                        <div class="col-md-12">
                            <h3 style="color: #636369;">BRIDGE CODE</h3>
                            <img src="./image/designation.png" width="30px" height="30px" align="left" class="sub-card-image">
                            <p style="padding-left: 40px !important; ">ANGULAR DEVELOPER</p>
                            <img src="./image/date.png" width="30px" height="30px" align="left" class="sub-card-image"><p style="padding-left: 40px !important; ">01 AUG 2016 - 2 FEB 2018</p>
                        </div>
                    </div>
                     <div class="col-md-4">
                        <div class="col-md-12">
                            <h3 style="color: #636369;">DEV IT</h3>
                            <img src="./image/designation.png" width="30px" height="30px" align="left" class="sub-card-image">
                            <p style="padding-left: 40px !important; ">PHP/ANGULAR DEVELOPER</p>
                            <img src="./image/date.png" width="30px" height="30px" align="left" class="sub-card-image"><p style="padding-left: 40px !important; ">19 MAY 2018 TO Till </p>
                        </div>
                    </div>
                </div>
               
            </div>
        </div>
    </div>


    <div class="card2-half">
        <div class="sub-card-heading">
            <H3>Skill</H3>
        </div>
        <div class="card-box-half">
            <div class="sub-card-detail">
                    <div class="row" style="padding:2%">
                        <div class="col-md-12 ">

                            <div class="col-md-6" style="float: left;"><img src="./image/dance.png" width="30px" height="30px" align="left" class="sub-card-image"> <p style="padding-left: 40px !important; "> Dancing </p></div>
                            <div class="col-md-6" style="float: left;">
                                <div class="progress">
                                    <div class="progress-bar progress-bar-striped active" role="progressbar" aria-valuenow="99" aria-valuemin="0" aria-valuemax="100" style="width:99%" title="99%">
                                     99%
                                    </div>
                                  </div>
                            </div>
                        </div>
                    </div>

                    <div class="row" style="padding:2%">
                        <div class="col-md-12 ">
                            <div class="col-md-6" style="float: left;"><img src="./image/traveling.jfif" width="30px" height="30px" align="left" class="sub-card-image"><p style="padding-left: 40px !important; ">Traveling </p></div>
                            <div class="col-md-6" style="float: left;">
                                <div class="progress">
                                 <div class="progress-bar progress-bar-striped active" role="progressbar" aria-valuenow="99" aria-valuemin="0" aria-valuemax="100" style="width:85%">85%
                                 </div>
                             </div>
                            </div>
                        </div>
                    </div>

                    <div class="row" style="padding:2%">
                        <div class="col-md-12 ">
                            <div class="col-md-6" style="float: left;"><img src="./image/reading.png" width="30px" height="30px" align="left" class="sub-card-image"><p style="padding-left: 40px !important; ">Reading </p></div>
                            <div class="col-md-6" style="float: left;">
                                <div class="progress">
                                 <div class="progress-bar progress-bar-striped active" role="progressbar" aria-valuenow="70" aria-valuemin="0" aria-valuemax="100" style="width:70%">70%
                                 </div>
                             </div>
                            </div>
                        </div>
                    </div>

                    <div class="row" style="padding:2%">
                        <div class="col-md-12 ">
                            <div class="col-md-6" style="float: left;"><img src="./image/chess.png" width="30px" height="30px" align="left" class="sub-card-image"><p style="padding-left: 40px !important; ">Playing Chess </p></div>
                            <div class="col-md-6" style="float: left;">
                                <div class="progress">
                                    <div class="progress-bar progress-bar-striped active" role="progressbar" aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width:65%">
                                      65%
                                    </div>
                                  </div>
                            </div>
                        </div>
                    </div>    
            </div>
        </div>
    </div>

    <div class="card2-half" >
        <div class="sub-card-heading">
            <H3>LANGUAGE </H3>
        </div>
        <div class="card-box-half">
            <div class="sub-card-detail">
                    <div class="row" style="padding:2%">
                        <div class="col-md-12 ">
                            <div class="col-md-4 " style="float: left;">
                                <div class="col-md-12">
                                    <center><h2>Gujarati</h2></center>
                                </div>
                                <div class="col-md-12">
                                    <div class="progress1 blue">
                                        <span class="progress1-left">
                                            <span class="progress1-bar"></span>
                                        </span>
                                        <span class="progress1-right">
                                            <span class="progress1-bar"></span>
                                        </span>
                                        <div class="progress1-value">90%</div>
                                    </div>    
                                </div>
                            </div>
                            <div class="col-md-4" style="float: left;">
                                <div class="col-md-12">
                                    <center><h2>Hindi</h2></center>
                                </div>
                                <div class="col-md-12">
                                    <div class="progress1 green">
                                        <span class="progress1-left">
                                            <span class="progress1-bar"></span>
                                        </span>
                                        <span class="progress1-right">
                                            <span class="progress1-bar"></span>
                                        </span>
                                        <div class="progress1-value">80%</div>
                                    </div>    
                                </div>
                            </div>
                            <div class="col-md-4" style="float: left;">
                                <div class="col-md-12">
                                    <center><h2>English</h2></center>
                                </div>
                                <div class="col-md-12">
                                    <div class="progress1 yellow">
                                        <span class="progress1-left">
                                            <span class="progress1-bar"></span>
                                        </span>
                                        <span class="progress1-right">
                                            <span class="progress1-bar"></span>
                                        </span>
                                        <div class="progress1-value">60%</div>
                                    </div>    
                                </div>
                            </div>
                        </div>
                    </div>
            </div>
        </div>
    </div>
</div>
</body>
</html>
