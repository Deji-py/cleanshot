<template>
  <section
    class="flex flex-col py-40 justify-center items-center py-24 w-full max-w-6xl"
  >
    <div class="grid gap-10 grid-cols-3">
      <div class="grid-item">
        <div class="icon">
          <img src="../static/24-timer.e5d9ea1f.svg" alt="" />
        </div>
        <h3 class="name">Self-timer</h3>
        <p class="description">
          Take a screenshot after a specified delay to capture the perfect
          moment.
        </p>
      </div>
      <div class="grid-item">
        <div class="icon">
          <img src="../static/24-retina.863f3d89.svg" alt="" />
        </div>
        <h3 class="name">Scale down Retina</h3>
        <p class="description">
          You can automatically scale down Retina screenshots to standard
          resolution.
        </p>
      </div>
      <div class="grid-item">
        <div class="icon">
          <img src="../static/24-crosshair.8ce0905e.svg" alt="" />
        </div>
        <h3 class="name">Crosshair mode</h3>
        <p class="description">
          Never waste time on trying to perfectly align your screenshots again.
        </p>
      </div>
      <div class="grid-item">
        <div class="icon">
          <img src="../static/24-wallpaper.91894f18.svg" alt="" />
        </div>
        <h3 class="name">Custom wallpaper</h3>
        <p class="description">
          Set a specific photo or a plain color as a wallpaper for screenshots
          and screen recordings.
        </p>
      </div>
      <div class="grid-item">
        <div class="icon">
          <img src="../static/24-user.30ea5c9c.svg" alt="" />
        </div>
        <h3 class="name">Tweak your workflow</h3>
        <p class="description">
          You can adjust lots of settings and tailor CleanShot exactly to your
          needs.
        </p>
      </div>
      <div class="grid-item">
        <div class="icon">
          <img src="../static/24-apple.9d6a10e1.svg" alt="" />
        </div>
        <h3 class="name">Made for Mac</h3>
        <p class="description">
          A completely native app gives you the performance you expect.
        </p>
      </div>
    </div>
    <div class="mt-20 actions">
      <a href="/features" class="action">
        Check all 50+ features
        <svg
          width="20"
          height="20"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          class="arrow"
          alt=""
        >
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M7.3 4.3a1 1 0 011.4 0l5 5c.4.4.4 1 0 1.4l-5 5a1 1 0 01-1.4-1.4l4.3-4.3-4.3-4.3a1 1 0 010-1.4z"
          ></path></svg
      ></a>
    </div>
  </section>
</template>

<style>
.grid-item {
  text-align: center;
}
.grid-item {
  text-align: center;
}

.action {
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  color: #0669ff;
  cursor: pointer;
  display: -webkit-inline-box;
  display: -ms-inline-flexbox;
  display: inline-flex;
  font-size: 20px;
  font-weight: 700;
  line-height: 1.6;
  -webkit-transition: color 0.1s ease;
  transition: color 0.1s ease;
}

.description {
  color: #333;
  font-size: 16px;
  font-weight: 400;
  line-height: 1.5;
  margin-bottom: 0;
  margin-top: 10px;
}

.name {
  color: #000;
  font-size: 20px;
  font-weight: 700;
  line-height: 1.6;
  margin-top: 10px;
}

.icon {
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  background: #f6f6f6;
  border-radius: 16px;
  display: -webkit-inline-box;
  display: -ms-inline-flexbox;
  display: inline-flex;
  height: 64px;
  justify-content: center;
  width: 64px;
}
</style>
