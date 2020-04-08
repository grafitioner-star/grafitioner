body {
	/*background-color: #FFDAB9;	*/
	background-color: #000;
	-webkit-transition:background-color linear 5s;
	-moz-transition:background-color linear 5s;
	-o-transition:background-color linear 5s;
	-ms-transition:background-color linear 5s;
	transition:background-color linear 5s;
	overflow-x:hidden;
}
.container {
	display: none;
}
.peach {
	background-color: #FFDAB9;
	
}
.peach-after {
	-webkit-animation:peach_alive linear 8s infinite;
	-moz-animation:peach_alive linear 8s infinite;
	-o-animation:peach_alive linear 8s infinite;
	-ms-animation:peach_alive linear 8s infinite;
	animation:peach_alive linear 8s infinite;
}

@-webkit-keyframes peach_alive {
	0%{
		background-color: #FFDAB9;
	}
	25%{
		background-color: #FFE4B5;
	}
	50%{
		background-color: #FFDAB9;
	}
	75%{
		background-color: #FFEFD5;
	}
	100%{
		background-color: #FFDAB9;
	}
}
@-moz-keyframes peach_alive {
	0%{
		background-color: #FFDAB9;
	}
	25%{
		background-color: #FFE4B5;
	}
	50%{
		background-color: #FFDAB9;
	}
	75%{
		background-color: #FFEFD5;
	}
	100%{
		background-color: #FFDAB9;
	}
}

@-o-keyframes peach_alive {
	0%{
		background-color: #FFDAB9;
	}
	25%{
		background-color: #FFE4B5;
	}
	50%{
		background-color: #FFDAB9;
	}
	75%{
		background-color: #FFEFD5;
	}
	100%{
		background-color: #FFDAB9;
	}
}

@-ms-keyframes peach_alive {
	0%{
		background-color: #FFDAB9;
	}
	25%{
		background-color: #FFE4B5;
	}
	50%{
		background-color: #FFDAB9;
	}
	75%{
		background-color: #FFEFD5;
	}
	100%{
		background-color: #FFDAB9;
	}
}

@keyframes peach_alive {
	0%{
		background-color: #FFDAB9;
	}
	25%{
		background-color: #FFE4B5;
	}
	50%{
		background-color: #FFDAB9;
	}
	75%{
		background-color: #FFEFD5;
	}
	100%{
		background-color: #FFDAB9;
	}
}


.bulb {
	width: 50px;
	height: 50px;
	margin: auto;
	background-repeat: no-repeat no-repeat;
	background-position:center 0px;
	background-size: 50px 50px;
}

.bulb-holder {
	height: 70px;
}

.bulb-glow-yellow {
	background-image: url('bulb_yellow.png');
	-webkit-animation: bulb_glow_yellow linear 5s;
	-moz-animation: bulb_glow_yellow linear 5s;
	-o-animation: bulb_glow_yellow linear 5s;
	-ms-animation: bulb_glow_yellow linear 5s;
	animation: bulb_glow_yellow linear 5s;
}

@-webkit-keyframes bulb_glow_yellow {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_yellow.png');
		opacity: 1;
	}
}
@-moz-keyframes bulb_glow_yellow {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_yellow.png');
		opacity: 1;
	}
}
@-o-keyframes bulb_glow_yellow {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_yellow.png');
		opacity: 1;
	}
}
@-ms-keyframes bulb_glow_yellow {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_yellow.png');
		opacity: 1;
	}
}
@keyframes bulb_glow_yellow {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_yellow.png');
		opacity: 1;
	}
}

.bulb-glow-red {
	background-image: url('bulb_red.png');
	-webkit-animation: bulb_glow_red linear 5s;
	-moz-animation: bulb_glow_red linear 5s;
	-o-animation: bulb_glow_red linear 5s;
	-ms-animation: bulb_glow_red linear 5s;
	animation: bulb_glow_red linear 5s;
}

@-webkit-keyframes bulb_glow_red {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_red.png');
		opacity: 1;
	}
}
@-moz-keyframes bulb_glow_red {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_red.png');
		opacity: 1;
	}
}
@-o-keyframes bulb_glow_red {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_red.png');
		opacity: 1;
	}
}
@-ms-keyframes bulb_glow_red {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_red.png');
		opacity: 1;
	}
}
@keyframes bulb_glow_red {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_red.png');
		opacity: 1;
	}
}
.bulb-glow-blue {
	background-image: url('bulb_blue.png');
	-webkit-animation: bulb_glow_blue linear 5s;
	-moz-animation: bulb_glow_blue linear 5s;
	-o-animation: bulb_glow_blue linear 5s;
	-ms-animation: bulb_glow_blue linear 5s;
	animation: bulb_glow_blue linear 5s;
}

@-webkit-keyframes bulb_glow_blue {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_blue.png');
		opacity: 1;
	}
}
@-moz-keyframes bulb_glow_blue {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_blue.png');
		opacity: 1;
	}
}
@-o-keyframes bulb_glow_blue {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_blue.png');
		opacity: 1;
	}
}
@-ms-keyframes bulb_glow_blue {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_blue.png');
		opacity: 1;
	}
}
@keyframes bulb_glow_blue {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_blue.png');
		opacity: 1;
	}
}

.bulb-glow-green {
	background-image: url('bulb_green.png');
	-webkit-animation: bulb_glow_green linear 5s;
	-moz-animation: bulb_glow_green linear 5s;
	-o-animation: bulb_glow_green linear 5s;
	-ms-animation: bulb_glow_green linear 5s;
	animation: bulb_glow_green linear 5s;
}

@-webkit-keyframes bulb_glow_green {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_green.png');
		opacity: 1;
	}
}
@-moz-keyframes bulb_glow_green {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_green.png');
		opacity: 1;
	}
}
@-o-keyframes bulb_glow_green {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_green.png');
		opacity: 1;
	}
}
@-ms-keyframes bulb_glow_green {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_green.png');
		opacity: 1;
	}
}
@keyframes bulb_glow_green {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_green.png');
		opacity: 1;
	}
}

.bulb-glow-pink {
	background-image: url('bulb_pink.png');
	-webkit-animation: bulb_glow_pink linear 5s;
	-moz-animation: bulb_glow_pink linear 5s;
	-o-animation: bulb_glow_pink linear 5s;
	-ms-animation: bulb_glow_pink linear 5s;
	animation: bulb_glow_pink linear 5s;
}

@-webkit-keyframes bulb_glow_pink {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_pink.png');
		opacity: 1;
	}
}
@-moz-keyframes bulb_glow_pink {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_pink.png');
		opacity: 1;
	}
}
@-o-keyframes bulb_glow_pink {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_pink.png');
		opacity: 1;
	}
}
@-ms-keyframes bulb_glow_pink {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_pink.png');
		opacity: 1;
	}
}
@keyframes bulb_glow_pink {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_pink.png');
		opacity: 1;
	}
}

.bulb-glow-orange {
	background-image: url('bulb_orange.png');
	-webkit-animation: bulb_glow_orange linear 5s;
	-moz-animation: bulb_glow_orange linear 5s;
	-o-animation: bulb_glow_orange linear 5s;
	-ms-animation: bulb_glow_orange linear 5s;
	animation: bulb_glow_orange linear 5s;
}

@-webkit-keyframes bulb_glow_orange {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_orange.png');
		opacity: 1;
	}
}
@-moz-keyframes bulb_glow_orange {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_orange.png');
		opacity: 1;
	}
}
@-o-keyframes bulb_glow_orange {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_orange.png');
		opacity: 1;
	}
}
@-ms-keyframes bulb_glow_orange {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_orange.png');
		opacity: 1;
	}
}
@keyframes bulb_glow_orange {
	0%{
		background-image: url('bulb.png');
		opacity: 0;
	}
	50%{
		opacity: 1;
	}
	100%{
		background-image: url('bulb_orange.png');
		opacity: 1;
	}
}


/*after music*/
.bulb-glow-yellow-after {
	background-image: url('bulb_yellow.png');
	-webkit-animation: bulb_glow_yellow_after linear 1s infinite;
	-moz-animation: bulb_glow_yellow_after linear 1s infinite;
	-o-animation: bulb_glow_yellow_after linear 1s infinite;
	-ms-animation: bulb_glow_yellow_after linear 1s infinite;
	animation: bulb_glow_yellow_after linear 1s infinite;
}

@-webkit-keyframes bulb_glow_yellow_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_yellow.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-moz-keyframes bulb_glow_yellow_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_yellow.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-o-keyframes bulb_glow_yellow_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_yellow.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-ms-keyframes bulb_glow_yellow_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_yellow.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@keyframes bulb_glow_yellow_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_yellow.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}

.bulb-glow-red-after {
	background-image: url('bulb_red.png');
	-webkit-animation: bulb_glow_red_after linear 1.2s infinite;
	-moz-animation: bulb_glow_red_after linear 1.2s infinite;
	-o-animation: bulb_glow_red_after linear 1.2s infinite;
	-ms-animation: bulb_glow_red_after linear 1.2s infinite;
	animation: bulb_glow_red_after linear 1.2s infinite;
}

@-webkit-keyframes bulb_glow_red_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_red.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-moz-keyframes bulb_glow_red_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_red.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-o-keyframes bulb_glow_red_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_red.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-ms-keyframes bulb_glow_red_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_red.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@keyframes bulb_glow_red_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_red.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}

.bulb-glow-blue-after {
	background-image: url('bulb_blue.png');
	-webkit-animation: bulb_glow_blue_after linear 1.4s infinite;
	-moz-animation: bulb_glow_blue_after linear 1.4s infinite;
	-o-animation: bulb_glow_blue_after linear 1.4s infinite;
	-ms-animation: bulb_glow_blue_after linear 1.4s infinite;
	animation: bulb_glow_blue_after linear 1.4s infinite;
}

@-webkit-keyframes bulb_glow_blue_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_blue.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-moz-keyframes bulb_glow_blue_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_blue.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-o-keyframes bulb_glow_blue_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_blue.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-ms-keyframes bulb_glow_blue_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_blue.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@keyframes bulb_glow_blue_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_blue.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
.bulb-glow-green-after {
	background-image: url('bulb_green.png');
	-webkit-animation: bulb_glow_green_after linear 1.8s infinite;
	-moz-animation: bulb_glow_green_after linear 1.8s infinite;
	-o-animation: bulb_glow_green_after linear 1.8s infinite;
	-ms-animation: bulb_glow_green_after linear 1.8s infinite;
	animation: bulb_glow_green_after linear 1.8s infinite;
}

@-webkit-keyframes bulb_glow_green_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_green.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}

@-moz-keyframes bulb_glow_green_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_green.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-o-keyframes bulb_glow_green_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_green.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-ms-keyframes bulb_glow_green_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_green.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@keyframes bulb_glow_green_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_green.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
.bulb-glow-pink-after {
	background-image: url('bulb_pink.png');
	-webkit-animation: bulb_glow_pink_after linear 2s infinite;
	-moz-animation: bulb_glow_pink_after linear 2s infinite;
	-o-animation: bulb_glow_pink_after linear 2s infinite;
	-ms-animation: bulb_glow_pink_after linear 2s infinite;
	animation: bulb_glow_pink_after linear 2s infinite;
}

@-webkit-keyframes bulb_glow_pink_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_pink.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-moz-keyframes bulb_glow_pink_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_pink.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-o-keyframes bulb_glow_pink_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_pink.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-ms-keyframes bulb_glow_pink_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_pink.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@keyframes bulb_glow_pink_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_pink.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
.bulb-glow-orange-after {
	background-image: url('bulb_orange.png');
	-webkit-animation: bulb_glow_orange_after linear 2.2s infinite;
	-moz-animation: bulb_glow_orange_after linear 2.2s infinite;
	-o-animation: bulb_glow_orange_after linear 2.2s infinite;
	-ms-animation: bulb_glow_orange_after linear 2.2s infinite;
	animation: bulb_glow_orange_after linear 2.2s infinite;
}

@-webkit-keyframes bulb_glow_orange_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_orange.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-moz-keyframes bulb_glow_orange_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_orange.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-o-keyframes bulb_glow_orange_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_orange.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@-ms-keyframes bulb_glow_orange_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_orange.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
@keyframes bulb_glow_orange_after {
	0%{
		background-image: url('bulb.png');
	}
	50%{
		background-image: url('bulb_orange.png');
	}
	100%{
		background-image: url('bulb.png');
	}
}
audio {
	display: none;
}

.bannar {
	max-width: 100%;
	-webkit-transform:translate(0px,-500px);
	-moz-transform:translate(0px,-500px);
	-o-transform:translate(0px,-500px);
	-ms-transform:translate(0px,-500px);
	transform:translate(0px,-500px);

}
.bannar-come {
	-webkit-animation: bannar_come linear 6s;
	-webkit-transform:translate(0px,0px);
	-moz-animation: bannar_come linear 6s;
	-moz-transform:translate(0px,0px);
	-o-animation: bannar_come linear 6s;
	-o-transform:translate(0px,0px);
	-ms-animation: bannar_come linear 6s;
	-ms-transform:translate(0px,0px);
	animation: bannar_come linear 6s;
	transform:translate(0px,0px);
}
@-webkit-keyframes bannar_come {
	0%{
		-webkit-transform:translate(0px,-1000px);
	}
	33%{
		-webkit-transform:translate(0px,0px);
		-webkit-transform:rotate(10deg);
		/*-webkit-transform:scale(1.5);*/
	}
	66% {
		-webkit-transform:translate(0px,100px);
		-webkit-transform:rotate(-10deg);
	}
	100% {
		-webkit-transform:translate(0px,0px);
	}
}
@-moz-keyframes bannar_come {
	0%{
		-moz-transform:translate(0px,-1000px);
	}
	33%{
		-moz-transform:translate(0px,0px);
		-moz-transform:rotate(10deg);
		/*-webkit-transform:scale(1.5);*/
	}
	66% {
		-moz-transform:translate(0px,100px);
		-moz-transform:rotate(-10deg);
	}
	100% {
		-moz-transform:translate(0px,0px);
	}
}
@-o-keyframes bannar_come {
	0%{
		-o-transform:translate(0px,-1000px);
	}
	33%{
		-o-transform:translate(0px,0px);
		-o-transform:rotate(10deg);
		/*-webkit-transform:scale(1.5);*/
	}
	66% {
		-o-transform:translate(0px,100px);
		-o-transform:rotate(-10deg);
	}
	100% {
		-o-transform:translate(0px,0px);
	}
}
@-ms-keyframes bannar_come {
	0%{
		-ms-transform:translate(0px,-1000px);
	}
	33%{
		-ms-transform:translate(0px,0px);
		-ms-transform:rotate(10deg);
		/*-webkit-transform:scale(1.5);*/
	}
	66% {
		-ms-transform:translate(0px,100px);
		-ms-transform:rotate(-10deg);
	}
	100% {
		-ms-transform:translate(0px,0px);
	}
}o
@keyframes bannar_come {
	0%{
		transform:translate(0px,-1000px);
	}
	33%{
		transform:translate(0px,0px);
		transform:rotate(10deg);
		/*-webkit-transform:scale(1.5);*/
	}
	66% {
		transform:translate(0px,100px);
		transform:rotate(-10deg);
	}
	100% {
		transform:translate(0px,0px);
	}
}

.balloons {
	position: fixed;
	bottom: -200px;
	opacity: 0.6;
	z-index: 99;
	width: 100px;
	height: 183px;
	background-repeat: no-repeat no-repeat;
	background-size: 100px 183px;
}
.balloons h2 {
	text-transform: uppercase;
	font-family: 'Signika', sans-serif;
	font-size: 50px;
	color: #BF4136;
	text-shadow: 5px 5px 5px #FFF;
	display: none;
}
#b1,#b11 {
	background-image: url('b1.png');
}
#b2,#b22 {
	background-image: url('b2.png');
}
#b3,#b33 {
	background-image: url('b3.png');
}
#b4,#b44{
	background-image: url('b4.png');
}
#b5,#b55{
	background-image: url('b5.png');
}
#b6,#b66{
	background-image: url('b6.png');
}
#b7,#b77{
	background-image: url('b7.png');
}
.balloons-rotate-behaviour-one {
	-webkit-animation: balloons_rotate_one linear 10s infinite;
	-webkit-transform: rotate(30deg);
	-moz-animation: balloons_rotate_one linear 10s infinite;
	-moz-transform: rotate(30deg);
	-o-animation: balloons_rotate_one linear 10s infinite;
	-o-transform: rotate(30deg);
	-ms-animation: balloons_rotate_one linear 10s infinite;
	-ms-transform: rotate(30deg);
	animation: balloons_rotate_one linear 10s infinite;
	transform: rotate(30deg);
}
@-webkit-keyframes balloons_rotate_one {
	0% {
		-webkit-transform: rotate(30deg);
	}
	50% {
		-webkit-transform: rotate(-30deg);
	}
	100% {
		-webkit-transform: rotate(30deg);
	}
}
@-moz-keyframes balloons_rotate_one {
	0% {
		-moz-transform: rotate(30deg);
	}
	50% {
		-moz-transform: rotate(-30deg);
	}
	100% {
		-moz-transform: rotate(30deg);
	}
}
@-o-keyframes balloons_rotate_one {
	0% {
		-o-transform: rotate(30deg);
	}
	50% {
		-o-transform: rotate(-30deg);
	}
	100% {
		-o-transform: rotate(30deg);
	}
}
@-ms-keyframes balloons_rotate_one {
	0% {
		-ms-transform: rotate(30deg);
	}
	50% {
		-ms-transform: rotate(-30deg);
	}
	100% {
		-ms-transform: rotate(30deg);
	}
}
@keyframes balloons_rotate_one {
	0% {
		transform: rotate(30deg);
	}
	50% {
		transform: rotate(-30deg);
	}
	100% {
		transform: rotate(30deg);
	}
}
.balloons-rotate-behaviour-two {
	-webkit-animation: balloons_rotate_two linear 10s infinite;
	-webkit-transform: rotate(-20deg);
	-moz-animation: balloons_rotate_two linear 10s infinite;
	-moz-transform: rotate(-20deg);
	-o-animation: balloons_rotate_two linear 10s infinite;
	-o-transform: rotate(-20deg);
	-ms-animation: balloons_rotate_two linear 10s infinite;
	-ms-transform: rotate(-20deg);
	animation: balloons_rotate_two linear 10s infinite;
	transform: rotate(-20deg);
}
@-webkit-keyframes balloons_rotate_two {
	0% {
		-webkit-transform: rotate(-20deg);
	}
	50% {
		-webkit-transform: rotate(20deg);
	}
	100% {
		-webkit-transform: rotate(-20deg);
	}
}
@-moz-keyframes balloons_rotate_two {
	0% {
		-moz-transform: rotate(-20deg);
	}
	50% {
		-moz-transform: rotate(20deg);
	}
	100% {
		-moz-transform: rotate(-20deg);
	}
}
@-o-keyframes balloons_rotate_two {
	0% {
		-o-transform: rotate(-20deg);
	}
	50% {
		-o-transform: rotate(20deg);
	}
	100% {
		-o-transform: rotate(-20deg);
	}
}
@-ms-keyframes balloons_rotate_two {
	0% {
		-ms-transform: rotate(-20deg);
	}
	50% {
		-ms-transform: rotate(20deg);
	}
	100% {
		-ms-transform: rotate(-20deg);
	}
}
@keyframes balloons_rotate_two {
	0% {
		transform: rotate(-20deg);
	}
	50% {
		transform: rotate(20deg);
	}
	100% {
		transform: rotate(-20deg);
	}
}

.balloon-border{
	position: fixed;
	top:100%;
	opacity: 0.5;
	z-index: 9999;
}
.control-panel {
	position: fixed;
	bottom: 0;
	padding:10px 0px 10px 0px;
}
#play, #bannar_coming, #balloons_flying,#cake_fadein,#light_candle,#wish_message,#story {
	display: none;
}

.cake-cover {
	margin-top: 50px;
}
.message {
	margin-top: 200px;
	display: none;
}
.message p {
	font-family: 'Signika', sans-serif;
	font-size: 30px;
	text-transform: uppercase;
	color: #C4515C;
	text-shadow: 2px 2px 2px #FFF;
	display: none;
	font-weight: bold;
}

.btn-primary {
        border-color: #466baf;
        padding: 10px;
        text-transform: uppercase;
        font-family: 'Signika', sans-serif;
        font-weight: 700;
        color: #fff;
        background-color: #466baf;
}
    .btn-primary:hover,
    .btn-primary:focus,
    .btn-primary:active,
    .btn-primary.active,
    .open .dropdown-toggle.btn-primary {
        border-color: #fff;
        color: #fff;
        background-color: #466baf;
    }



    /*controlling tablet width*/
    /*@media only screen and (max-width: 720px){
    	.container {
    		-webkit-transform: scale(0.9);
    	}
    }*/
