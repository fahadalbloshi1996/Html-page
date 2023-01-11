# Html-page
#i will put code for how to do html file for Animal Trading Cards

<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="styles.css">
	<meta charset="utf-8">
	<title>Animal Trading Cards</title>
</head>
<body>
	<div class="container">
		<!-- your favorite animal's name goes here -->
		<h3 class="text-style-to-title"> Owl</h3>
		<!-- your favorite animal's image goes here -->
		<img class="image-edit" src="owl300200.jpg" alt="Owl">
		<div>
			<!-- your favorite animal's interesting fact goes here -->
          <div class="container-p">
			<p class="style-to-Intro">Most owls share an innate ability to fly almost silently and also more slowly in comparison to other birds of prey</p>
			<ul>
				<!-- your favorite animal's list items go here -->
              <li class="dot-remove"><span class="list-style1">Kingdom:</span> Animalia</li>
              <li class="dot-remove2"><span class="list-style2">Phylum:</span>Chordata </li>
              <li class="dot-remove3"> <span class="list-style3">Class:</span> Aves</li>
              <li class="dot-remove4"> <span class="list-style4">Clade:</span> Telluraves</li>
              <li class="dot-remove5"> <span class="list-style5">Order:
</span>Strigiformes Wagler, 1830</li>
			</ul>
			<!-- your favorite animal's description goes here -->
			<p>Owls are birds from the order Strigiformes, which includes over 200 species of mostly solitary and nocturnal birds of prey typified by an upright stance, a large, broad head, binocular vision, binaural hearing, sharp talons, and feathers adapted for silent flight. Exceptions include the diurnal northern hawk-owl and the gregarious burrowing owl.</p>
		</div>
	</div>
</body>
</html>






-----------------------------------------------------------------------------------------------
#css file

.text-style-to-title{
  font-weight:bold;
  font-size:20pt;
  margin:0.5em;
  padding:0.5em;
  font-family:'albert-sans',           sans-serif}

.image-edit{ 
  width:300px;
  margin:2em;
  pandding:2em;
  display:flex;
  flex-wrap:wrap;
  float:center;
  postion:fixed;
  top:}

.container{
  border-style:solid;
  box-shadow: 8px 10px  lightgray;
  margin: 1em;
  border-width:thin;
  display:flex;
  flex-wrap:wrap;
  font-family:'Finlandica',           sans-serif}

.container-p{
  border:solid;
  border-width:thin;
  margin:1em;
  display:flex;
  flex-wrap:wrap;
  padding:15px}

.style-to-Intro{font-style:italic;}
.dot-remove{list-style-type:none;}
.dot-remove2{list-style-type:none;}
.dot-remove3{list-style-type:none;}
.dot-remove4{list-style-type:none;}
.dot-remove5{list-style-type:none;}
.list-style1{font-weight:bold;}
.list-style2{font-weight:bold;}
.list-style3{font-weight:bold;}
.list-style4{font-weight:bold;}
.list-style5{font-weight:bold;}
