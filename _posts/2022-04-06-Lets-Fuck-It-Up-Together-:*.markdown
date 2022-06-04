---
layout: post
title:  "Lets Fuck it Up Together :*"
date:  2022-06-04 20:35:29 +0300
---

<iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/0jNi9HTJBga3Nn5gEyw9I9?utm_source=generator" width="100%" height="380" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"></iframe>

<br><br>

That's not really a post. Lets just listen to some electronics together :)

<div class="centered-box">
  <span class="heart animate-beat">🎧</span>
</div>

<style>

$big-fallback: 50px;
$big-size: 25vh;
$small-fallback: 40px;
$small-size: 20vh;


@mixin big-beat() {
  font-size: $big-fallback; /* fallback */
  font-size: $big-size;
}

@mixin small-beat() {
  font-size: $small-fallback; /* fallback */
  font-size: $small-size;
}

.centered-box {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

.heart {
  @include big-beat();
}

.animate-beat {
    animation: beat 1s infinite;
}

@keyframes beat {
  0% {
    @include small-beat();
  }
  40% {
    @include big-beat();
  }
  60% {
    @include small-beat();
  }
  80% {
    @include big-beat();
  }
  100% {
    @include small-beat();
  }
}

</style>
