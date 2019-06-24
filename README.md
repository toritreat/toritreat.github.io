<!DOCTYPE html>
<html lang="ja">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<link rel="stylesheet" href="./toritreat.css">
	<link rel="stylesheet" href="./script.js">
	<title>ToriTreat</title>
</head>
<body>

	<header>
			<div class="header-logo-menu">
					<div id="nav-drawer">
							<input id="nav-input" type="checkbox" class="nav-unshown">
							<label id="nav-open" for="nav-input"><span></span></label>
							<label class="nav-unshown" id="nav-close" for="nav-input"></label>
							<div id="nav-content">
								<li><a href="#concept">理念</a></li><br>
								<li><a href="#service">サービス</a></li><br>
								<li><a href="#message">挨拶</a></li><br>
								<li><a href="#contact">お問い合わせ</a></li><br>
							</div>
					</div>
			</div>
		<!--logo画像-->
		<h1 class="logo">
				<img src="./img/logo.png">
		</h1>    
		<!--メニュー-->
		<div class="headiv">        
				<ul>
						<li><a href="#concept">理念</a></li>
						<li><a href="#service">サービス</a></li>
						<li><a href="#message">挨拶</a></li>
						<li><a href="#contact">お問い合わせ</a></li>
				</ul>
		</div>              
</header>

<main>
<!-- concept -->	
	<div id="concept">
	<svg version="1.1" xmlns="http://www.w3.org/2000/svg"><path id="wave" d=""/></svg>
	
	 <div class="content concept1">
       <h2>Innovate Chicken Business</h2>
			 <p class="sub_concept">テクノロジーで養鶏業を変える</p>
			 <p class="text">全産業がデジタル革命によりビジネスモデルの変革を求められています。今がちょうど養鶏業界における時代の変わり目です。私たちはテクノロジーを用いて、養鶏家の皆様と購入者の皆様と共に養鶏業界に新たな風を吹かせます。</p>
	</div>

	 <div class="content concept2">
		<h2>Make Chickens Happy</h2>
		<p class="sub_concept">鶏のためにより良い環境を作り出す</p>
		<p class="text">現在世界中で動物福祉への関心が高まっています。日本でもこの考えに共鳴する人々が増えています。次世代の養鶏業を作る我々は鶏も人々も共に幸せになれる社会づくりに貢献します。</p>
   </div>
   </div>

<!-- service -->	 
	 <div id="service">
		 <h2>SERVICE</h2>

		 <div class="service_img">
		 <img class="img" src="./img/service.jpg" alt="">
		</div>

		 <p class="text">ToriTreat</p>
		 <p class="text2">「あなただけの鶏で、あなただけの卵を。」</p>
		 <p class="text3">
			ToriTreatはオンライン上で鶏を契約し、その鶏の餌を皆さまがカスタマイズすることで<span>オリジナルの卵</span>を作っていただけるサービスです。また、契約された鶏はケージの外で飼われるため<span>動物福祉に貢献</span>できます。リアルタイムでの観察も可能で<span>安心</span>です。愛を持ってあなただけの鶏を私たちと共に育て上げましょう。
			</p>
	 </div>

<!-- message -->	 
	 <div id="message">
		 <h2>MESSAGE</h2>
		 <div class="tori">
			 <img src="./img/tori2.png" alt="">
		 </div>
		 <div>
			<li>皆さま初めまして。代表の宮崎と申します。<br>
			私は日本の養鶏の在り方に以前から疑問を抱いていました。<br>
			<br>
			「鶏により良い環境を与えたい」「養鶏家がもっと稼げるようなビジネスに変えたい」<br>
			<br>
			私たちはこれらを成し遂げるためにテクノロジーで次世代の養鶏を創出します。<br>
			また将来、この志のために物流事業への積極的な投資もお約束します。<br>
			<br>
			皆さま一人一人に愛らしい鶏がいる。<br>
			その彼女たちがケージに取り囲まれることなく自由に動き回れる。<br>
			そして彼女たちの卵が新鮮なうちにあなたの元に届けられる。<br>
			<br>
		  そのような将来を想像してみるとワクワクしませんか？<br>
			明るい未来を創るために今後ともご支援賜りますようお願い申し上げます。<br>
			また、私たちと共に未来を創る仲間を募集しています。<br></li>
	 </div>


	<!-- CONTACT -->
<div id="contact"> 
		<h2>CONTACT</h2>
	 <form action="confirmation.php" method="post">
		名前：<br/>
		<input type="text" name="name" value="" /><br />

		メールアドレス：<br />
		<input type="text" name="mail"  value="" /><br />

		お問合せ内容：<br />
		<textarea name="inquiry"  rows="5"></textarea><br />
		<br />

    <input class="submit" type="submit" value="送信する" />
   </form>
</div>
	
</main>

<footer class="footer">
	   <div> 
		<nav>
				<li><a href="#concept">理念</a></li>
				<li><a href="#service">サービス</a></li>
				<li><a href="#message">挨拶</a></li>
				<li><a href="#contact">お問い合わせ</a></li>
		</nav>
	</div>
	
  <div class="copyright">
		Copyright © 2019 ToriTreat Co., Ltd. 
	</div>
</footer>


<script src="https://unpkg.com/scrollreveal/dist/scrollreveal.min.js"></script>
	<script>
	window.sr = ScrollReveal({ reset: true ,mobile: true});
  sr.reveal('.img', { 
		origin: 'left', easing: 'ease', duration: 2000, distance: '400px', opacity: 1,
		rotate: {x:180, y:0, z:0}, scale: 1 });
	sr.reveal('#service .text',{scale:2,});
	sr.reveal('#service .text2',{scale:2,});
	sr.reveal('#service .text3',{scale:2,});
</script>


</body>
</html>

