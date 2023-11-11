<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Leaf's Site</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Tilt+Neon&display=swap" rel="stylesheet">

	<style>
		zx {
			
		}
		body {
			align-content: center;
			overflow: hidden;
		}
		h1 {
			text-align: center;
			font-family: "Tilt Neon"
		}
		#dunce {
			 
		}
		.hidden_elements {
    		display:none;
		}

		.open {
  			display:block;
		}
	</style>
	<style>
	/*
* infinite Loader 
*
* Author: Jonathan Silva
* Url: https://portfolio.jonathansilva.com.br
*
*/
/* ----- Base ----- */
/* ----- Loader ----- */

.loader-wrapper {
  width: 148px;
  height: 100px;
  position: absolute;
  margin: -50px 0 0 -74px;
  left: 50%;
  top: 60%;
}

.loader {
  width: 148px;
  height: 100px;
  top: 0;
  left: 0;
  position: absolute;
}
.loader:after {
  content: "";
  top: auto;
  position: absolute;
  display: block;
  animation: shadow 1.2s infinite linear;
  -moz-animation: shadow 1.2s infinite linear;
  bottom: 0em;
  left: 0;
  height: .25em;
  width: 1em;
  border-radius: 50%;
  background-color: #034466;
  opacity: 0.3;
}

.roller,
.roller:last-child {
  width: 70px;
  height: 70px;
  position: absolute;
  top: 0;
  left: 0;
  -webkit-animation: rollercoaster 1.2s infinite linear;
  -webkit-transform: rotate(135deg);
  -moz-animation: rollercoaster 1.2s infinite linear;
  -moz-transform: rotate(135deg);
  animation: rollercoaster 1.2s infinite linear;
  transform: rotate(135deg);
}

.roller:last-child {
  left: auto;
  right: 0;
  -webkit-transform: rotate(-45deg);
  -webkit-animation: rollercoaster2 1.2s infinite linear;
  -moz-transform: rotate(-45deg);
  -moz-animation: rollercoaster2 1.2s infinite linear;
  transform: rotate(-45deg);
  animation: rollercoaster2 1.2s infinite linear;
}

.roller:before,
.roller:last-child:before {
  content: "";
  display: block;
  width: 15px;
  height: 15px;
  background: #000;
  border-radius: 50%;
}

@-webkit-keyframes rollercoaster {
  0% {
    -webkit-transform: rotate(135deg);
  }
  8% {
    -webkit-transform: rotate(240deg);
  }
  20% {
    -webkit-transform: rotate(300deg);
  }
  40% {
    -webkit-transform: rotate(380deg);
  }
  45% {
    -webkit-transform: rotate(440deg);
  }
  50% {
    -webkit-transform: rotate(495deg);
    opacity: 1;
  }
  50.1% {
    -webkit-transform: rotate(495deg);
    opacity: 0;
  }
  100% {
    -webkit-transform: rotate(495deg);
    opacity: 0;
  }
}
@-webkit-keyframes rollercoaster2 {
  0% {
    opacity: 0;
  }
  49.9% {
    opacity: 0;
  }
  50% {
    opacity: 1;
    -webkit-transform: rotate(-45deg);
  }
  58% {
    -webkit-transform: rotate(-160deg);
  }
  70% {
    -webkit-transform: rotate(-240deg);
  }
  80% {
    -webkit-transform: rotate(-300deg);
  }
  90% {
    -webkit-transform: rotate(-340deg);
  }
  100% {
    -webkit-transform: rotate(-405deg);
  }
}
@-webkit-keyframes shadow {
  0% {
    opacity: .3;
    -webkit-transform: translateX(65px) scale(0.5, 0.5);
  }
  8% {
    -webkit-transform: translateX(30px) scale(2, 2);
  }
  13% {
    -webkit-transform: translateX(0px) scale(1.3, 1.3);
  }
  30% {
    -webkit-transform: translateX(-15px) scale(0.5, 0.5);
    opacity: 0.1;
  }
  50% {
    -webkit-transform: translateX(60px) scale(1.2, 1.2);
    opacity: 0.3;
  }
  60% {
    -webkit-transform: translateX(130px) scale(2, 2);
    opacity: 0.05;
  }
  65% {
    -webkit-transform: translateX(145px) scale(1.2, 1.2);
  }
  80% {
    -webkit-transform: translateX(120px) scale(0.5, 0.5);
    opacity: 0.1;
  }
  90% {
    -webkit-transform: translateX(80px) scale(0.8, 0.8);
  }
  100% {
    -webkit-transform: translateX(60px);
    opacity: 0.3;
  }
}
/* Moz */
@-moz-keyframes rollercoaster {
  0% {
    -moz-transform: rotate(135deg);
  }
  8% {
    -moz-transform: rotate(240deg);
  }
  20% {
    -moz-transform: rotate(300deg);
  }
  40% {
    -moz-transform: rotate(380deg);
  }
  45% {
    -moz-transform: rotate(440deg);
  }
  50% {
    -moz-transform: rotate(495deg);
    opacity: 1;
  }
  50.1% {
    -moz-transform: rotate(495deg);
    opacity: 0;
  }
  100% {
    -moz-transform: rotate(495deg);
    opacity: 0;
  }
}
@-moz-keyframes rollercoaster2 {
  0% {
    opacity: 0;
  }
  49.9% {
    opacity: 0;
  }
  50% {
    opacity: 1;
    -moz-transform: rotate(-45deg);
  }
  58% {
    -moz-transform: rotate(-160deg);
  }
  70% {
    -moz-transform: rotate(-240deg);
  }
  80% {
    -moz-transform: rotate(-300deg);
  }
  90% {
    -moz-transform: rotate(-340deg);
  }
  100% {
    -moz-transform: rotate(-405deg);
  }
}
@-moz-keyframes shadow {
  0% {
    opacity: .3;
    -moz-transform: translateX(65px) scale(0.5, 0.5);
  }
  8% {
    -moz-transform: translateX(30px) scale(2, 2);
  }
  13% {
    -moz-transform: translateX(0px) scale(1.3, 1.3);
  }
  30% {
    -moz-transform: translateX(-15px) scale(0.5, 0.5);
    opacity: 0.1;
  }
  50% {
    -moz-transform: translateX(60px) scale(1.2, 1.2);
    opacity: 0.3;
  }
  60% {
    -moz-transform: translateX(130px) scale(2, 2);
    opacity: 0.05;
  }
  65% {
    -moz-transform: translateX(145px) scale(1.2, 1.2);
  }
  80% {
    -moz-transform: translateX(120px) scale(0.5, 0.5);
    opacity: 0.1;
  }
  90% {
    -moz-transform: translateX(80px) scale(0.8, 0.8);
  }
  100% {
    -moz-transform: translateX(60px);
    opacity: 0.3;
  }
}
/* No-prefix */
@keyframes rollercoaster {
  0% {
    transform: rotate(135deg);
  }
  8% {
    transform: rotate(240deg);
  }
  20% {
    transform: rotate(300deg);
  }
  40% {
    transform: rotate(380deg);
  }
  45% {
    transform: rotate(440deg);
  }
  50% {
    transform: rotate(495deg);
    opacity: 1;
  }
  50.1% {
    transform: rotate(495deg);
    opacity: 0;
  }
  100% {
    transform: rotate(495deg);
    opacity: 0;
  }
}
@keyframes rollercoaster2 {
  0% {
    opacity: 0;
  }
  49.9% {
    opacity: 0;
  }
  50% {
    opacity: 1;
    transform: rotate(-45deg);
  }
  58% {
    transform: rotate(-160deg);
  }
  70% {
    transform: rotate(-240deg);
  }
  80% {
    transform: rotate(-300deg);
  }
  90% {
    transform: rotate(-340deg);
  }
  100% {
    transform: rotate(-405deg);
  }
}
@keyframes shadow {
  0% {
    opacity: .3;
    transform: translateX(65px) scale(0.5, 0.5);
  }
  8% {
    transform: translateX(30px) scale(2, 2);
  }
  13% {
    transform: translateX(0px) scale(1.3, 1.3);
  }
  30% {
    transform: translateX(-15px) scale(0.5, 0.5);
    opacity: 0.1;
  }
  50% {
    transform: translateX(60px) scale(1.2, 1.2);
    opacity: 0.3;
  }
  60% {
    transform: translateX(130px) scale(2, 2);
    opacity: 0.05;
  }
  65% {
    transform: translateX(145px) scale(1.2, 1.2);
  }
  80% {
    transform: translateX(120px) scale(0.5, 0.5);
    opacity: 0.1;
  }
  90% {
    transform: translateX(80px) scale(0.8, 0.8);
  }
  100% {
    transform: translateX(60px);
    opacity: 0.3;
  }
}
#loader2:after {
  -webkit-animation-delay: 0.15s;
  animation-delay: 0.15s;
}
#loader2 .roller {
  -webkit-animation-delay: 0.15s;
  animation-delay: 0.15s;
}

#loader3:after {
  -webkit-animation-delay: 0.3s;
  animation-delay: 0.3s;
}
#loader3 .roller {
  -webkit-animation-delay: 0.3s;
  animation-delay: 0.3s;
}

		@font-face {
  font-family: "gyre";
  src: url("http://ff.static.1001fonts.net/t/e/tex-gyre-adventor.bold-italic.otf?#iefix") format("opentype");
}


#container {
  position: relative;
  margin: auto;
  width: 130px;
  height: 220px;
}

#back {
  position: absolute;
  bottom: 0;
  background-color: #ed2618;
  box-shadow: 5px 5px 0 0 #c7ab52;
  -webkit-animation: backAnim 5s 2 both;
  -moz-animation: backAnim 5s 2 both;
  -o-animation: backAnim 5s 2 both;
  animation: backAnim 5s 2 both;
}

@-webkit-keyframes backAnim {
  0% {
    width: 8px;
    height: 68px;
  }
  4% {
    width: 100px;
    height: 75px;
  }
  5% {
    width: 125px;
    height: 80px;
    border-radius: 3px 3px 20px 3px;
  }
  11%, 100% {
    height: 206px;
    width: 125px;
    border-radius: 3px 3px 20px 3px;
  }
}
@-moz-keyframes backAnim {
  0% {
    width: 8px;
    height: 68px;
  }
  4% {
    width: 100px;
    height: 75px;
  }
  5% {
    width: 125px;
    height: 80px;
    border-radius: 3px 3px 20px 3px;
  }
  11%, 100% {
    height: 206px;
    width: 125px;
    border-radius: 3px 3px 20px 3px;
  }
}
@-ms-keyframes backAnim {
  0% {
    width: 8px;
    height: 68px;
  }
  4% {
    width: 100px;
    height: 75px;
  }
  5% {
    width: 125px;
    height: 80px;
    border-radius: 3px 3px 20px 3px;
  }
  11%, 100% {
    height: 206px;
    width: 125px;
    border-radius: 3px 3px 20px 3px;
  }
}
@keyframes backAnim {
  0% {
    width: 8px;
    height: 68px;
  }
  4% {
    width: 100px;
    height: 75px;
  }
  5% {
    width: 125px;
    height: 80px;
    border-radius: 3px 3px 20px 3px;
  }
  11%, 100% {
    height: 206px;
    width: 125px;
    border-radius: 3px 3px 20px 3px;
  }
}
#speaker {
  position: absolute;
  background-color: #646060;
  -webkit-animation: speakerAnim 5s 2 both;
  -moz-animation: speakerAnim 5s 2 both;
  -o-animation: speakerAnim 5s 2 both;
  animation: speakerAnim 5s 2 both;
}

@-webkit-keyframes speakerAnim {
  0%, 6% {
    width: 0px;
    height: 0px;
    bottom: 22px;
    left: 103px;
  }
  11% {
    width: 30px;
    height: 30px;
    bottom: 7px;
    left: 88px;
    border-radius: 15px;
    box-shadow: inset 0px 0px 0px 15px #484848;
  }
  14%, 100% {
    width: 30px;
    height: 30px;
    bottom: 7px;
    left: 88px;
    border-radius: 15px;
    box-shadow: inset 0px 0px 0px 8px #484848;
  }
}
@-moz-keyframes speakerAnim {
  0%, 6% {
    width: 0px;
    height: 0px;
    bottom: 22px;
    left: 103px;
  }
  11% {
    width: 30px;
    height: 30px;
    bottom: 7px;
    left: 88px;
    border-radius: 15px;
    box-shadow: inset 0px 0px 0px 15px #484848;
  }
  14%, 100% {
    width: 30px;
    height: 30px;
    bottom: 7px;
    left: 88px;
    border-radius: 15px;
    box-shadow: inset 0px 0px 0px 8px #484848;
  }
}
@-ms-keyframes speakerAnim {
  0%, 6% {
    width: 0px;
    height: 0px;
    bottom: 22px;
    left: 103px;
  }
  11% {
    width: 30px;
    height: 30px;
    bottom: 7px;
    left: 88px;
    border-radius: 15px;
    box-shadow: inset 0px 0px 0px 15px #484848;
  }
  14%, 100% {
    width: 30px;
    height: 30px;
    bottom: 7px;
    left: 88px;
    border-radius: 15px;
    box-shadow: inset 0px 0px 0px 8px #484848;
  }
}
@keyframes speakerAnim {
  0%, 6% {
    width: 0px;
    height: 0px;
    bottom: 22px;
    left: 103px;
  }
  11% {
    width: 30px;
    height: 30px;
    bottom: 7px;
    left: 88px;
    border-radius: 15px;
    box-shadow: inset 0px 0px 0px 15px #484848;
  }
  14%, 100% {
    width: 30px;
    height: 30px;
    bottom: 7px;
    left: 88px;
    border-radius: 15px;
    box-shadow: inset 0px 0px 0px 8px #484848;
  }
}
#card1 {
  position: absolute;
  left: 15px;
  background-color: #5eaf89;
  -webkit-animation: card1Anim 5s 2 both;
  -moz-animation: card1Anim 5s 2 both;
  -o-animation: card1Anim 5s 2 both;
  animation: card1Anim 5s 2 both;
}

@-webkit-keyframes card1Anim {
  0%, 8% {
    height: 0px;
    width: 0px;
    bottom: 64px;
  }
  9% {
    height: 17px;
    width: 15px;
    bottom: 64px;
  }
  12% {
    height: 113px;
    width: 15px;
    bottom: 17px;
  }
  18%, 100% {
    height: 113px;
    width: 95px;
    bottom: 17px;
  }
}
@-moz-keyframes card1Anim {
  0%, 8% {
    height: 0px;
    width: 0px;
    bottom: 64px;
  }
  9% {
    height: 17px;
    width: 15px;
    bottom: 64px;
  }
  12% {
    height: 113px;
    width: 15px;
    bottom: 17px;
  }
  18%, 100% {
    height: 113px;
    width: 95px;
    bottom: 17px;
  }
}
@-ms-keyframes card1Anim {
  0%, 8% {
    height: 0px;
    width: 0px;
    bottom: 64px;
  }
  9% {
    height: 17px;
    width: 15px;
    bottom: 64px;
  }
  12% {
    height: 113px;
    width: 15px;
    bottom: 17px;
  }
  18%, 100% {
    height: 113px;
    width: 95px;
    bottom: 17px;
  }
}
@keyframes card1Anim {
  0%, 8% {
    height: 0px;
    width: 0px;
    bottom: 64px;
  }
  9% {
    height: 17px;
    width: 15px;
    bottom: 64px;
  }
  12% {
    height: 113px;
    width: 15px;
    bottom: 17px;
  }
  18%, 100% {
    height: 113px;
    width: 95px;
    bottom: 17px;
  }
}
#border {
  position: absolute;
  bottom: 2px;
  right: 7px;
  border: 2px solid #646060;
  border-radius: 3px 3px 20px 3px;
  -webkit-animation: borderAnim 5s 2 both;
  -moz-animation: borderAnim 5s 2 both;
  -o-animation: borderAnim 5s 2 both;
  animation: borderAnim 5s 2 both;
}

@-webkit-keyframes borderAnim {
  0%, 8% {
    height: 0px;
    width: 0px;
    border: none;
  }
  9% {
    height: 40px;
    width: 10px;
    border-right: 2px solid #646060;
    border-bottom: 2px solid #646060;
    border-top: none;
    border-left: none;
  }
  13% {
    height: 40px;
    width: 117px;
    border-right: 2px solid #646060;
    border-bottom: 2px solid #646060;
    border-top: none;
    border-left: none;
  }
  17% {
    height: 198px;
    width: 117px;
    border-right: 2px solid #646060;
    border-left: 2px solid #646060;
    border-bottom: 2px solid #646060;
    border-top: none;
  }
  18%, 100% {
    height: 198px;
    width: 117px;
    border: 2px solid #646060;
  }
}
@-moz-keyframes borderAnim {
  0%, 8% {
    height: 0px;
    width: 0px;
    border: none;
  }
  9% {
    height: 40px;
    width: 10px;
    border-right: 2px solid #646060;
    border-bottom: 2px solid #646060;
    border-top: none;
    border-left: none;
  }
  13% {
    height: 40px;
    width: 117px;
    border-right: 2px solid #646060;
    border-bottom: 2px solid #646060;
    border-top: none;
    border-left: none;
  }
  17% {
    height: 198px;
    width: 117px;
    border-right: 2px solid #646060;
    border-left: 2px solid #646060;
    border-bottom: 2px solid #646060;
    border-top: none;
  }
  18%, 100% {
    height: 198px;
    width: 117px;
    border: 2px solid #646060;
  }
}
@-ms-keyframes borderAnim {
  0%, 8% {
    height: 0px;
    width: 0px;
    border: none;
  }
  9% {
    height: 40px;
    width: 10px;
    border-right: 2px solid #646060;
    border-bottom: 2px solid #646060;
    border-top: none;
    border-left: none;
  }
  13% {
    height: 40px;
    width: 117px;
    border-right: 2px solid #646060;
    border-bottom: 2px solid #646060;
    border-top: none;
    border-left: none;
  }
  17% {
    height: 198px;
    width: 117px;
    border-right: 2px solid #646060;
    border-left: 2px solid #646060;
    border-bottom: 2px solid #646060;
    border-top: none;
  }
  18%, 100% {
    height: 198px;
    width: 117px;
    border: 2px solid #646060;
  }
}
@keyframes borderAnim {
  0%, 8% {
    height: 0px;
    width: 0px;
    border: none;
  }
  9% {
    height: 40px;
    width: 10px;
    border-right: 2px solid #646060;
    border-bottom: 2px solid #646060;
    border-top: none;
    border-left: none;
  }
  13% {
    height: 40px;
    width: 117px;
    border-right: 2px solid #646060;
    border-bottom: 2px solid #646060;
    border-top: none;
    border-left: none;
  }
  17% {
    height: 198px;
    width: 117px;
    border-right: 2px solid #646060;
    border-left: 2px solid #646060;
    border-bottom: 2px solid #646060;
    border-top: none;
  }
  18%, 100% {
    height: 198px;
    width: 117px;
    border: 2px solid #646060;
  }
}
#card2 {
  position: absolute;
  bottom: 6px;
  left: 7px;
  width: 10px;
  height: 20px;
  background-color: #646060;
  -webkit-animation: card2Anim 5s 2 both;
  -moz-animation: card2Anim 5s 2 both;
  -o-animation: card2Anim 5s 2 both;
  animation: card2Anim 5s 2 both;
}

@-webkit-keyframes card2Anim {
  0%, 12% {
    height: 0px;
    width: 0px;
  }
  13% {
    height: 20px;
    width: 10px;
  }
  21%, 100% {
    height: 20px;
    width: 78px;
  }
}
@-moz-keyframes card2Anim {
  0%, 12% {
    height: 0px;
    width: 0px;
  }
  13% {
    height: 20px;
    width: 10px;
  }
  21%, 100% {
    height: 20px;
    width: 78px;
  }
}
@-ms-keyframes card2Anim {
  0%, 12% {
    height: 0px;
    width: 0px;
  }
  13% {
    height: 20px;
    width: 10px;
  }
  21%, 100% {
    height: 20px;
    width: 78px;
  }
}
@keyframes card2Anim {
  0%, 12% {
    height: 0px;
    width: 0px;
  }
  13% {
    height: 20px;
    width: 10px;
  }
  21%, 100% {
    height: 20px;
    width: 78px;
  }
}
#card3 {
  position: absolute;
  bottom: 48px;
  left: 8px;
  height: 5px;
  background-color: #3c9b66;
  -webkit-animation: card3Anim 5s 2 both;
  -moz-animation: card3Anim 5s 2 both;
  -o-animation: card3Anim 5s 2 both;
  animation: card3Anim 5s 2 both;
}

@-webkit-keyframes card3Anim {
  0%, 12% {
    height: 0px;
    width: 0px;
  }
  15% {
    height: 5px;
    width: 110px;
  }
  23%, 100% {
    height: 150px;
    width: 110px;
  }
}
@-moz-keyframes card3Anim {
  0%, 12% {
    height: 0px;
    width: 0px;
  }
  15% {
    height: 5px;
    width: 110px;
  }
  23%, 100% {
    height: 150px;
    width: 110px;
  }
}
@-ms-keyframes card3Anim {
  0%, 12% {
    height: 0px;
    width: 0px;
  }
  15% {
    height: 5px;
    width: 110px;
  }
  23%, 100% {
    height: 150px;
    width: 110px;
  }
}
@keyframes card3Anim {
  0%, 12% {
    height: 0px;
    width: 0px;
  }
  15% {
    height: 5px;
    width: 110px;
  }
  23%, 100% {
    height: 150px;
    width: 110px;
  }
}
#chip {
  position: absolute;
  bottom: 46px;
  left: 54px;
  width: 4px;
  height: 4px;
  background-color: #484848;
  -webkit-animation: chipAnim 5s 2 both;
  -moz-animation: chipAnim 5s 2 both;
  -o-animation: chipAnim 5s 2 both;
  animation: chipAnim 5s 2 both;
}

@-webkit-keyframes chipAnim {
  0%, 15% {
    height: 0px;
    width: 0px;
  }
  16% {
    height: 4px;
    width: 4px;
    bottom: 46px;
    left: 54px;
  }
  20%, 100% {
    height: 22px;
    width: 22px;
    bottom: 37px;
    left: 45px;
  }
}
@-moz-keyframes chipAnim {
  0%, 15% {
    height: 0px;
    width: 0px;
  }
  16% {
    height: 4px;
    width: 4px;
    bottom: 46px;
    left: 54px;
  }
  20%, 100% {
    height: 22px;
    width: 22px;
    bottom: 37px;
    left: 45px;
  }
}
@-ms-keyframes chipAnim {
  0%, 15% {
    height: 0px;
    width: 0px;
  }
  16% {
    height: 4px;
    width: 4px;
    bottom: 46px;
    left: 54px;
  }
  20%, 100% {
    height: 22px;
    width: 22px;
    bottom: 37px;
    left: 45px;
  }
}
@keyframes chipAnim {
  0%, 15% {
    height: 0px;
    width: 0px;
  }
  16% {
    height: 4px;
    width: 4px;
    bottom: 46px;
    left: 54px;
  }
  20%, 100% {
    height: 22px;
    width: 22px;
    bottom: 37px;
    left: 45px;
  }
}
#chip2 {
  position: absolute;
  bottom: 132px;
  left: 60px;
  width: 4px;
  height: 12px;
  background-color: #484848;
  -webkit-animation: chip2Anim 5s 2 both;
  -moz-animation: chip2Anim 5s 2 both;
  -o-animation: chip2Anim 5s 2 both;
  animation: chip2Anim 5s 2 both;
}

@-webkit-keyframes chip2Anim {
  0%, 16% {
    height: 0px;
    width: 0px;
  }
  17% {
    height: 12px;
    width: 4px;
    bottom: 132px;
    left: 60px;
  }
  23% {
    height: 12px;
    width: 60px;
    bottom: 132px;
    left: 32px;
  }
  30%, 100% {
    height: 12px;
    width: 60px;
    bottom: 160px;
    left: 32px;
  }
}
@-moz-keyframes chip2Anim {
  0%, 16% {
    height: 0px;
    width: 0px;
  }
  17% {
    height: 12px;
    width: 4px;
    bottom: 132px;
    left: 60px;
  }
  23% {
    height: 12px;
    width: 60px;
    bottom: 132px;
    left: 32px;
  }
  30%, 100% {
    height: 12px;
    width: 60px;
    bottom: 160px;
    left: 32px;
  }
}
@-ms-keyframes chip2Anim {
  0%, 16% {
    height: 0px;
    width: 0px;
  }
  17% {
    height: 12px;
    width: 4px;
    bottom: 132px;
    left: 60px;
  }
  23% {
    height: 12px;
    width: 60px;
    bottom: 132px;
    left: 32px;
  }
  30%, 100% {
    height: 12px;
    width: 60px;
    bottom: 160px;
    left: 32px;
  }
}
@keyframes chip2Anim {
  0%, 16% {
    height: 0px;
    width: 0px;
  }
  17% {
    height: 12px;
    width: 4px;
    bottom: 132px;
    left: 60px;
  }
  23% {
    height: 12px;
    width: 60px;
    bottom: 132px;
    left: 32px;
  }
  30%, 100% {
    height: 12px;
    width: 60px;
    bottom: 160px;
    left: 32px;
  }
}
#volumeWheelBack {
  position: absolute;
  left: 108px;
  bottom: 157px;
  width: 10px;
  height: 10px;
  background-color: #645d5f;
  -webkit-animation: volumeWheelBackAnim 5s 2 both;
  -moz-animation: volumeWheelBackAnim 5s 2 both;
  -o-animation: volumeWheelBackAnim 5s 2 both;
  animation: volumeWheelBackAnim 5s 2 both;
}

@-webkit-keyframes volumeWheelBackAnim {
  0%, 17% {
    height: 0px;
    width: 0px;
    left: 113px;
    bottom: 162px;
  }
  21%, 25% {
    height: 10px;
    width: 10px;
    left: 108px;
    bottom: 157px;
  }
  30%, 100% {
    height: 10px;
    width: 10px;
    left: 108px;
    bottom: 167px;
  }
}
@-moz-keyframes volumeWheelBackAnim {
  0%, 17% {
    height: 0px;
    width: 0px;
    left: 113px;
    bottom: 162px;
  }
  21%, 25% {
    height: 10px;
    width: 10px;
    left: 108px;
    bottom: 157px;
  }
  30%, 100% {
    height: 10px;
    width: 10px;
    left: 108px;
    bottom: 167px;
  }
}
@-ms-keyframes volumeWheelBackAnim {
  0%, 17% {
    height: 0px;
    width: 0px;
    left: 113px;
    bottom: 162px;
  }
  21%, 25% {
    height: 10px;
    width: 10px;
    left: 108px;
    bottom: 157px;
  }
  30%, 100% {
    height: 10px;
    width: 10px;
    left: 108px;
    bottom: 167px;
  }
}
@keyframes volumeWheelBackAnim {
  0%, 17% {
    height: 0px;
    width: 0px;
    left: 113px;
    bottom: 162px;
  }
  21%, 25% {
    height: 10px;
    width: 10px;
    left: 108px;
    bottom: 157px;
  }
  30%, 100% {
    height: 10px;
    width: 10px;
    left: 108px;
    bottom: 167px;
  }
}
#volumeWheel {
  position: absolute;
  left: 108px;
  bottom: 157px;
  width: 16px;
  height: 16px;
  border-radius: 8px;
  background-color: #b2aea9;
  box-shadow: inset 0px 0px 0px 5px #dddddd;
  -webkit-animation: volumeWheelAnim 5s 2 both;
  -moz-animation: volumeWheelAnim 5s 2 both;
  -o-animation: volumeWheelAnim 5s 2 both;
  animation: volumeWheelAnim 5s 2 both;
}

@-webkit-keyframes volumeWheelAnim {
  0%, 18% {
    height: 1px;
    width: 1px;
    left: 115px;
    bottom: 159px;
    box-shadow: inset 0px 0px 0px 10px #dddddd;
  }
  22% {
    height: 16px;
    width: 16px;
    left: 110px;
    bottom: 154px;
    box-shadow: inset 0px 0px 0px 10px #dddddd;
  }
  25% {
    height: 16px;
    width: 16px;
    left: 110px;
    bottom: 154px;
    box-shadow: inset 0px 0px 0px 5px #dddddd;
  }
  30%, 100% {
    height: 16px;
    width: 16px;
    left: 110px;
    bottom: 164px;
    box-shadow: inset 0px 0px 0px 5px #dddddd;
  }
}
@-moz-keyframes volumeWheelAnim {
  0%, 18% {
    height: 1px;
    width: 1px;
    left: 115px;
    bottom: 159px;
    box-shadow: inset 0px 0px 0px 10px #dddddd;
  }
  22% {
    height: 16px;
    width: 16px;
    left: 110px;
    bottom: 154px;
    box-shadow: inset 0px 0px 0px 10px #dddddd;
  }
  25% {
    height: 16px;
    width: 16px;
    left: 110px;
    bottom: 154px;
    box-shadow: inset 0px 0px 0px 5px #dddddd;
  }
  30%, 100% {
    height: 16px;
    width: 16px;
    left: 110px;
    bottom: 164px;
    box-shadow: inset 0px 0px 0px 5px #dddddd;
  }
}
@-ms-keyframes volumeWheelAnim {
  0%, 18% {
    height: 1px;
    width: 1px;
    left: 115px;
    bottom: 159px;
    box-shadow: inset 0px 0px 0px 10px #dddddd;
  }
  22% {
    height: 16px;
    width: 16px;
    left: 110px;
    bottom: 154px;
    box-shadow: inset 0px 0px 0px 10px #dddddd;
  }
  25% {
    height: 16px;
    width: 16px;
    left: 110px;
    bottom: 154px;
    box-shadow: inset 0px 0px 0px 5px #dddddd;
  }
  30%, 100% {
    height: 16px;
    width: 16px;
    left: 110px;
    bottom: 164px;
    box-shadow: inset 0px 0px 0px 5px #dddddd;
  }
}
@keyframes volumeWheelAnim {
  0%, 18% {
    height: 1px;
    width: 1px;
    left: 115px;
    bottom: 159px;
    box-shadow: inset 0px 0px 0px 10px #dddddd;
  }
  22% {
    height: 16px;
    width: 16px;
    left: 110px;
    bottom: 154px;
    box-shadow: inset 0px 0px 0px 10px #dddddd;
  }
  25% {
    height: 16px;
    width: 16px;
    left: 110px;
    bottom: 154px;
    box-shadow: inset 0px 0px 0px 5px #dddddd;
  }
  30%, 100% {
    height: 16px;
    width: 16px;
    left: 110px;
    bottom: 164px;
    box-shadow: inset 0px 0px 0px 5px #dddddd;
  }
}
#chipPinL {
  position: absolute;
  left: 43px;
  bottom: 54px;
  width: 4px;
  height: 2px;
  background-color: #dddddd;
  box-shadow: 0px 3px #dddddd;
  -webkit-animation: chipPinAnimL 5s 2 both;
  -moz-animation: chipPinAnimL 5s 2 both;
  -o-animation: chipPinAnimL 5s 2 both;
  animation: chipPinAnimL 5s 2 both;
}

@-webkit-keyframes chipPinAnimL {
  0%, 19% {
    width: 0px;
  }
  20% {
    width: 4px;
    box-shadow: 0px 3px #dddddd;
  }
  21% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd;
  }
  22%, 100% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd, 0px 12px #dddddd, 0px 15px #dddddd;
  }
}
@-moz-keyframes chipPinAnimL {
  0%, 19% {
    width: 0px;
  }
  20% {
    width: 4px;
    box-shadow: 0px 3px #dddddd;
  }
  21% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd;
  }
  22%, 100% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd, 0px 12px #dddddd, 0px 15px #dddddd;
  }
}
@-ms-keyframes chipPinAnimL {
  0%, 19% {
    width: 0px;
  }
  20% {
    width: 4px;
    box-shadow: 0px 3px #dddddd;
  }
  21% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd;
  }
  22%, 100% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd, 0px 12px #dddddd, 0px 15px #dddddd;
  }
}
@keyframes chipPinAnimL {
  0%, 19% {
    width: 0px;
  }
  20% {
    width: 4px;
    box-shadow: 0px 3px #dddddd;
  }
  21% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd;
  }
  22%, 100% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd, 0px 12px #dddddd, 0px 15px #dddddd;
  }
}
#chipPinR {
  position: absolute;
  left: 65px;
  bottom: 54px;
  width: 4px;
  height: 2px;
  background-color: #dddddd;
  box-shadow: 0px 3px #dddddd;
  -webkit-animation: chipPinAnimR 5s 2 both;
  -moz-animation: chipPinAnimR 5s 2 both;
  -o-animation: chipPinAnimR 5s 2 both;
  animation: chipPinAnimR 5s 2 both;
}

@-webkit-keyframes chipPinAnimR {
  0%, 22% {
    width: 0px;
  }
  23% {
    width: 4px;
    box-shadow: 0px 3px #dddddd;
  }
  24% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd;
  }
  25%, 100% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd, 0px 12px #dddddd, 0px 15px #dddddd;
  }
}
@-moz-keyframes chipPinAnimR {
  0%, 22% {
    width: 0px;
  }
  23% {
    width: 4px;
    box-shadow: 0px 3px #dddddd;
  }
  24% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd;
  }
  25%, 100% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd, 0px 12px #dddddd, 0px 15px #dddddd;
  }
}
@-ms-keyframes chipPinAnimR {
  0%, 22% {
    width: 0px;
  }
  23% {
    width: 4px;
    box-shadow: 0px 3px #dddddd;
  }
  24% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd;
  }
  25%, 100% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd, 0px 12px #dddddd, 0px 15px #dddddd;
  }
}
@keyframes chipPinAnimR {
  0%, 22% {
    width: 0px;
  }
  23% {
    width: 4px;
    box-shadow: 0px 3px #dddddd;
  }
  24% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd;
  }
  25%, 100% {
    box-shadow: 0px 3px #dddddd, 0px 6px #dddddd, 0px 9px #dddddd, 0px 12px #dddddd, 0px 15px #dddddd;
  }
}
#ec1 {
  position: absolute;
  left: 24px;
  bottom: 122px;
  width: 4px;
  height: 4px;
  border-radius: 2px;
  background-color: #484848;
  -webkit-animation: ec3Anim 5s 2 both;
  -moz-animation: ec3Anim 5s 2 both;
  -o-animation: ec3Anim 5s 2 both;
  animation: ec3Anim 5s 2 both;
}

@-webkit-keyframes ec3Anim {
  0%, 18% {
    width: 0px;
  }
  20% {
    width: 4px;
    height: 4px;
  }
  22% {
    box-shadow: 8px 0px #484848;
  }
  24% {
    box-shadow: 8px 0px #484848, 16px 0px #484848;
  }
  26% {
    box-shadow: 8px 0px #484848, 16px 0px #484848, 24px 0px #484848;
  }
  28% {
    box-shadow: 8px 0px #484848, 16px 0px #484848, 24px 0px #484848, 32px 0px #484848;
  }
  30%, 100% {
    box-shadow: 8px 0px #484848, 16px 0px #484848, 24px 0px #484848, 32px 0px #484848, 40px 0px #484848;
  }
}
@-moz-keyframes ec3Anim {
  0%, 18% {
    width: 0px;
  }
  20% {
    width: 4px;
    height: 4px;
  }
  22% {
    box-shadow: 8px 0px #484848;
  }
  24% {
    box-shadow: 8px 0px #484848, 16px 0px #484848;
  }
  26% {
    box-shadow: 8px 0px #484848, 16px 0px #484848, 24px 0px #484848;
  }
  28% {
    box-shadow: 8px 0px #484848, 16px 0px #484848, 24px 0px #484848, 32px 0px #484848;
  }
  30%, 100% {
    box-shadow: 8px 0px #484848, 16px 0px #484848, 24px 0px #484848, 32px 0px #484848, 40px 0px #484848;
  }
}
@-ms-keyframes ec3Anim {
  0%, 18% {
    width: 0px;
  }
  20% {
    width: 4px;
    height: 4px;
  }
  22% {
    box-shadow: 8px 0px #484848;
  }
  24% {
    box-shadow: 8px 0px #484848, 16px 0px #484848;
  }
  26% {
    box-shadow: 8px 0px #484848, 16px 0px #484848, 24px 0px #484848;
  }
  28% {
    box-shadow: 8px 0px #484848, 16px 0px #484848, 24px 0px #484848, 32px 0px #484848;
  }
  30%, 100% {
    box-shadow: 8px 0px #484848, 16px 0px #484848, 24px 0px #484848, 32px 0px #484848, 40px 0px #484848;
  }
}
@keyframes ec3Anim {
  0%, 18% {
    width: 0px;
  }
  20% {
    width: 4px;
    height: 4px;
  }
  22% {
    box-shadow: 8px 0px #484848;
  }
  24% {
    box-shadow: 8px 0px #484848, 16px 0px #484848;
  }
  26% {
    box-shadow: 8px 0px #484848, 16px 0px #484848, 24px 0px #484848;
  }
  28% {
    box-shadow: 8px 0px #484848, 16px 0px #484848, 24px 0px #484848, 32px 0px #484848;
  }
  30%, 100% {
    box-shadow: 8px 0px #484848, 16px 0px #484848, 24px 0px #484848, 32px 0px #484848, 40px 0px #484848;
  }
}
#joystickBack {
  position: absolute;
  left: 8px;
  bottom: 47px;
  width: 36px;
  height: 36px;
  border-radius: 18px;
  background-color: #dddddd;
  -webkit-animation: joystickBackAnim 5s 2 both;
  -moz-animation: joystickBackAnim 5s 2 both;
  -o-animation: joystickBackAnim 5s 2 both;
  animation: joystickBackAnim 5s 2 both;
}

@-webkit-keyframes joystickBackAnim {
  0%, 23% {
    left: 26px;
    bottom: 65px;
    width: 0px;
    height: 0px;
  }
  28%, 100% {
    left: 8px;
    bottom: 47px;
    width: 36px;
    height: 36px;
  }
}
@-moz-keyframes joystickBackAnim {
  0%, 23% {
    left: 26px;
    bottom: 65px;
    width: 0px;
    height: 0px;
  }
  28%, 100% {
    left: 8px;
    bottom: 47px;
    width: 36px;
    height: 36px;
  }
}
@-ms-keyframes joystickBackAnim {
  0%, 23% {
    left: 26px;
    bottom: 65px;
    width: 0px;
    height: 0px;
  }
  28%, 100% {
    left: 8px;
    bottom: 47px;
    width: 36px;
    height: 36px;
  }
}
@keyframes joystickBackAnim {
  0%, 23% {
    left: 26px;
    bottom: 65px;
    width: 0px;
    height: 0px;
  }
  28%, 100% {
    left: 8px;
    bottom: 47px;
    width: 36px;
    height: 36px;
  }
}
#joystickCross1 {
  position: absolute;
  left: 11px;
  bottom: 60px;
  width: 30px;
  height: 10px;
  border-radius: 1px;
  background-color: #484848;
  -webkit-animation: joystickCrossAnim 5s 2 both;
  -moz-animation: joystickCrossAnim 5s 2 both;
  -o-animation: joystickCrossAnim 5s 2 both;
  animation: joystickCrossAnim 5s 2 both;
}

#joystickCross2 {
  position: absolute;
  left: 11px;
  bottom: 60px;
  width: 30px;
  height: 10px;
  border-radius: 1px;
  background-color: #484848;
  -moz-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  -webkit-transform: rotate(90deg);
  transform: rotate(90deg);
  -webkit-animation: joystickCrossAnim 5s 2 both;
  -moz-animation: joystickCrossAnim 5s 2 both;
  -o-animation: joystickCrossAnim 5s 2 both;
  animation: joystickCrossAnim 5s 2 both;
}

@-webkit-keyframes joystickCrossAnim {
  0%, 26% {
    left: 26px;
    bottom: 65px;
    width: 0px;
    height: 0px;
  }
  33%, 100% {
    left: 11px;
    bottom: 60px;
    width: 30px;
    height: 10px;
  }
}
@-moz-keyframes joystickCrossAnim {
  0%, 26% {
    left: 26px;
    bottom: 65px;
    width: 0px;
    height: 0px;
  }
  33%, 100% {
    left: 11px;
    bottom: 60px;
    width: 30px;
    height: 10px;
  }
}
@-ms-keyframes joystickCrossAnim {
  0%, 26% {
    left: 26px;
    bottom: 65px;
    width: 0px;
    height: 0px;
  }
  33%, 100% {
    left: 11px;
    bottom: 60px;
    width: 30px;
    height: 10px;
  }
}
@keyframes joystickCrossAnim {
  0%, 26% {
    left: 26px;
    bottom: 65px;
    width: 0px;
    height: 0px;
  }
  33%, 100% {
    left: 11px;
    bottom: 60px;
    width: 30px;
    height: 10px;
  }
}
#buttonsABBack {
  position: absolute;
  left: 70px;
  bottom: 55px;
  width: 50px;
  height: 22px;
  border-radius: 11px;
  background-color: #dddddd;
  box-shadow: inset 0px 0px 0px 2px #a9a9a9;
  -moz-transform: rotate(160deg);
  -ms-transform: rotate(160deg);
  -webkit-transform: rotate(160deg);
  transform: rotate(160deg);
  -webkit-animation: buttonsABBackAnim 5s 2 both;
  -moz-animation: buttonsABBackAnim 5s 2 both;
  -o-animation: buttonsABBackAnim 5s 2 both;
  animation: buttonsABBackAnim 5s 2 both;
}

@-webkit-keyframes buttonsABBackAnim {
  0%, 24% {
    left: 95px;
    bottom: 67px;
    width: 0px;
    height: 0px;
    -moz-transform: rotate(220deg);
    -ms-transform: rotate(220deg);
    -webkit-transform: rotate(220deg);
    transform: rotate(220deg);
  }
  29% {
    left: 70px;
    bottom: 55px;
    width: 50px;
    height: 22px;
    -webkit-transform: rotate(160deg);
    -moz-transform: rotate(160deg);
    -ms-transform: rotate(160deg);
    -webkit-transform: rotate(160deg);
    transform: rotate(160deg);
  }
  33%, 100% {
    box-shadow: inset 0px 0px 0px 2px #a9a9a9;
  }
}
@-moz-keyframes buttonsABBackAnim {
  0%, 24% {
    left: 95px;
    bottom: 67px;
    width: 0px;
    height: 0px;
    -moz-transform: rotate(220deg);
    -ms-transform: rotate(220deg);
    -webkit-transform: rotate(220deg);
    transform: rotate(220deg);
  }
  29% {
    left: 70px;
    bottom: 55px;
    width: 50px;
    height: 22px;
    -webkit-transform: rotate(160deg);
    -moz-transform: rotate(160deg);
    -ms-transform: rotate(160deg);
    -webkit-transform: rotate(160deg);
    transform: rotate(160deg);
  }
  33%, 100% {
    box-shadow: inset 0px 0px 0px 2px #a9a9a9;
  }
}
@-ms-keyframes buttonsABBackAnim {
  0%, 24% {
    left: 95px;
    bottom: 67px;
    width: 0px;
    height: 0px;
    -moz-transform: rotate(220deg);
    -ms-transform: rotate(220deg);
    -webkit-transform: rotate(220deg);
    transform: rotate(220deg);
  }
  29% {
    left: 70px;
    bottom: 55px;
    width: 50px;
    height: 22px;
    -webkit-transform: rotate(160deg);
    -moz-transform: rotate(160deg);
    -ms-transform: rotate(160deg);
    -webkit-transform: rotate(160deg);
    transform: rotate(160deg);
  }
  33%, 100% {
    box-shadow: inset 0px 0px 0px 2px #a9a9a9;
  }
}
@keyframes buttonsABBackAnim {
  0%, 24% {
    left: 95px;
    bottom: 67px;
    width: 0px;
    height: 0px;
    -moz-transform: rotate(220deg);
    -ms-transform: rotate(220deg);
    -webkit-transform: rotate(220deg);
    transform: rotate(220deg);
  }
  29% {
    left: 70px;
    bottom: 55px;
    width: 50px;
    height: 22px;
    -webkit-transform: rotate(160deg);
    -moz-transform: rotate(160deg);
    -ms-transform: rotate(160deg);
    -webkit-transform: rotate(160deg);
    transform: rotate(160deg);
  }
  33%, 100% {
    box-shadow: inset 0px 0px 0px 2px #a9a9a9;
  }
}
#buttonsAB {
  position: absolute;
  left: 74px;
  bottom: 53px;
  width: 16px;
  height: 16px;
  border-radius: 11px;
  background-color: #484848;
  box-shadow: 26px -10px #484848;
  -webkit-animation: buttonsABAnim 5s 2 both;
  -moz-animation: buttonsABAnim 5s 2 both;
  -o-animation: buttonsABAnim 5s 2 both;
  animation: buttonsABAnim 5s 2 both;
}

@-webkit-keyframes buttonsABAnim {
  0%, 28% {
    left: 81px;
    bottom: 61px;
    width: 0px;
    height: 0px;
    box-shadow: 26px -10px #484848;
  }
  33%, 100% {
    left: 74px;
    bottom: 53px;
    width: 16px;
    height: 16px;
    box-shadow: 26px -10px #484848;
  }
}
@-moz-keyframes buttonsABAnim {
  0%, 28% {
    left: 81px;
    bottom: 61px;
    width: 0px;
    height: 0px;
    box-shadow: 26px -10px #484848;
  }
  33%, 100% {
    left: 74px;
    bottom: 53px;
    width: 16px;
    height: 16px;
    box-shadow: 26px -10px #484848;
  }
}
@-ms-keyframes buttonsABAnim {
  0%, 28% {
    left: 81px;
    bottom: 61px;
    width: 0px;
    height: 0px;
    box-shadow: 26px -10px #484848;
  }
  33%, 100% {
    left: 74px;
    bottom: 53px;
    width: 16px;
    height: 16px;
    box-shadow: 26px -10px #484848;
  }
}
@keyframes buttonsABAnim {
  0%, 28% {
    left: 81px;
    bottom: 61px;
    width: 0px;
    height: 0px;
    box-shadow: 26px -10px #484848;
  }
  33%, 100% {
    left: 74px;
    bottom: 53px;
    width: 16px;
    height: 16px;
    box-shadow: 26px -10px #484848;
  }
}
#buttonsABText {
  -webkit-animation: buttonsABTextAnim 5s 2 both;
  -moz-animation: buttonsABTextAnim 5s 2 both;
  -o-animation: buttonsABTextAnim 5s 2 both;
  animation: buttonsABTextAnim 5s 2 both;
}

#buttonsABText::before {
  content: "A";
  position: absolute;
  left: 106px;
  bottom: 50px;
  font: 8px "Arial";
  color: #606060;
}

#buttonsABText::after {
  content: "B";
  position: absolute;
  left: 80px;
  bottom: 40px;
  font: 8px "Arial";
  color: #606060;
}

@-webkit-keyframes buttonsABTextAnim {
  0%, 73% {
    visibility: hidden;
  }
  74%, 100% {
    bisibility: visible;
  }
}
@-moz-keyframes buttonsABTextAnim {
  0%, 73% {
    visibility: hidden;
  }
  74%, 100% {
    bisibility: visible;
  }
}
@-ms-keyframes buttonsABTextAnim {
  0%, 73% {
    visibility: hidden;
  }
  74%, 100% {
    bisibility: visible;
  }
}
@keyframes buttonsABTextAnim {
  0%, 73% {
    visibility: hidden;
  }
  74%, 100% {
    bisibility: visible;
  }
}
#buttonsSSText {
  -webkit-animation: buttonsSSTextAnim 5s 2 both;
  -moz-animation: buttonsSSTextAnim 5s 2 both;
  -o-animation: buttonsSSTextAnim 5s 2 both;
  animation: buttonsSSTextAnim 5s 2 both;
}

#buttonsSSText::before {
  content: "select";
  position: absolute;
  left: 45px;
  bottom: 15px;
  font: 7px "Arial";
  color: #606060;
}

#buttonsSSText::after {
  content: "start";
  position: absolute;
  left: 68px;
  bottom: 15px;
  font: 7px "Arial";
  color: #606060;
}

@-webkit-keyframes buttonsSSTextAnim {
  0%, 75% {
    visibility: hidden;
  }
  76%, 100% {
    bisibility: visible;
  }
}
@-moz-keyframes buttonsSSTextAnim {
  0%, 75% {
    visibility: hidden;
  }
  76%, 100% {
    bisibility: visible;
  }
}
@-ms-keyframes buttonsSSTextAnim {
  0%, 75% {
    visibility: hidden;
  }
  76%, 100% {
    bisibility: visible;
  }
}
@keyframes buttonsSSTextAnim {
  0%, 75% {
    visibility: hidden;
  }
  76%, 100% {
    bisibility: visible;
  }
}
#buttonsSSBack {
  position: absolute;
  left: 45px;
  bottom: 26px;
  width: 40px;
  height: 10px;
  background-color: #dddddd;
  -webkit-animation: buttonsSSBackAnim 5s 2 both;
  -moz-animation: buttonsSSBackAnim 5s 2 both;
  -o-animation: buttonsSSBackAnim 5s 2 both;
  animation: buttonsSSBackAnim 5s 2 both;
}

@-webkit-keyframes buttonsSSBackAnim {
  0%, 27% {
    left: 65px;
    bottom: 26px;
    width: 0px;
    height: 10px;
  }
  33%, 100% {
    left: 45px;
    bottom: 26px;
    width: 40px;
    height: 10px;
  }
}
@-moz-keyframes buttonsSSBackAnim {
  0%, 27% {
    left: 65px;
    bottom: 26px;
    width: 0px;
    height: 10px;
  }
  33%, 100% {
    left: 45px;
    bottom: 26px;
    width: 40px;
    height: 10px;
  }
}
@-ms-keyframes buttonsSSBackAnim {
  0%, 27% {
    left: 65px;
    bottom: 26px;
    width: 0px;
    height: 10px;
  }
  33%, 100% {
    left: 45px;
    bottom: 26px;
    width: 40px;
    height: 10px;
  }
}
@keyframes buttonsSSBackAnim {
  0%, 27% {
    left: 65px;
    bottom: 26px;
    width: 0px;
    height: 10px;
  }
  33%, 100% {
    left: 45px;
    bottom: 26px;
    width: 40px;
    height: 10px;
  }
}
#buttonsSS {
  position: absolute;
  border-radius: 2px;
  background-color: #484848;
  -webkit-animation: buttonsSSAnim 5s 2 both;
  -moz-animation: buttonsSSAnim 5s 2 both;
  -o-animation: buttonsSSAnim 5s 2 both;
  animation: buttonsSSAnim 5s 2 both;
}

@-webkit-keyframes buttonsSSAnim {
  0%, 34% {
    left: 52px;
    bottom: 31px;
    width: 0px;
    height: 0px;
    box-shadow: inset 0px 0px 0px 2px #a9a8a6, 20px 0px 0px -2px #484848, 26px 0px #a9a8a6;
  }
  41% {
    left: 45px;
    bottom: 29px;
    width: 14px;
    height: 4px;
    box-shadow: inset 0px 0px 0px 2px #a9a8a6, 20px 0px 0px -2px #484848, 26px 0px #a9a8a6;
  }
  44% {
    left: 48px;
    bottom: 29px;
    width: 14px;
    height: 4px;
    box-shadow: inset 0px 0px 0px 2px #a9a8a6, 20px 0px 0px -2px #484848, 20px 0px #a9a8a6;
  }
  49%, 100% {
    left: 48px;
    bottom: 29px;
    width: 14px;
    height: 4px;
    box-shadow: inset 0px 0px 0px 0px #a9a8a6, 20px 0px 0px 0px #484848, 20px 0px #a9a8a6;
  }
}
@-moz-keyframes buttonsSSAnim {
  0%, 34% {
    left: 52px;
    bottom: 31px;
    width: 0px;
    height: 0px;
    box-shadow: inset 0px 0px 0px 2px #a9a8a6, 20px 0px 0px -2px #484848, 26px 0px #a9a8a6;
  }
  41% {
    left: 45px;
    bottom: 29px;
    width: 14px;
    height: 4px;
    box-shadow: inset 0px 0px 0px 2px #a9a8a6, 20px 0px 0px -2px #484848, 26px 0px #a9a8a6;
  }
  44% {
    left: 48px;
    bottom: 29px;
    width: 14px;
    height: 4px;
    box-shadow: inset 0px 0px 0px 2px #a9a8a6, 20px 0px 0px -2px #484848, 20px 0px #a9a8a6;
  }
  49%, 100% {
    left: 48px;
    bottom: 29px;
    width: 14px;
    height: 4px;
    box-shadow: inset 0px 0px 0px 0px #a9a8a6, 20px 0px 0px 0px #484848, 20px 0px #a9a8a6;
  }
}
@-ms-keyframes buttonsSSAnim {
  0%, 34% {
    left: 52px;
    bottom: 31px;
    width: 0px;
    height: 0px;
    box-shadow: inset 0px 0px 0px 2px #a9a8a6, 20px 0px 0px -2px #484848, 26px 0px #a9a8a6;
  }
  41% {
    left: 45px;
    bottom: 29px;
    width: 14px;
    height: 4px;
    box-shadow: inset 0px 0px 0px 2px #a9a8a6, 20px 0px 0px -2px #484848, 26px 0px #a9a8a6;
  }
  44% {
    left: 48px;
    bottom: 29px;
    width: 14px;
    height: 4px;
    box-shadow: inset 0px 0px 0px 2px #a9a8a6, 20px 0px 0px -2px #484848, 20px 0px #a9a8a6;
  }
  49%, 100% {
    left: 48px;
    bottom: 29px;
    width: 14px;
    height: 4px;
    box-shadow: inset 0px 0px 0px 0px #a9a8a6, 20px 0px 0px 0px #484848, 20px 0px #a9a8a6;
  }
}
@keyframes buttonsSSAnim {
  0%, 34% {
    left: 52px;
    bottom: 31px;
    width: 0px;
    height: 0px;
    box-shadow: inset 0px 0px 0px 2px #a9a8a6, 20px 0px 0px -2px #484848, 26px 0px #a9a8a6;
  }
  41% {
    left: 45px;
    bottom: 29px;
    width: 14px;
    height: 4px;
    box-shadow: inset 0px 0px 0px 2px #a9a8a6, 20px 0px 0px -2px #484848, 26px 0px #a9a8a6;
  }
  44% {
    left: 48px;
    bottom: 29px;
    width: 14px;
    height: 4px;
    box-shadow: inset 0px 0px 0px 2px #a9a8a6, 20px 0px 0px -2px #484848, 20px 0px #a9a8a6;
  }
  49%, 100% {
    left: 48px;
    bottom: 29px;
    width: 14px;
    height: 4px;
    box-shadow: inset 0px 0px 0px 0px #a9a8a6, 20px 0px 0px 0px #484848, 20px 0px #a9a8a6;
  }
}
#screenBack {
  position: absolute;
  background-color: #dddddd;
  border-radius: 2px;
  -webkit-animation: screenBackAnim 5s 2 both;
  -moz-animation: screenBackAnim 5s 2 both;
  -o-animation: screenBackAnim 5s 2 both;
  animation: screenBackAnim 5s 2 both;
}

@-webkit-keyframes screenBackAnim {
  0%, 25% {
    left: 63px;
    bottom: 125px;
    width: 0px;
    height: 64px;
  }
  31%, 100% {
    left: 21px;
    bottom: 125px;
    width: 84px;
    height: 64px;
  }
}
@-moz-keyframes screenBackAnim {
  0%, 25% {
    left: 63px;
    bottom: 125px;
    width: 0px;
    height: 64px;
  }
  31%, 100% {
    left: 21px;
    bottom: 125px;
    width: 84px;
    height: 64px;
  }
}
@-ms-keyframes screenBackAnim {
  0%, 25% {
    left: 63px;
    bottom: 125px;
    width: 0px;
    height: 64px;
  }
  31%, 100% {
    left: 21px;
    bottom: 125px;
    width: 84px;
    height: 64px;
  }
}
@keyframes screenBackAnim {
  0%, 25% {
    left: 63px;
    bottom: 125px;
    width: 0px;
    height: 64px;
  }
  31%, 100% {
    left: 21px;
    bottom: 125px;
    width: 84px;
    height: 64px;
  }
}
#screen {
  position: absolute;
  background-color: #494949;
  border-radius: 4px 4px 10px 4px;
  -webkit-animation: screenAnim 5s 2 both;
  -moz-animation: screenAnim 5s 2 both;
  -o-animation: screenAnim 5s 2 both;
  animation: screenAnim 5s 2 both;
}

@-webkit-keyframes screenAnim {
  0%, 28% {
    left: 68px;
    bottom: 131px;
    width: 0px;
    height: 0px;
  }
  33%, 36% {
    left: 26px;
    bottom: 100px;
    width: 74px;
    height: 64px;
  }
  40%, 42% {
    left: 26px;
    bottom: 114px;
    width: 74px;
    height: 64px;
  }
  48%, 100% {
    left: 8px;
    bottom: 100px;
    width: 110px;
    height: 96px;
  }
}
@-moz-keyframes screenAnim {
  0%, 28% {
    left: 68px;
    bottom: 131px;
    width: 0px;
    height: 0px;
  }
  33%, 36% {
    left: 26px;
    bottom: 100px;
    width: 74px;
    height: 64px;
  }
  40%, 42% {
    left: 26px;
    bottom: 114px;
    width: 74px;
    height: 64px;
  }
  48%, 100% {
    left: 8px;
    bottom: 100px;
    width: 110px;
    height: 96px;
  }
}
@-ms-keyframes screenAnim {
  0%, 28% {
    left: 68px;
    bottom: 131px;
    width: 0px;
    height: 0px;
  }
  33%, 36% {
    left: 26px;
    bottom: 100px;
    width: 74px;
    height: 64px;
  }
  40%, 42% {
    left: 26px;
    bottom: 114px;
    width: 74px;
    height: 64px;
  }
  48%, 100% {
    left: 8px;
    bottom: 100px;
    width: 110px;
    height: 96px;
  }
}
@keyframes screenAnim {
  0%, 28% {
    left: 68px;
    bottom: 131px;
    width: 0px;
    height: 0px;
  }
  33%, 36% {
    left: 26px;
    bottom: 100px;
    width: 74px;
    height: 64px;
  }
  40%, 42% {
    left: 26px;
    bottom: 114px;
    width: 74px;
    height: 64px;
  }
  48%, 100% {
    left: 8px;
    bottom: 100px;
    width: 110px;
    height: 96px;
  }
}
#jackBack {
  position: absolute;
  background-color: #646060;
  -webkit-animation: jackBackAnim 5s 2 both;
  -moz-animation: jackBackAnim 5s 2 both;
  -o-animation: jackBackAnim 5s 2 both;
  animation: jackBackAnim 5s 2 both;
}

@-webkit-keyframes jackBackAnim {
  0%, 21% {
    left: 11px;
    bottom: 136px;
    width: 0px;
    height: 0px;
  }
  25%, 31% {
    left: 6px;
    bottom: 132px;
    width: 12px;
    height: 12px;
  }
  36%, 100% {
    left: 6px;
    bottom: 138px;
    width: 12px;
    height: 12px;
  }
}
@-moz-keyframes jackBackAnim {
  0%, 21% {
    left: 11px;
    bottom: 136px;
    width: 0px;
    height: 0px;
  }
  25%, 31% {
    left: 6px;
    bottom: 132px;
    width: 12px;
    height: 12px;
  }
  36%, 100% {
    left: 6px;
    bottom: 138px;
    width: 12px;
    height: 12px;
  }
}
@-ms-keyframes jackBackAnim {
  0%, 21% {
    left: 11px;
    bottom: 136px;
    width: 0px;
    height: 0px;
  }
  25%, 31% {
    left: 6px;
    bottom: 132px;
    width: 12px;
    height: 12px;
  }
  36%, 100% {
    left: 6px;
    bottom: 138px;
    width: 12px;
    height: 12px;
  }
}
@keyframes jackBackAnim {
  0%, 21% {
    left: 11px;
    bottom: 136px;
    width: 0px;
    height: 0px;
  }
  25%, 31% {
    left: 6px;
    bottom: 132px;
    width: 12px;
    height: 12px;
  }
  36%, 100% {
    left: 6px;
    bottom: 138px;
    width: 12px;
    height: 12px;
  }
}
#jack {
  position: absolute;
  background-color: #494949;
  border-radius: 7px;
  -webkit-animation: jackAnim 5s 2 both;
  -moz-animation: jackAnim 5s 2 both;
  -o-animation: jackAnim 5s 2 both;
  animation: jackAnim 5s 2 both;
}

@-webkit-keyframes jackAnim {
  0%, 23% {
    left: 6px;
    bottom: 135px;
    width: 0px;
    height: 0px;
  }
  27%, 31% {
    left: 1px;
    bottom: 131px;
    width: 14px;
    height: 14px;
  }
  36%, 100% {
    left: 1px;
    bottom: 137px;
    width: 14px;
    height: 14px;
  }
}
@-moz-keyframes jackAnim {
  0%, 23% {
    left: 6px;
    bottom: 135px;
    width: 0px;
    height: 0px;
  }
  27%, 31% {
    left: 1px;
    bottom: 131px;
    width: 14px;
    height: 14px;
  }
  36%, 100% {
    left: 1px;
    bottom: 137px;
    width: 14px;
    height: 14px;
  }
}
@-ms-keyframes jackAnim {
  0%, 23% {
    left: 6px;
    bottom: 135px;
    width: 0px;
    height: 0px;
  }
  27%, 31% {
    left: 1px;
    bottom: 131px;
    width: 14px;
    height: 14px;
  }
  36%, 100% {
    left: 1px;
    bottom: 137px;
    width: 14px;
    height: 14px;
  }
}
@keyframes jackAnim {
  0%, 23% {
    left: 6px;
    bottom: 135px;
    width: 0px;
    height: 0px;
  }
  27%, 31% {
    left: 1px;
    bottom: 131px;
    width: 14px;
    height: 14px;
  }
  36%, 100% {
    left: 1px;
    bottom: 137px;
    width: 14px;
    height: 14px;
  }
}
#screen2 {
  position: absolute;
  background-color: #b7b28f;
  border-radius: 2px;
  -webkit-animation: screen2Anim 5s 2 both;
  -moz-animation: screen2Anim 5s 2 both;
  -o-animation: screen2Anim 5s 2 both;
  animation: screen2Anim 5s 2 both;
}

@-webkit-keyframes screen2Anim {
  0%, 44% {
    left: 59px;
    bottom: 151px;
    width: 0px;
    height: 0px;
  }
  48% {
    left: 54px;
    bottom: 146px;
    width: 10px;
    height: 10px;
  }
  52% {
    left: 22px;
    bottom: 146px;
    width: 80px;
    height: 10px;
  }
  60%, 100% {
    left: 22px;
    bottom: 112px;
    width: 80px;
    height: 74px;
  }
}
@-moz-keyframes screen2Anim {
  0%, 44% {
    left: 59px;
    bottom: 151px;
    width: 0px;
    height: 0px;
  }
  48% {
    left: 54px;
    bottom: 146px;
    width: 10px;
    height: 10px;
  }
  52% {
    left: 22px;
    bottom: 146px;

    width: 80px;
    height: 10px;
  }
  60%, 100% {
    left: 22px;
    bottom: 112px;
    width: 80px;
    height: 74px;
  }
}
@-ms-keyframes screen2Anim {
  0%, 44% {
    left: 59px;
    bottom: 151px;
    width: 0px;
    height: 0px;
  }
  48% {
    left: 54px;
    bottom: 146px;
    width: 10px;
    height: 10px;
  }
  52% {
    left: 22px;
    bottom: 146px;
    width: 80px;
    height: 10px;
  }
  60%, 100% {
    left: 22px;
    bottom: 112px;
    width: 80px;
    height: 74px;
  }
}
@keyframes screen2Anim {
  0%, 44% {
    left: 59px;
    bottom: 151px;
    width: 0px;
    height: 0px;
  }
  48% {
    left: 54px;
    bottom: 146px;
    width: 10px;
    height: 10px;
  }
  52% {
    left: 22px;
    bottom: 146px;
    width: 80px;
    height: 10px;
  }
  60%, 100% {
    left: 22px;
    bottom: 112px;
    width: 80px;
    height: 74px;
  }
}
#box {
  position: absolute;
  background-color: #ed2618;
  border-radius: 3px 3px 20px 3px;
  height: 206px;
  width: 125px;
  bottom: 0px;
  -webkit-animation: boxAnim 5s 2 both;
  -moz-animation: boxAnim 5s 2 both;
  -o-animation: boxAnim 5s 2 both;
  animation: boxAnim 5s 2 both;
}

@-webkit-keyframes boxAnim {
  0%, 67% {
    height: 0px;
    width: 125px;
    bottom: 206px;
  }
  80%, 100% {
    height: 206px;
    width: 125px;
    bottom: 0px;
  }
}
@-moz-keyframes boxAnim {
  0%, 67% {
    height: 0px;
    width: 125px;
    bottom: 206px;
  }
  80%, 100% {
    height: 206px;
    width: 125px;
    bottom: 0px;
  }
}
@-ms-keyframes boxAnim {
  0%, 67% {
    height: 0px;
    width: 125px;
    bottom: 206px;
  }
  80%, 100% {
    height: 206px;
    width: 125px;
    bottom: 0px;
  }
}
@keyframes boxAnim {
  0%, 67% {
    height: 0px;
    width: 125px;
    bottom: 206px;
  }
  80%, 100% {
    height: 206px;
    width: 125px;
    bottom: 0px;
  }
}
#gameboyText {
  position: absolute;
  left: 23px;
  bottom: 93px;
  height: 20px;
  width: 100px;
  font: 7px "gyre";
  color: #b7b28f;
  clip: rect(0px, 0px, 40px, 20px);
  -webkit-animation: gameboyTextAnim 5s 2 both;
  -moz-animation: gameboyTextAnim 5s 2 both;
  -o-animation: gameboyTextAnim 5s 2 both;
  animation: gameboyTextAnim 5s 2 both;
}

@-webkit-keyframes gameboyTextAnim {
  0%, 55% {
    clip: rect(0px, 0px, 20px, 0px);
  }
  60%, 100% {
    clip: rect(0px, 40px, 20px, 0px);
  }
}
@-moz-keyframes gameboyTextAnim {
  0%, 55% {
    clip: rect(0px, 0px, 20px, 0px);
  }
  60%, 100% {
    clip: rect(0px, 40px, 20px, 0px);
  }
}
@-ms-keyframes gameboyTextAnim {
  0%, 55% {
    clip: rect(0px, 0px, 20px, 0px);
  }
  60%, 100% {
    clip: rect(0px, 40px, 20px, 0px);
  }
}
@keyframes gameboyTextAnim {
  0%, 55% {
    clip: rect(0px, 0px, 20px, 0px);
  }
  60%, 100% {
    clip: rect(0px, 40px, 20px, 0px);
  }
}
#powerBack {
  position: absolute;
  background-color: #494949;
  width: 15px;
  height: 9px;
  left: 6px;
  bottom: 197px;
  -webkit-animation: powerBackAnim 5s 2 both;
  -moz-animation: powerBackAnim 5s 2 both;
  -o-animation: powerBackAnim 5s 2 both;
  animation: powerBackAnim 5s 2 both;
}

@-webkit-keyframes powerBackAnim {
  0%, 23% {
    height: 0px;
  }
  30%, 100% {
    height: 9px;
  }
}
@-moz-keyframes powerBackAnim {
  0%, 23% {
    height: 0px;
  }
  30%, 100% {
    height: 9px;
  }
}
@-ms-keyframes powerBackAnim {
  0%, 23% {
    height: 0px;
  }
  30%, 100% {
    height: 9px;
  }
}
@keyframes powerBackAnim {
  0%, 23% {
    height: 0px;
  }
  30%, 100% {
    height: 9px;
  }
}
#power {
  position: absolute;
  background-color: #494949;
  border-radius: 4px 4px 0px 0px / 2px 2px 0px 0px;
  width: 8px;
  height: 6px;
  visibility: visible;
  -webkit-animation: powerAnim 5s 2 both;
  -moz-animation: powerAnim 5s 2 both;
  -o-animation: powerAnim 5s 2 both;
  animation: powerAnim 5s 2 both;
}

@-webkit-keyframes powerAnim {
  0%, 42% {
    visibility: hidden;
    left: 9px;
    bottom: 197px;
  }
  43% {
    visibility: visible;
    left: 9px;
    bottom: 197px;
  }
  46%, 90% {
    visibility: visible;
    left: 9px;
    bottom: 202px;
  }
  92%, 100% {
    visibility: visible;
    left: 15px;
    bottom: 202px;
  }
}
@-moz-keyframes powerAnim {
  0%, 42% {
    visibility: hidden;
    left: 9px;
    bottom: 197px;
  }
  43% {
    visibility: visible;
    left: 9px;
    bottom: 197px;
  }
  46%, 90% {
    visibility: visible;
    left: 9px;
    bottom: 202px;
  }
  92%, 100% {
    visibility: visible;
    left: 15px;
    bottom: 202px;
  }
}
@-ms-keyframes powerAnim {
  0%, 42% {
    visibility: hidden;
    left: 9px;
    bottom: 197px;
  }
  43% {
    visibility: visible;
    left: 9px;
    bottom: 197px;
  }
  46%, 90% {
    visibility: visible;
    left: 9px;
    bottom: 202px;
  }
  92%, 100% {
    visibility: visible;
    left: 15px;
    bottom: 202px;
  }
}
@keyframes powerAnim {
  0%, 42% {
    visibility: hidden;
    left: 9px;
    bottom: 197px;
  }
  43% {
    visibility: visible;
    left: 9px;
    bottom: 197px;
  }
  46%, 90% {
    visibility: visible;
    left: 9px;
    bottom: 202px;
  }
  92%, 100% {
    visibility: visible;
    left: 15px;
    bottom: 202px;
  }
}
#powerLed {
  position: absolute;
  background-color: #202020;
  border-radius: 2px;
  width: 4px;
  height: 4px;
  left: 10px;
  bottom: 180px;
  -webkit-animation: powerLedAnim 5s 2 both;
  -moz-animation: powerLedAnim 5s 2 both;
  -o-animation: powerLedAnim 5s 2 both;
  animation: powerLedAnim 5s 2 both;
}

@-webkit-keyframes powerLedAnim {
  0%, 49% {
    width: 0px;
    height: 0px;
    left: 12px;
    bottom: 172px;
  }
  52%, 91% {
    background-color: #202020;
    width: 4px;
    height: 4px;
    left: 10px;
    bottom: 170px;
  }
  92%, 100% {
    background-color: red;
    width: 4px;
    height: 4px;
    left: 10px;
    bottom: 170px;
  }
}
@-moz-keyframes powerLedAnim {
  0%, 49% {
    width: 0px;
    height: 0px;
    left: 12px;
    bottom: 172px;
  }
  52%, 91% {
    background-color: #202020;
    width: 4px;
    height: 4px;
    left: 10px;
    bottom: 170px;
  }
  92%, 100% {
    background-color: red;
    width: 4px;
    height: 4px;
    left: 10px;
    bottom: 170px;
  }
}
@-ms-keyframes powerLedAnim {
  0%, 49% {
    width: 0px;
    height: 0px;
    left: 12px;
    bottom: 172px;
  }
  52%, 91% {
    background-color: #202020;
    width: 4px;
    height: 4px;
    left: 10px;
    bottom: 170px;
  }
  92%, 100% {
    background-color: red;
    width: 4px;
    height: 4px;
    left: 10px;
    bottom: 170px;
  }
}
@keyframes powerLedAnim {
  0%, 49% {
    width: 0px;
    height: 0px;
    left: 12px;
    bottom: 172px;
  }
  52%, 91% {
    background-color: #202020;
    width: 4px;
    height: 4px;
    left: 10px;
    bottom: 170px;
  }
  92%, 100% {
    background-color: red;
    width: 4px;
    height: 4px;
    left: 10px;
    bottom: 170px;
  }
}
#speakerFilter {
  position: absolute;
  background-color: #555;
  border-radius: 2px;
  width: 4px;
  height: 4px;
  left: 95px;
  bottom: 20px;
  visibility: visible;
  box-shadow: 3px -3px #555, 6px -6px #555, 9px -9px #555, 0px 6px #555,3px 3px #555, 6px 0px #555, 9px -3px #555, 12px -6px #555, 15px -9px #555, 3px 9px #555, 6px 6px #555, 9px 3px #555, 12px 0px #555, 15px -3px #555, 18px -6px #555, 9px 9px #555, 12px 6px #555, 15px 3px #555, 18px 0px #555;
  -webkit-animation: speakerFilterAnim 5s 2 both;
  -moz-animation: speakerFilterAnim 5s 2 both;
  -o-animation: speakerFilterAnim 5s 2 both;
  animation: speakerFilterAnim 5s 2 both;
}

@-webkit-keyframes speakerFilterAnim {
  0%, 75% {
    visibility: hidden;
  }
  76%, 100% {
    visibility: visible;
  }
}
@-moz-keyframes speakerFilterAnim {
  0%, 75% {
    visibility: hidden;
  }
  76%, 100% {
    visibility: visible;
  }
}
@-ms-keyframes speakerFilterAnim {
  0%, 75% {
    visibility: hidden;
  }
  76%, 100% {
    visibility: visible;
  }
}
@keyframes speakerFilterAnim {
  0%, 75% {
    visibility: hidden;
  }
  76%, 100% {
    visibility: visible;
  }
}
.slide-in-elliptic-bottom-bck {
	-webkit-animation: slide-in-elliptic-bottom-bck 0.7s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
	        animation: slide-in-elliptic-bottom-bck 0.7s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
}
		/* ----------------------------------------------
 * Generated by Animista on 2023-11-10 16:4:32
 * Licensed under FreeBSD License.
 * See http://animista.net/license for more info. 
 * w: http://animista.net, t: @cssanimista
 * ---------------------------------------------- */

/**
 * ----------------------------------------
 * animation slide-in-elliptic-bottom-bck
 * ----------------------------------------
 */
@-webkit-keyframes slide-in-elliptic-bottom-bck {
  0% {
    -webkit-transform: translateY(600px) rotateX(-30deg) scale(6.5);
            transform: translateY(600px) rotateX(-30deg) scale(6.5);
    -webkit-transform-origin: 50% -100%;
            transform-origin: 50% -100%;
    opacity: 0;
  }
  100% {
    -webkit-transform: translateY(0) rotateX(0) scale(1);
            transform: translateY(0) rotateX(0) scale(1);
    -webkit-transform-origin: 50% 500px;
            transform-origin: 50% 500px;
    opacity: 1;
  }
}
@keyframes slide-in-elliptic-bottom-bck {
  0% {
    -webkit-transform: translateY(600px) rotateX(-30deg) scale(6.5);
            transform: translateY(600px) rotateX(-30deg) scale(6.5);
    -webkit-transform-origin: 50% -100%;
            transform-origin: 50% -100%;
    opacity: 0;
  }
  100% {
    -webkit-transform: translateY(0) rotateX(0) scale(1);
            transform: translateY(0) rotateX(0) scale(1);
    -webkit-transform-origin: 50% 500px;
            transform-origin: 50% 500px;
    opacity: 1;
  }
}
.flip-vertical-left {
	-webkit-animation: flip-vertical-left 0.4s linear 1s infinite both;
	        animation: flip-vertical-left 0.4s linear 1s infinite both;
}
/* ----------------------------------------------
 * Generated by Animista on 2023-11-10 16:15:31
 * Licensed under FreeBSD License.
 * See http://animista.net/license for more info. 
 * w: http://animista.net, t: @cssanimista
 * ---------------------------------------------- */

/**
 * ----------------------------------------
 * animation flip-vertical-left
 * ----------------------------------------
 */
@-webkit-keyframes flip-vertical-left {
  0% {
    -webkit-transform: rotateY(0);
            transform: rotateY(0);
  }
  100% {
    -webkit-transform: rotateY(-180deg);
            transform: rotateY(-180deg);
  }
}
@keyframes flip-vertical-left {
  0% {
    -webkit-transform: rotateY(0);
            transform: rotateY(0);
  }
  100% {
    -webkit-transform: rotateY(-180deg);
            transform: rotateY(-180deg);
  }
}
.fade-out {
	-webkit-animation: fade-out 1s ease-out 2s both;
	        animation: fade-out 1s ease-out 2s both;
}
		/* ----------------------------------------------
 * Generated by Animista on 2023-11-10 16:22:41
 * Licensed under FreeBSD License.
 * See http://animista.net/license for more info. 
 * w: http://animista.net, t: @cssanimista
 * ---------------------------------------------- */

/**
 * ----------------------------------------
 * animation fade-out
 * ----------------------------------------
 */
@-webkit-keyframes fade-out {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
  }
}
@keyframes fade-out {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
  }
}
.bounce-in-top {
	-webkit-animation: bounce-in-top 1.1s 2s both;
	        animation: bounce-in-top 1.1s 2s both;
}
/* ----------------------------------------------
 * Generated by Animista on 2023-11-10 16:24:21
 * Licensed under FreeBSD License.
 * See http://animista.net/license for more info. 
 * w: http://animista.net, t: @cssanimista
 * ---------------------------------------------- */

/**
 * ----------------------------------------
 * animation bounce-in-top
 * ----------------------------------------
 */
@-webkit-keyframes bounce-in-top {
  0% {
    -webkit-transform: translateY(-500px);
            transform: translateY(-500px);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
    opacity: 0;
  }
  38% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
    opacity: 1;
  }
  55% {
    -webkit-transform: translateY(-65px);
            transform: translateY(-65px);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
  }
  72% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
  }
  81% {
    -webkit-transform: translateY(-28px);
            transform: translateY(-28px);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
  }
  90% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
  }
  95% {
    -webkit-transform: translateY(-8px);
            transform: translateY(-8px);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
  }
  100% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
  }
}
@keyframes bounce-in-top {
  0% {
    -webkit-transform: translateY(-500px);
            transform: translateY(-500px);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
    opacity: 0;
  }
  38% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
    opacity: 1;
  }
  55% {
    -webkit-transform: translateY(-65px);
            transform: translateY(-65px);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
  }
  72% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
  }
  81% {
    -webkit-transform: translateY(-28px);
            transform: translateY(-28px);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
  }
  90% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
  }
  95% {
    -webkit-transform: translateY(-8px);
            transform: translateY(-8px);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
  }
  100% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
  }
}
.bounce-in-top2 {
	-webkit-animation: bounce-in-top 1.1s 2.1s both;
	        animation: bounce-in-top 1.1s 2.1s both;
}
.bounce-in-top3 {
	-webkit-animation: bounce-in-top 1.1s 2.2s both;
	        animation: bounce-in-top 1.1s 2.2s both;
}
		.bounce-in-top4 {
	-webkit-animation: bounce-in-top 1.1s 2.3s both;
	        animation: bounce-in-top 1.1s 2.3s both;
}
		.bounce-in-top5 {
	-webkit-animation: bounce-in-top 1.1s 2.4s both;
	        animation: bounce-in-top 1.1s 2.4s both;
}
		.bounce-in-top6 {
	-webkit-animation: bounce-in-top 1.1s 2.5s both;
	        animation: bounce-in-top 1.1s 2.5s both;
}
		.bounce-in-top7 {
	-webkit-animation: bounce-in-top 1.1s 2.6s both;
	        animation: bounce-in-top 1.1s 2.6s both;
}
		.bounce-in-top8 {
	-webkit-animation: bounce-in-top 1.1s 2.7s both;
	        animation: bounce-in-top 1.1s 2.7s both;
}
		.bounce-in-top9 {
	-webkit-animation: bounce-in-top 1.1s 2.8s both;
	        animation: bounce-in-top 1.1s 2.8s both;
}
		.bounce-in-top10 {
	-webkit-animation: bounce-in-top 1.1s 2.9s both;
	        animation: bounce-in-top 1.1s 2.9s both;
}
		.bounce-in-top11 {
	-webkit-animation: bounce-in-top 1.1s 3s both;
	        animation: bounce-in-top 1.1s 3s both;
}
		.bounce-in-top12 {
	-webkit-animation: bounce-in-top 1.1s 3.1s both;
	        animation: bounce-in-top 1.1s 3.1s both;
}
		.text-pop-up-top {
	-webkit-animation: text-pop-up-top 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) infinite alternate both;
	        animation: text-pop-up-top 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) infinite alternate both;
}
		/* ----------------------------------------------
 * Generated by Animista on 2023-11-10 16:37:42
 * Licensed under FreeBSD License.
 * See http://animista.net/license for more info. 
 * w: http://animista.net, t: @cssanimista
 * ---------------------------------------------- */

/**
 * ----------------------------------------
 * animation text-pop-up-top
 * ----------------------------------------
 */
@-webkit-keyframes text-pop-up-top {
  0% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    -webkit-transform-origin: 50% 50%;
            transform-origin: 50% 50%;
    text-shadow: none;
  }
  100% {
    -webkit-transform: translateY(-50px);
            transform: translateY(-50px);
    -webkit-transform-origin: 50% 50%;
            transform-origin: 50% 50%;
    text-shadow: 0 1px 0 #cccccc, 0 2px 0 #cccccc, 0 3px 0 #cccccc, 0 4px 0 #cccccc, 0 5px 0 #cccccc, 0 6px 0 #cccccc, 0 7px 0 #cccccc, 0 8px 0 #cccccc, 0 9px 0 #cccccc, 0 50px 30px rgba(0, 0, 0, 0.3);
  }
}
@keyframes text-pop-up-top {
  0% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    -webkit-transform-origin: 50% 50%;
            transform-origin: 50% 50%;
    text-shadow: none;
  }
  100% {
    -webkit-transform: translateY(-50px);
            transform: translateY(-50px);
    -webkit-transform-origin: 50% 50%;
            transform-origin: 50% 50%;
    text-shadow: 0 1px 0 #cccccc, 0 2px 0 #cccccc, 0 3px 0 #cccccc, 0 4px 0 #cccccc, 0 5px 0 #cccccc, 0 6px 0 #cccccc, 0 7px 0 #cccccc, 0 8px 0 #cccccc, 0 9px 0 #cccccc, 0 50px 30px rgba(0, 0, 0, 0.3);
  }
}
.slide-in-blurred-tl {
	-webkit-animation: slide-in-blurred-tl 1s cubic-bezier(0.230, 1.000, 0.320, 1.000) 2.4s both;
	        animation: slide-in-blurred-tl 1s cubic-bezier(0.230, 1.000, 0.320, 1.000) 2.4s both;
}
		/* ----------------------------------------------
 * Generated by Animista on 2023-11-10 16:56:59
 * Licensed under FreeBSD License.
 * See http://animista.net/license for more info. 
 * w: http://animista.net, t: @cssanimista
 * ---------------------------------------------- */

/**
 * ----------------------------------------
 * animation slide-in-blurred-tl
 * ----------------------------------------
 */
@-webkit-keyframes slide-in-blurred-tl {
  0% {
    -webkit-transform: translate(-1000px, -1000px) skew(80deg, 10deg);
            transform: translate(-1000px, -1000px) skew(80deg, 10deg);
    -webkit-transform-origin: 100% 0%;
            transform-origin: 100% 0%;
    -webkit-filter: blur(40px);
            filter: blur(40px);
    opacity: 0;
  }
  100% {
    -webkit-transform: translate(0, 0) skew(0deg, 0deg);
            transform: translate(0, 0) skew(0deg, 0deg);
    -webkit-transform-origin: 50% 50%;
            transform-origin: 50% 50%;
    -webkit-filter: blur(0);
            filter: blur(0);
    opacity: 1;
  }
}
@keyframes slide-in-blurred-tl {
  0% {
    -webkit-transform: translate(-1000px, -1000px) skew(80deg, 10deg);
            transform: translate(-1000px, -1000px) skew(80deg, 10deg);
    -webkit-transform-origin: 100% 0%;
            transform-origin: 100% 0%;
    -webkit-filter: blur(40px);
            filter: blur(40px);
    opacity: 0;
  }
  100% {
    -webkit-transform: translate(0, 0) skew(0deg, 0deg);
            transform: translate(0, 0) skew(0deg, 0deg);
    -webkit-transform-origin: 50% 50%;
            transform-origin: 50% 50%;
    -webkit-filter: blur(0);
            filter: blur(0);
    opacity: 1;
  }
}
.swirl-out-bck {
	-webkit-animation: swirl-out-bck 0.6s ease-in 10s both;
	        animation: swirl-out-bck 0.6s ease-in 10s both;
}
		/* ----------------------------------------------
 * Generated by Animista on 2023-11-10 18:37:56
 * Licensed under FreeBSD License.
 * See http://animista.net/license for more info. 
 * w: http://animista.net, t: @cssanimista
 * ---------------------------------------------- */

/**
 * ----------------------------------------
 * animation swirl-out-bck
 * ----------------------------------------
 */
@-webkit-keyframes swirl-out-bck {
  0% {
    -webkit-transform: rotate(0) scale(1);
            transform: rotate(0) scale(1);
    opacity: 1;
  }
  100% {
    -webkit-transform: rotate(-540deg) scale(0);
            transform: rotate(-540deg) scale(0);
    opacity: 0;
  }
}
@keyframes swirl-out-bck {
  0% {
    -webkit-transform: rotate(0) scale(1);
            transform: rotate(0) scale(1);
    opacity: 1;
  }
  100% {
    -webkit-transform: rotate(-540deg) scale(0);
            transform: rotate(-540deg) scale(0);
    opacity: 0;
  }
}

	</style>
</head>

<body>
	<br>
	<h1 class="text-pop-up-top"><zx class="bounce-in-top">S</zx><zx class="bounce-in-top2">P</zx><zx class="bounce-in-top3">I</zx><zx class="bounce-in-top4">N</zx><zx class="bounce-in-top5">N</zx><zx class="bounce-in-top6">I</zx><zx class="bounce-in-top7">N</zx><zx class="bounce-in-top8">G</zx> <zx class="bounce-in-top9">L</zx><zx class="bounce-in-top10">E</zx><zx class="bounce-in-top11">A</zx><zx class="bounce-in-top12">F</zx></h1>
	<br>
	<a href="./easteregg.html"><img src="images/3dgifmaker02074.gif" class="slide-in-elliptic-bottom-bck"></a>
	<div class="hidden_elements">
	<a href="">Go To Bug Land</a>
	</div>
	<div class="fade-out">
<div class="loader-wrapper">
	<div class="loader">
    <div class="roller"></div>
    <div class="roller"></div>
  </div>
  
  <div id="loader2" class="loader">
    <div class="roller"></div>
    <div class="roller"></div>
  </div>
  
  <div id="loader3" class="loader">
    <div class="roller"></div>
    <div class="roller"></div>
  </div>
</div>
	</div>
	<div id="dunce" class="slide-in-blurred-tl">
	<div class="swirl-out-bck">
  <div id='container'>
  <div id='back'></div>
  <div id='border'></div>
  <div id='card3'></div>
  <div id='card2'></div>
  <div id='chip2'></div>
  <div id='screenBack'></div>
  <div id='card1'></div>
  <div id='speaker'></div>
  <div id='chip'></div>
  <div id='chipPinL'></div>
  <div id='chipPinR'></div>
  <div id='ec1'></div>
  <div id='volumeWheelBack'></div>
  <div id='volumeWheel'></div>
  <div id='joystickBack'></div>
  <div id='buttonsABBack'></div>
  <div id='buttonsSSBack'></div>
  <div id='jackBack'></div>
  <div id='jack'></div>
  <div id='ec2'></div>
  <div id='powerBack'></div>
  <div id='power'></div>
  <div id='box'></div>
  <div id='screen'></div>
  <div id='screen2'></div>
  <div id='joystickCross1'></div>
  <div id='joystickCross2'></div>
  <div id='buttonsSS'></div>
  <div id='buttonsSSText'></div>
  <div id='buttonsAB'></div>
  <div id='buttonsABText'></div>
  <div id='gameboyText'>SILLY BUG</div>
  <div id='powerLed'></div>
  <div id='speakerFilter'></div>
</div>
	</div>
	</div>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
	<script>
	$(document).ready(function() {
  'use strict';
  let buff = '';
  $('body').on('keyup', function(event) {
    
    
    buff += event.originalEvent.key;
    // console.log('buff.length', buff.length, buff);
    if (buff.length >= 5) {
      const lastFive = buff.substr(buff.length - 5);
      if(lastFive.toLowerCase() == 'billy') {
        $('.hidden_elements').addClass('open');
      }
    }
  });
});
	</script>
</body>
</html>