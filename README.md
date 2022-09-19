# ACS-Video-Player
Used to develop video player template for your video gallery website  on the fly
### In order to Create a Video Player you need Deploy your custom HTML which should look like this
```
  <div class="video-container">
      <div class="media">
        <video
          src="https://cdn.sharechat.com/cv-2d4dd1e_1609143171216_sc_watermarked_1.mp4"
          class="src-video"
        ></video>
        <div class="loader-animation"></div>
      </div>
      <div class="controls">
        <div class="seek-container">
          <span class="currentDuration">00:00:00 </span>
          <input
            type="range"
            name=""
            max="100"
            min="0"
            value="0"
            class="seek-slider"
          />
          <span class="totalDuration">00:00:00</span>
        </div>
        <div class="forward">&#8635;</div>
        <div class="play">&#9654;</div>
        <div class="pause">&#9612;&#9612;</div>
        <div class="forward backward">&#8635;</div>
        <div class="mute">🔈</div>
        <div class="rotate">🗘</div>
      </div>
      <div class="controls mobile-controls">
        <div class="seek-container">
          <span class="currentDuration">00:00:00 </span>
          <input
            type="range"
            name=""
            max="100"
            min="0"
            value="0"
            class="seek-slider"
          />
          <span class="totalDuration">00:00:00</span>
        </div>
        <div class="nested-controls">
          <div class="forward">&#8635;</div>
          <div class="play">&#9654;</div>
          <div class="pause">&#9612;&#9612;</div>
          <div class="forward backward">&#8635;</div>
          <div class="mute">🔈</div>
          <div class="rotate">🗘</div>
        </div>
      </div>
    </div>
```
