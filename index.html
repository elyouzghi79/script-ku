<?php
include 'src/list.php';
include 'src/souar.php';
if (isset($_GET['q'])) { $q = $_GET['q']; }else{ $q = 1; }
$sh = $shaikh[$q]['href'];
function is_url_exist($url){
    $ch = curl_init($url);
    curl_setopt($ch, CURLOPT_NOBODY, true);
    curl_exec($ch);
    $code = curl_getinfo($ch, CURLINFO_HTTP_CODE);
    if($code == 200){
       $status = true;
    }else{
      $status = false;
    }
    curl_close($ch);
   return $status;
}
?>
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
  <meta name="viewport" content="width=device-width">
  <title>الاستماع للقرآن الكريم </title>
  <link rel="stylesheet" href="css/font-awesome.min.css">
  <link rel="stylesheet" href="theme.css">
</head>
<body>

<div class="wrapp">
<a href="#" class="menu-toggle"><i class="fa fa-bars"></i></a>

<div class="sh-list">
<a href="#" class="menu-toggle"><i class="fa fa-close"></i></a>
<div class="sh-list-wrapp">
	<ul>
<?php
for ($i=1; $i < count($shaikh) ; $i++) {
	if ($q == $i) {
		$current = 'current-player';
	}else {
		$current = '';
	}
	echo "<li class=\"$current\"><a href=\"?q=$i\"><img src=\"thumbs/$i.jpg\" alt=''> <span>" . $shaikh[$i]['name'] . "</span></a></li>";
}
?>
</ul>
</div>
</div>

<div class="player-block">
<div id="j_wrapp" class="jp-jplayer"></div>
<div id="j_player" class="jp-audio" role="application" aria-label="media player">
	<div class="jp-type-playlist">
		<div class="bg clfx">
			<div class="s-info">
				<?php
				echo "<img class=\"sh-avatar\" src=\"thumbs/$q.jpg\" alt=\"\">";
				echo "<h3>". $shaikh[$q]['name'] . "</h3>";
				 ?>
			 </div>
		<div class="playlist-wrapp">
		<div class="jp-playlist">
			<ul>
				<li>&nbsp;</li>
			</ul>
		</div>
		</div>
	</div>
		<div class="jp-gui jp-interface clfx">
			<div class="jp-progress">
				<div class="jp-seek-bar">
					<div class="jp-play-bar"></div>
				</div>
			</div>
			<div class="jp-time-holder clfx">
				<div class="jp-current-time" role="timer" aria-label="time">&nbsp;</div>
				<div class="sepr"> / </div>
				<div class="jp-duration" role="timer" aria-label="duration">&nbsp;</div>
			</div>
			<div class="jp-volume-controls">
				<button class="toggle-left"><i class="fa fa-bars"></i></button>
				<button class="jp-volume-max" role="button" tabindex="0"><i class="fa fa-volume-up"></i></button>
				<div class="jp-volume-bar">
					<div class="jp-volume-bar-value"></div>
				</div>
				<button class="jp-mute" role="button" tabindex="0"><i class="fa fa-volume-off"></i></button>
				<div class="jp-toggles">
					<button class="jp-repeat" role="button" tabindex="0"><i class="fa fa-repeat"></i></button>
					<button class="jp-shuffle" role="button" tabindex="0"><i class="fa fa-random"></i></button>
				</div>
			</div>
			<div class="jp-controls">
				<button class="jp-previous" role="button" tabindex="0"><i class="fa fa-fast-backward"></i></button>
				<button class="jp-next" role="button" tabindex="0"><i class="fa fa-fast-forward"></i></button>
				<button class="jp-play" role="button" tabindex="0"><i class="fa fa-play"></i></button>
			</div>
    <div class="f"></div>
		</div>
		<div class="jp-no-solution">
			<span>Update Required</span>
			To play the media you will need to either update your browser to a recent version or update your <a href="http://get.adobe.com/flashplayer/" target="_blank">Flash plugin</a>.
		</div>
	</div>
</div>
</div>
</div>

<script type="text/javascript" src="js/jquery.min.js"></script>
<script type="text/javascript" src="js/jquery.jplayer.min.js"></script>
<script type="text/javascript" src="js/jplayer.playlist.min.js"></script>
<script type="text/javascript">
//<![CDATA[
$(document).ready(function(){
		new jPlayerPlaylist({
			jPlayer: "#j_wrapp",
			cssSelectorAncestor: "#j_player"
		}, [
			<?php
			foreach ($soura as $name => $num) {
				//if (is_url_exist("$sh$num") == 1) {
					echo "{ title: \"$name\" , mp3:\" $sh$num.mp3\" },";
				//}
			}
			 ?>
		],
		 {
			 playlistOptions: {
    //autoPlay: true,
    enableRemoveControls: true
  },
			supplied: "oga, mp3",
			wmode: "window",
			useStateClassSkin: true,
			autoBlur: false,
			smoothPlayBar: true,
			keyEnabled: true
		});
});
//]]>
</script>
<script type="text/javascript" src="js/site.js"></script>
<script type="text/javascript" src="js/js.js"></script>
</body>

</html>
