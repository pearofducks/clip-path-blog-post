<template>
  <div class="blobbed">
    <img class="blobbed-pug" src="./charles-550068-unsplash-squared.jpg" alt="a pug in a jean-jacket" />

    <svg width="0" height="0">
      <defs>
        <clipPath id="svg-blob" clipPathUnits="objectBoundingBox">
          <path d="M0.863,0.173c0.093,0.089 0.151,0.19 0.134,0.277c-0.017,0.087 -0.109,0.16 -0.161,0.266c-0.053,0.107 -0.067,0.246 -0.137,0.277c-0.069,0.031 -0.195,-0.047 -0.346,-0.085c-0.151,-0.038 -0.327,-0.037 -0.35,-0.097c-0.023,-0.061 0.107,-0.183 0.149,-0.308c0.042,-0.124 -0.005,-0.251 0.041,-0.347c0.046,-0.096 0.185,-0.162 0.318,-0.156c0.133,0.006 0.26,0.084 0.352,0.173Z"/>
        </clipPath>
      </defs>
    </svg>
  </div>
</template>

<style>
html, body {
  height: 100%;
}
body {
  display: flex;
  align-items: center;
  justify-content: center;
  background: #aaa;
}
.blobbed {
  height: 50vw;
  width: 50vw;
  -webkit-clip-path: url(#svg-blob);
  clip-path: url(#svg-blob);
}
.blobbed-pug {
  width: 100%;
  height: auto;
}
</style>


// have blob - notice the viewbox is 0 0 600 600!
// squared up the picture
