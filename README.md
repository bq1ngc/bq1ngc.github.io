<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN">
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>陈宝庆❤翟茹</title>
</head>

<audio id="musicid" autoplay="autoplay" loop="true" >
  <source src="http://home.bqingc.win:8080/audio/可能否.mp3" type="audio/mp3" />
  <embed src="http://home.bqingc.win:8080/audio/可能否.mp3" width="0" height="0" loop="true" />
</audio>


<script>

// 音乐播放
function autoPlayMusic() {
    // 自动播放音乐效果，解决微信自动播放问题
    function musicInWeixinHandler() {
        musicPlay(true);
        document.addEventListener("WeixinJSBridgeReady", function () {
            musicPlay(true);
        }, false);
        document.removeEventListener('DOMContentLoaded', musicInWeixinHandler);
    }
    document.addEventListener('DOMContentLoaded', musicInWeixinHandler);
}
function musicPlay(isPlay) {
    var audio = document.getElementById('musicid');
    if (isPlay && audio.paused) {
        audio.play();
    }
    if (!isPlay && !audio.paused) {
        audio.pause();
    }
}
autoPlayMusic();
</script>



<body>
<div style="text-align: center;">
<img src="/img/byl.jpg" alt="IIS" align="center" /></a>
</div>

<h1 align="center">Welcome To BBQ's Sweet House</h1>
</body>
</html>
