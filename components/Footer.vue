<template>
  <footer class="footer w-full flex flex-col justify-center items-center">
    <div class="content max-w-6xl w-full">
      <div class="sections">
        <ul class="section">
          <li class="title">Product</li>
          <li class="item">
            <a href="/features" class="link">All Features</a>
          </li>
          <li class="item">
            <a href="/changelog" class="link">Changelog</a>
          </li>
          <li class="item">
            <a href="/testimonials" class="link">Testimonials</a>
          </li>
          <li class="item">
            <a href="/affiliate" class="link">Affiliate Program</a>
          </li>
          <li class="item">
            <a href="/discounts" class="link">Available discounts</a>
          </li>
          <li class="item">
            <a href="/docs-api" class="link">URL scheme API</a>
          </li>
        </ul>
        <ul class="section">
          <li class="title">License</li>
          <li class="item">
            <a href="/pricing" class="link">Pricing</a>
          </li>
          <li class="item">
            <a
              class="link"
              href="https://licenses.cleanshot.com/"
              target="_blank"
              rel="noopener"
              >License Manager</a
            >
          </li>
          <li class="item">
            <a
              class="link"
              href="https://licenses.cleanshot.com/"
              target="_blank"
              rel="noopener"
              >Buy additional seats</a
            >
          </li>
          <li class="item">
            <a href="/eula" class="link">EULA</a>
          </li>
          <li class="item">
            <a
              class="link"
              href="https://licenses.cleanshot.com/download/cleanshotx"
              target="_blank"
              rel="noopener"
              >Download</a
            >
          </li>
        </ul>
        <ul class="section">
          <li class="title">Support</li>
          <li class="item">
            <a class="link" href="mailto:hello@cleanshot.com">Contact us</a>
          </li>
          <li class="item">
            <a href="/faq" class="link">FAQ</a>
          </li>
          <li class="item">
            <a
              class="link"
              href="https://cleanshot-x.s3.eu-central-1.amazonaws.com/Presskit.zip"
              target="_blank"
              rel="noopener"
              >Press kit</a
            >
          </li>
          <li class="item">
            <a
              class="link"
              href="https://status.cleanshot.com"
              target="_blank"
              rel="noopener"
              >Status Page</a
            >
          </li>
          <li class="item">
            <a
              class="link"
              href="https://www.youtube.com/channel/UCm2D6iChCp1bBZQb93np6YA"
              target="_blank"
              rel="noopener"
              >YouTube</a
            >
          </li>
        </ul>
        <ul class="section">
          <li class="title">CleanShot Cloud</li>
          <li class="item">
            <a
              class="link"
              href="https://cleanshot.cloud"
              target="_blank"
              rel="noopener"
              >Log in to Cloud</a
            >
          </li>
          <li class="item">
            <a href="/security" class="link">Security</a>
          </li>
          <li class="item">
            <a href="/cloud/terms" class="link">Terms of Service</a>
          </li>
          <li class="item">
            <a href="/cloud/privacy" class="link">Privacy Policy</a>
          </li>
          <li class="item">
            <a href="/cloud/dpa" class="link">DPA</a>
          </li>
        </ul>
      </div>
      <div class="">
        <div class="copyright">
          © Copyright
          <a class="link" href="https://mtw.team" target="_blank" rel="noopener"
            >MTW</a
          >
        </div>
        <div>
          <a
            class="twitter text-primary text-end"
            href="https://x.com/cleanshot"
            target="_blank"
            rel="noopener"
          >
            Follow us on 𝕏
          </a>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  background: #fafafa;
}
.twitter {
  display: block;
  font-size: 14px;
  font-weight: 700;
  line-height: 1.35;
  margin-top: 16px;
  -webkit-transition: color 0.1s ease;
  transition: color 0.1s ease;
}
.copyright .link {
  font-weight: 700;
  -webkit-transition: color 0.1s ease;
  transition: color 0.1s ease;
}
.info {
  -ms-flex-negative: 0;
  flex-shrink: 0;
  margin-top: 40px;
  text-align: right;
  background: #000;
}
.title {
  color: #000;
  font-size: 16px;
  font-weight: 700;
  line-height: 1.5;
  margin-bottom: 28px;
}
.item > .link {
  color: #333;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  font-size: 14px;
  font-weight: 400;
  line-height: 1.4;
  margin: 16px 0;
  -webkit-transition: color 0.1s ease;
  transition: color 0.1s ease;
}
.content {
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  justify-content: space-between;
  padding: 80px 0px 80px;
}

.sections {
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  -webkit-box-flex: 1;
  -ms-flex-positive: 1;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  flex-grow: 1;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-right: 30px;
  max-width: 750px;
}
.info {
  -ms-flex-negative: 0;
  flex-shrink: 0;
  margin-top: 40px;
  text-align: right;
}

.twitter {
  display: block;
  font-size: 14px;
  font-weight: 700;
  line-height: 1.35;
  margin-top: 16px;
  -webkit-transition: color 0.1s ease;
  transition: color 0.1s ease;
}
.copyright,
.copyright .link {
  color: #000;
  font-size: 16px;
  line-height: 1.5;
}
.copyright {
  font-weight: 400;
}
</style>
