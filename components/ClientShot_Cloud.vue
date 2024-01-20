<template>
  <section
    class="w-full flex gap-20 flex-row justify-center items-center max-w-6xl"
  >
    <div class="left flex-1 flex flex-col gap-5 justify-start items-start">
      <div class="info">
        <img class="check" src="../static/24-check.86c8c111.svg" alt="" />
        Cloud account is not required to use the app
      </div>
      <h1 class="text-[48px] font-bold">CleanShot Cloud</h1>
      <p class="text-xl font-[400]">
        Upload your captures to our blazing-fast Cloud and instantly get a
        shareable link.
      </p>
      <div class="highlights flex flex-col justify-start items-start">
        <div class="highlight">
          <div class="highlight-icon">
            <img src="../static/20-link.2665e57e.svg" alt="" />
          </div>
          <div class="highlight-name">
            Upload &amp; get a link in a single click
          </div>
        </div>
        <div class="highlight">
          <div class="highlight-icon">
            <img src="../static/20-tags.8259867b.svg" alt="" />
          </div>
          <div class="highlight-name">
            Tag screenshots for better organization&nbsp;
          </div>
        </div>
        <div class="highlight">
          <div class="highlight-icon">
            <img src="../static/20-destruct.7bc688c7.svg" alt="" />
          </div>
          <div class="highlight-name">
            Self destruct control&nbsp;<a href="/pricing" class=""
              ><span class="badge">Pro</span></a
            >
          </div>
        </div>
        <div class="highlight">
          <div class="highlight-icon">
            <img src="../static/20-domains.0f3b91b2.svg" alt="" />
          </div>
          <div class="highlight-name">
            Custom domain &amp; branding&nbsp;<a href="/pricing" class=""
              ><span class="badge">Pro</span></a
            >
          </div>
        </div>
        <div class="highlight">
          <div class="highlight-icon">
            <img src="../static/20-team.9c66b912.svg" alt="" />
          </div>
          <div class="highlight-name">
            Team management&nbsp;<a href="/pricing" class=""
              ><span class="badge">Pro</span></a
            >
          </div>
        </div>
      </div>
    </div>
    <div class="w-[55%]">
      <img src="../static/cloud_2x.8cb9df44.webp" alt="cloud" />
    </div>
  </section>
</template>

<style>
.highlight {
  display: flex;
  justify-content: start;
  align-items: center;
  margin: 5px 0px;
}

.highlight-icon {
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  background: #f6f6f6;
  margin-right: 15px;
  border-radius: 8px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  height: 40px;
  justify-content: center;
  width: 40px;
}

.info {
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  color: #2ccb89;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  font-size: 14px;
  font-weight: 700;
  line-height: 1.35;
  margin-bottom: 24px;
  gap: 10px;
}

.highlight-name .badge {
  background: #e2eeff;
  border-radius: 20px;
  color: #0669ff;
  font-size: 14px;
  font-size: 12px;
  font-weight: 700;
  line-height: 1.35;
  margin-left: 10px;
  padding: 4px 7px 5px;
}

.highlight-name .badge {
  background: #e2eeff;
  border-radius: 20px;
  color: #0669ff;
  font-size: 14px;
  font-size: 12px;
  font-weight: 700;
  line-height: 1.35;
  margin-left: 10px;
  padding: 4px 7px 5px;
}
</style>
