<?php 
$curl = curl_init();
if (isset($_GET["country"])) {
	$country=htmlspecialchars($_GET["country"]);
}
else{
$country="Algeria";
}
curl_setopt_array($curl, array(
	CURLOPT_URL => "https://covid-19-coronavirus-statistics.p.rapidapi.com/v1/stats?country=$country",
	CURLOPT_RETURNTRANSFER => true,
	CURLOPT_FOLLOWLOCATION => true,
	CURLOPT_ENCODING => "",
	CURLOPT_MAXREDIRS => 10,
	CURLOPT_TIMEOUT => 30,
	CURLOPT_HTTP_VERSION => CURL_HTTP_VERSION_1_1,
	CURLOPT_CUSTOMREQUEST => "GET",
	CURLOPT_HTTPHEADER => array(
		"x-rapidapi-host: covid-19-coronavirus-statistics.p.rapidapi.com",
		"x-rapidapi-key: " #rapid-api-key Here
	),
));

$response = curl_exec($curl);
$err = curl_error($curl);


$data_encoded=json_encode($response);
$data_decoded=json_decode($response,true);
#echo $data_decoded;
#var_dump($data_decoded);
$covid19stats=$data_decoded["data"];
$covid19stats=$covid19stats["covid19Stats"];
foreach ($covid19stats as $corona) {
	$d = $corona["deaths"];
	$r = $corona["recovered"];
	$c = $corona["confirmed"];
}
?>
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>COVID19 Statics For Today</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.8.0/css/bulma.min.css">
    <script defer src="https://use.fontawesome.com/releases/v5.3.1/js/all.js"></script>
  </head>
  <body>
  <section class="hero is-fullheight" style="background: linear-gradient(120deg, #ff8800, #ff3300);">
  <!-- Hero head: will stick at the top -->
  <div class="hero-head">
    <header class="navbar">
      <div class="container">
        <div class="navbar-brand">
          <a class="navbar-item">
            <img src="corona.png" alt="Covid States For <?php echo $country;?>">
          </a>
        </div>
      </div>
    </header>
  </div>
  <div class="hero-body">
    <div class="container has-text-centered">
      <h1 class="title">
        <?php echo $country;?>
      </h1>
      <p class="subtitle is-big is-size-15" >
        <span class="tag is-danger"> deaths:<?php echo $d; ?></span>
        <span class="tag is-warning"> confirmed:<?php echo $c; ?></span>
        <span class="tag is-success"> recovred:<?php echo $r; ?></span>
      </p>
      <br>
      <br>
      <br>
      <form method="get" >
        <div align="center">
      <input name="country" class="input is-rounded is-centred has-text-centered" type="text" placeholder="Country">
      </div>
      </form>
    </div>
  </div>
  <div class="hero-foot has-text-centered">
    <p class="subtitle">
      #Stay_At_Home<br>
      <a href="https://maamounbenhafsa.github.io/Me/" class="tag">By Mamoun Benhafsa</a>
      <figure class="image container is-128x128">
        <img src="heart.png" >
      </figure>
    </p>

  </div>
</section>
  </body>
</html>
