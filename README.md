# Estuss.github.io

<!-- It-Студия -->
<!-- Created by Dmitriy Kozlov -->

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "https://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="https://www.w3.org/1999/xhtml">

<head>
	
	<title>IT-Студия</title>

	<!-- Indexing from Google -->
	<meta name="google-site-verification" content="6cQgxZP7A4GA_2e3LIdhXDnlXuZSpFxu8NDL2qjskX0" />
	
	<!-- Responsiveness and UTF-8 encoding -->
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<meta charset="utf-8" name="viewport" content="width=device-width, minimum-scale=1.0, maximum-scale=1.0" />

	<!-- Icon -->
	<link rel="shortcut icon" href="./img/code-slash-outline.svg" type="image/png">
	
	<!-- CSS -->
	<link rel="stylesheet" href="./css/style.css">
	<link rel="stylesheet" href="./css/Animation.css">
	<link rel="stylesheet" href="./css/Media.css" id="theme-link">

	<!-- WoW-Css -->
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.0/animate.min.css">

	<!-- FontAwesome -->
	<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css">

	<!-- BootsTrap framework -->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
		integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

</head>

<body>

	<!-- Header -->

	<div id="wrapper">
		<div id="header" class="clearfix wow flash">
			<div class="container">
				<div class="logo" id="logo"><a href="#home">IT-СТУДИЯ</a></div>
				<ul class="nav" id="navJS">
					<li><a href="#skills">Обо мне</a></li>
					<li><a href="#portfolio">Портфолио</a></li>
					<li><a href="#services">Ещё</a></li>
					<li><a href="#footer">Контакты</a></li>
					<li>
						<div class="toggle">
							<div class="theme-button" id="theme-button"></div>
						</div>
					</li>
				</ul>
			</div>
		</div>
		<div id="home" mame="home">
			<div id="welcome" class="container wow bounceIn">
				<h3>Добро пожаловать!</h3>
				<h1>It-студия Дмитрия Козлова</h1>
				<a href="#footer" class="btn btn-warn" id="button_caption">
					<p id="button_text">Хочу в It-студию!</p>
				</a>
			</div>
		</div>
	</div>

	<!-- About me -->

	<div id="skills">
		<div class="container">
			<h2 class="title wow fadeIn">Мои навыки</h2>
			<p class="descr wow fadeIn">Одни из большинства</p>
			<div class="row justify-content-center wow fadeIn">
				<div class="col-lg-12">
					<div id="circles" class="row text-center">
						<div class="col-lg-4" id="person1">
							<img src="./img/python.png" alt="">
							<h4>Python</h4>
							<p class="descr">Python очень важен для любого Web-Программиста, поэтому
								я его активно использую для своих проектов</p>
						</div>
						<div class="col-lg-4" id="person2">
							<img src="./img/bootstrap.png" alt="">
							<h4>Bootstrap</h4>
							<p class="descr">Фреймворк Bootstrap помогает делать сайт адаптивным и с крутым стилем</p>
						</div>
						<div class="col-lg-4" id="person3">
							<img src="./img/js.png" alt="">
							<h4>JavaScript</h4>
							<p class="descr">JavaScript позволяет мне расширять свои знания в сфере
								Web-Программирования каждый день</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>

	<!-- Portfolio -->

	<div id="portfolio" name="portfolio">
		<div class="container">
			<h2 class="title wow fadeIn">Моё портфолио</h2>
			<p class="descr wow fadeIn">Все мои проекты сосредоточены здесь</p>
		</div>


		<div class="container" id="Container">

			<section id="Portfolio" class="text-center">
				<h2 class="mb-5 font-weight-bold wow fadeIn">Проекты</h2>

				<div class="row">
					<div class="col-lg-4 col-md-6 mb-4">
						<div class="view overlay zoom wow bounceIn">
							<a class="lake" target="_blank" href="./subPages/index.html" title="" alt="Мой первый сайт-визитка на GitHub.com, который я написал в 9 лет! (Исторически важное событие)">
							<img src="./img/PORTFOLIO_1.jpg" alt="" class="fluid"></img></a>
							<h4 class="my-4 font-weight-bold mb-5">Проект #1</h4>
							<!-- <div class="line_caption col-lg-4"></div> -->
						</div>
					</div>

					<div class="col-lg-4 col-md-6 mb-4">
						<div class="view overlay zoom wow bounceIn">
							<a class="lake" target="_blank" href="./subPages/JS_Game/index.html" title="" alt="Игра на JavaScript (Бета-тестирование, ещё в разработке...)">
							<img src="./img/PORTFOLIO_2.jpg" alt="" class="fluid"></img></a>
							<h4 class="my-4 font-weight-bold mb-5">Проект #2</h4>
							<!-- <div class="line_caption col-lg-4"></div> -->
						</div>
					</div>

					<div class="col-lg-4 col-md-6 mb-4">
						<div class="view overlay zoom wow bounceIn">
							<a class="lake" href="#portfolio" title="" alt="Проект №3 готовится к своему звездному часу!">
							<img src="./img/PORTFOLIO_3.jpg" alt="" class="fluid"></img></a>
							<h4 class="my-4 font-weight-bold mb-5">Проект #3</h4>
							<!-- <div class="line_caption col-lg-4"></div> -->
						</div>
					</div>

					<div class="col-lg-4 col-md-6 mb-4">
						<div class="view overlay zoom wow bounceIn">
							<a class="lake" href="#portfolio" title="" alt="Проект №4 готовится к своему звездному часу!">
							<img src="./img/PORTFOLIO_4.jpg" alt="" class="fluid"></img></a>
							<h4 class="my-4 font-weight-bold">Проект #4</h4>
							<!-- <div class="line_caption col-lg-4"></div> -->
						</div>
					</div>

					<div class="col-lg-4 col-md-6 mb-4">
						<div class="view overlay zoom wow bounceIn">
							<a class="lake" href="#portfolio" title=""
								alt="Проект №5 готовится к своему звездному часу!">
							<img src="./img/PORTFOLIO_5.jpg" alt="" class="fluid"></img></a>
							<h4 class="my-4 font-weight-bold">Проект #5</h4>
							<!-- <div class="line_caption col-lg-4"></div> -->
						</div>
					</div>

					<div class="col-lg-4 col-md-6 mb-4">
						<div class="view overlay zoom wow bounceIn">
							<a class="lake" href="#portfolio" title="" alt="Проект №6 готовится к своему звездному часу!">
							<img src="./img/PORTFOLIO_6.jpg" alt="" class="fluid"></img></a>
							<h4 class="my-4 font-weight-bold">Проект #6</h4>
							<!-- <div class="line_caption col-lg-4"></div> -->
						</div>
					</div>
				</div>
			</section>

		</div>
	</div>	

	<!-- Services -->

	<div id="services" name="services">
		<div class="container">
			<h2 id="Unikalnost_Media" class="title wow fadeIn">Уникальность</h2>
			<p class="descr wow fadeIn">Помимо Web-Программирования я также увлекаюсь фотографиями. Ещё у моих друзей есть собственная фотостудия!</p>

			<div class="clearfix services-wrap text-center">
				<div id="I_Can_1" class="col-lg-4 services-item commerce">
					<img class="wow fadeIn" src="./img/STYLE.jpg" alt="">
					<h4 class="wow fadeIn">Стиль</h4>
					<p class="descr wow fadeIn">Наши опытные профессионалы подберут вам стиль подходящий для съемки<br /> aenean rhoncus posuere odio in tincidunt.</p>
				</div>

				<div id="I_Can_2" class="col-lg-4 services-item responsive">
					<img class="wow fadeIn" src="./img/PHOTO.jpg" alt="">
					<h4 class="wow fadeIn">Фотогеничность</h4>
					<p class="descr wow fadeIn">Я делаю качественные снимки снимки более 2 лет. Ваши фотки будут, просто, Вах, Уася! :)<br /> aenean rhoncus posuere odio in tincidunt.</p>
				</div>

				<div id="I_Can_3" class="col-lg-4 services-item security">
					<img class="wow fadeIn" src="./img/COSINESS.jpg" alt="">
					<h4 class="wow fadeIn">Уют</h4>
					<p class="descr wow fadeIn">Наша фотостудия станет для вас вторым домом. Весь уют сосредоточен именно здесь<br /> aenean rhoncus posuere odio in tincidunt.</p>
				</div>
			</div>

		</div>
	</div>

	<!-- Contact form -->

	<div id="footer">
		<div class="footer_text">
			<h2 style="opacity: 0;">g</h2>
			<h2 style="opacity: 0;">g</h2>
			<h4 style="opacity: 0;">g</h4>
			<h2 class="title wow fadeIn">Свяжитесь с нами</h2>
		</div>
		<div class="container">
			<div id="submit_form" class="row text-center">

				<div class="col-lg-2"></div>

			<div id="fuild_media" class="input-group col-lg-8 text-center wow fadeIn">

				<div class="col-2"></div>

				<form class="PHP_Form col-8" action="https://anthropical-ages.000webhostapp.com/form-lesson/mail.php" method="post" name="It-Studio">

   					<div class="form-group" style="user-select: none;">
      					<input type="email" class="form-control" name="email" placeholder=" Ваша эл. почта">
      				</div>

   					<div class="form-group" style="user-select: none;">
   						<textarea id="PHP_Text" class="col-12 form-control" type="text" placeholder="Ваше сообщение" name="text" required="required"></textarea>
      				</div>

   					<button type="submit" value="Submit" id="btn_Media" class="PHP_Buttton btn btn-danger col-12"><p id="footer_text_btn" class="mt-2">SUBMIT</p></button>
				
				</form>
				
			</div>

			<div id="adress_Media" class="col-12 text-center wow fadeIn" style="color: white;">
				<p id="adress_Media1">It-Студия Дмитрия Козлова<br>Томск, Россия</p>
				<p id="copyright_Media" id="copyright" class="wow fadeIn"></p>
			</div>
			
			</div>
		</div>
	</div>

	<!-- Jquery library -->
	<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js" integrity="sha512-bLT0Qm9VnAYZDflyKcBaQ2gg0hSYNQrJ8RilYldYQ1FxQYoCLtUjuuRuZo+fjqhx/qtq/1itJ0C2ejDxltZVFg==" crossorigin="anonymous"></script>

	<!-- WOW JS -->
	<script type="text/javascript" src="https://cdn.boomcdn.com/libs/wow-js/1.3.0/wow.js"></script>

	<script type="text/javascript">
		new WOW().init();
	</script>


	<!-- Всё для содержимого страницы -->
	<script type="text/javascript">

		// Плавные переходы по меню к блокам
		$(document).ready(function(){
    		$("#wrapper").on("click","a", function (event) {
        		event.preventDefault();
        		var id  = $(this).attr('href'),
            		top = $(id).offset().top;
        		$('body,html').animate({scrollTop: top}, 1500);
    		});
		});

		// При перезагрузке страницы поднимаем её в самый верх
		$(window).on('beforeunload', function(){
			$(window).scrollTop(0);
		});

		// Делаем блок #home во всю высоту экрана устройства
		$('#home').css({
			"height": window.screen.height
		})
		
		//Указываем текущий год
		document.getElementById('copyright_Media').innerHTML = "©Copyright 2020-" + (new Date()).getFullYear() + ". Private license."

		// // Успешная отправка формы на почту
		// function btn() {
		// 	alert('✔ Ваше сообщение успешно отправлено. Ожидайте нашего ответа на указанную вами почту. Нажмите "OK" для продолжения.');
		// }

		// Плавная прокрутка меню
		$(document).ready(function(){

			// Фикмированная шапка при скролле
			$("#header").removeClass("default");

			$(window).scroll(function(){
				elScroll = $(this).scrollTop();
				if (elScroll == 0 ) {

					$("#navJS a").css({
						"color": "white"
					})

					$("#header").css({
						"backgroundColor": `rgb(254, 254, 254, 0)`,
					})
					$("#header").css({
						"-webkit-box-shadow": `0px 0px 0px 0px rgba(50, 50, 50, 0.87)`,
						"-moz-box-shadow":    `0px 0px 0px 0px rgba(50, 50, 50, 0.87)`,
						"box-shadow":         `0px 0px 0px 0px rgba(50, 50, 50, 0.87)`,
					})	
				}


				if (elScroll > 0 && elScroll < 450 ) {
					$("#header").css(
						{
							"position": "fixed",
							"top": "0",
							"backgroundColor": `rgb(254, 254, 254, ${elScroll/450})`,
							"transition": "background-color 0.1s ease"
						}
					)


					if ( elScroll>290 && elScroll <= 450){
						$('#navJS a').css({
							"color": `rgb(${254 - (elScroll-200)}, ${254 - (elScroll-200)}, ${254 - (elScroll-200)})`
						})
					}

				}
				else if (elScroll >= 450) {
					$("#header").addClass("default").fadeIn('fast');
					$("#header").css(
						{
							"position": "fixed",
							"top": "0",
							"backgroundColor": `white`,
							"transition": "background-color 0.1s ease",
							"-webkit-box-shadow": `0px 3px 8px 0px rgba(50, 50, 50, 0.87)`,
							"-moz-box-shadow":    `0px 3px 8px 0px rgba(50, 50, 50, 0.87)`,
							"box-shadow":         `0px 1px 10px 0px rgba(50, 50, 50, 0.87)`,
						}
					)
					$('#navJS a').css({
						"color": "black"
					})
				};
			});
		});


		


		/* ТЁМНАЯ и СВЕТЛАЯ ТЕМЫ */
		var btn = document.getElementById("theme-button");
		var link = document.getElementById("theme-link");

		let lightTheme = "css/style.css";
		let darkTheme = "css/Dark.css";

		var currTheme = link.getAttribute("href");
		var theme = "";

		//Toggle switch functions
		var togglestate=0;
		document.getElementsByClassName('toggle')[0].onclick = function() {
		this.classList.toggle('on');
		document.getElementsByClassName('theme-button')[0].classList.toggle('on');


			// ТЁМНАЯ ТЕМА
			if (togglestate == 0) {
			    // console.log(togglestate);
			    togglestate = 1;

			    currTheme = darkTheme;
			   	theme = "Dark";
			   	link.setAttribute("href", currTheme);


			    $(document).ready(function(){
			        if ($(window).scrollTop() >= 450) {
			        	$("#header").css({
			                "backgroundColor": `#222222`,
			            });

			            $("#navJS a").css({
			                "color": `white`,
			            });

			        }
			    });


			    // Плавная прокрутка меню ТЁМНАЯ ТЕМА
			    $(document).ready(function(){

			        // Фикмированная шапка при скролле
			        $("#header").removeClass("default");

			        $(window).scroll(function(){
			            elScroll = $(this).scrollTop();

			            if (elScroll > 0 && elScroll < 450 ) {
			                $("#header").css(
			                    {
			                        "backgroundColor": `rgb(34, 34, 34, ${elScroll/450})`,
			                    }
			                )


			                if ( elScroll>290 && elScroll <= 450){
			                    $('#navJS a').css({
			                        "color": `white`
			                    })
			                }

			            }
			                
			            else if (elScroll >= 450) {
			                $("#header").addClass("default").fadeIn('fast');
			                $("#header").css(
			                    {
			                        "backgroundColor": `#222222`,
			                    }
			                )

			                $('#navJS a').css({
			                    "color": "white"
			                })
			            };
			        });
			    });

			}


			// СВЕТЛАЯ ТЕМА
			else if (togglestate == 1) {
			    // console.log(togglestate);
			    togglestate = 0;

			    currTheme = lightTheme;
			   	theme = "Light";
			   	link.setAttribute("href", currTheme);

				$(document).ready(function(){
				    if ($(window).scrollTop() >= 450) {
				    	$("#header").css({
				            "backgroundColor": `white`,
				        });

				        $("#navJS a").css({
				            "color": `black`,
				        });

				    }
				});

				// Плавная прокрутка меню СВЕТЛАЯ ТЕМА
				$(document).ready(function(){

				    // Фикмированная шапка при скролле
				    $("#header").removeClass("default");

				    $(window).scroll(function(){
				        elScroll = $(this).scrollTop();

				        if (elScroll > 0 && elScroll < 450 ) {
				            $("#header").css(
				                {
				                    "backgroundColor": `rgb(254, 254, 254, ${elScroll/450})`,
				                }

				            )


				            if ( elScroll>290 && elScroll <= 450){
				                $('#navJS a').css({
				                    "color": `rgb(${254 - (elScroll-200)}, ${254 - (elScroll-200)}, ${254 - (elScroll-200)})`
				                })
				            }

				        }
				                
				        else if (elScroll >= 450) {
				            $("#header").addClass("default").fadeIn('fast');
				            $("#header").css(
				                {
				                    "backgroundColor": `white`,
				                }
				            )
				            $('#navJS a').css({
				                "color": "black"
				            })
				        };
				    });
				});

			}

			//Save(theme);
		}

	</script>

</body>

</html>
