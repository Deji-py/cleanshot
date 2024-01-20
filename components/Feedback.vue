<template>
  <section class="overflow-hidden w-full">
    <div class="col-1224">
      <div class="left">
        <div class="title text-[48px] font-bold">Feedback</div>
        <p class="description">
          Our users love CleanShot. Here's what they are saying.
        </p>
        <div class="rating py-5 flex flex-row justify-start items-center">
          <img src="../static/stars.179e9d97.svg" alt="5 stars" /><span
            class="rating-value font-bold ml-3"
          >
            4.9 </span
          ><span class="rating-info translate-x-2">
            Based on user reviews.</span
          >
        </div>
        <a href="/testimonials" class="action">
          Check out 350+ tweets
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
        <div
          class="arrows mt-20 flex flex-row justify-start items-start gap-10"
        >
          <img
            class="arrow -left"
            src="https://cleanshot.com/_nuxt/20-chevron-left.772b9c09.svg"
            alt="Previous testimonial"
          /><img
            class="arrow -right"
            src="https://cleanshot.com/_nuxt/20-chevron-right.2b95a164.svg"
            alt="Next testimonial"
          />
        </div>
      </div>
      <div
        class="flex-none quotes flex flex-row justify-start items-start gap-5"
      >
        <div class="quote flex-none">
          <a
            class="author-link"
            href="https://twitter.com/JimRaymount"
            target="_blank"
            rel="noopener"
            ><div class="author">
              <picture class="avatar"
                ><source
                  srcset="https://cleanshot.com/_nuxt/jimraymount.9f1bfd53.webp"
                  type="image/webp" />
                <img
                  src="https://cleanshot.com/_nuxt/jimraymount.691b1552.jpg"
                  alt=""
              /></picture>
              <div class="name">
                Jim Raymount,<br /><span class="author-info -twitter"
                  >𝕏 JimRaymount</span
                >
              </div>
            </div></a
          >
          <div class="content">
            I never knew I needed a better screenshot tool, but the annotation
            and workflow improvements mean I find myself oddly enjoying taking
            screenshots.
          </div>
          <div class="tweet-link">
            <a
              class="link"
              href="https://twitter.com/JimRaymount/status/1288487136585547781"
              target="_blank"
              rel="noopener"
              >View on X</a
            >
          </div>
        </div>
        <div class="quote flex-none">
          <a
            class="author-link"
            href="https://twitter.com/mykola_harmash"
            target="_blank"
            rel="noopener"
            ><div class="author">
              <picture class="avatar"
                ><source
                  srcset="
                    data:image/webp;base64,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
                  "
                  type="image/webp" />
                <img
                  src="https://cleanshot.com/_nuxt/mykolaharmash.53715ee6.jpg"
                  alt=""
              /></picture>
              <div class="name">
                Mykola Harmash,<br /><span class="author-info -twitter"
                  >𝕏 mykola_harmash</span
                >
              </div>
            </div></a
          >
          <div class="content">
            CleanShot X is amazing. Such a beautifully crafted mac app, nails so
            many real-life use-cases overlooked by the default screenshot tool.
          </div>
          <div class="tweet-link">
            <a
              class="link"
              href="https://twitter.com/mykola_harmash/status/1314223353960501249"
              target="_blank"
              rel="noopener"
              >View on X</a
            >
          </div>
        </div>
        <div class="quote flex-none">
          <a
            class="author-link"
            href="https://twitter.com/mattrambles"
            target="_blank"
            rel="noopener"
            ><div class="author">
              <picture class="avatar"
                ><source
                  srcset="
                    data:image/webp;base64,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
                  "
                  type="image/webp" />
                <img
                  src="https://cleanshot.com/_nuxt/mattstein.8d32b814.jpg"
                  alt=""
              /></picture>
              <div class="name">
                Matt Stein,<br /><span class="author-info"
                  ><!---->
                  Web designer &amp; developer</span
                >
              </div>
            </div></a
          >
          <div class="content">
            You’ve stylishly and intuitively combined some of the best features
            I’ve seen in different apps and focused them into a fast,
            unobtrusive tool. It’s exactly the kind of utility I would’ve hoped
            for. I love CleanShot and it’s easily one of the most useful apps
            I’ve purchased in a long time.
          </div>
          <!---->
        </div>
        <div class="quote flex-none">
          <a
            class="author-link"
            href="https://twitter.com/petrchutny"
            target="_blank"
            rel="noopener"
            ><div class="author">
              <picture class="avatar"
                ><source
                  srcset="
                    data:image/webp;base64,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
                  "
                  type="image/webp" />
                <img
                  src="data:image/jpeg;base64,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"
                  alt=""
              /></picture>
              <div class="name">
                Petr Chutny,<br /><span class="author-info -twitter"
                  >𝕏 petrchutny</span
                >
              </div>
            </div></a
          >
          <div class="content">
            I'm so happy to have found Cleanshot X. The best designed
            screenshot, annotation, video recording app for Mac. Paid, but
            absolutely worth it. Well done!
          </div>
          <div class="tweet-link">
            <a
              class="link"
              href="https://twitter.com/petrchutny/status/1333681794705731584"
              target="_blank"
              rel="noopener"
              >View on X</a
            >
          </div>
        </div>
        <div class="quote flex-none">
          <a
            class="author-link"
            href="https://twitter.com/jordanborth"
            target="_blank"
            rel="noopener"
            ><div class="author">
              <picture class="avatar"
                ><source
                  srcset="https://cleanshot.com/_nuxt/jordanborth.1c0d4d6f.webp"
                  type="image/webp" />
                <img
                  src="https://cleanshot.com/_nuxt/jordanborth.ea325713.jpg"
                  alt=""
              /></picture>
              <div class="name">
                Jordan Borth,<br /><span class="author-info"
                  ><!---->
                  UI design at Quill</span
                >
              </div>
            </div></a
          >
          <div class="content">
            The option to hide desktop icons and add margins to screenshots is
            super nice. The annotation tools are intuitive and being able to
            drag from the toolbar is super handy. I also love that there are
            tons of customization options!
          </div>
          <!---->
        </div>
        <div class="quote flex-none">
          <a
            class="author-link"
            href="https://twitter.com/LeahLundqvist"
            target="_blank"
            rel="noopener"
            ><div class="author">
              <picture class="avatar"
                ><source
                  srcset="
                    https://cleanshot.com/_nuxt/leahlundqvist.23107014.webp
                  "
                  type="image/webp" />
                <img
                  src="https://cleanshot.com/_nuxt/leahlundqvist.2561b92e.jpg"
                  alt=""
              /></picture>
              <div class="name">
                Leah Lundqvist,<br /><span class="author-info -twitter"
                  >𝕏 LeahLundqvist</span
                >
              </div>
            </div></a
          >
          <div class="content">
            CleanShot is THE BEST! It’s an integral part of my workflow, so
            seamless. I especially love the screencapture and scrolling capture.
            So freaking useful.
          </div>
          <div class="tweet-link">
            <a
              class="link"
              href="https://twitter.com/LeahLundqvist/status/1337728215109013505"
              target="_blank"
              rel="noopener"
              >View on X</a
            >
          </div>
        </div>
        <div class="quote flex-none">
          <a
            class="author-link"
            href="https://twitter.com/shawnroos"
            target="_blank"
            rel="noopener"
            ><div class="author">
              <picture class="avatar"
                ><source
                  srcset="
                    data:image/webp;base64,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
                  "
                  type="image/webp" />
                <img
                  src="https://cleanshot.com/_nuxt/shawnroos.9b6a654b.jpg"
                  alt=""
              /></picture>
              <div class="name">
                Shawn Roos,<br /><span class="author-info"
                  ><!---->
                  Product at Over</span
                >
              </div>
            </div></a
          >
          <div class="content">
            CleanShot is one of those few apps that is so good it becomes
            invisible, an extension of your work. It’s one of the first apps I
            install on any machine and easily one of my most used apps daily.
          </div>
          <!---->
        </div>
        <div class="quote flex-none">
          <a
            class="author-link"
            href="https://twitter.com/chrismessina"
            target="_blank"
            rel="noopener"
            ><div class="author">
              <picture class="avatar"
                ><source
                  srcset="
                    https://cleanshot.com/_nuxt/chrismessina.5991feb8.webp
                  "
                  type="image/webp" />
                <img
                  src="https://cleanshot.com/_nuxt/chrismessina.4e6d6ee4.jpg"
                  alt=""
              /></picture>
              <div class="name">
                Chris Messina,<br /><span class="author-info"
                  ><!---->
                  Hashtag inventor</span
                >
              </div>
            </div></a
          >
          <div class="content">
            CleanShot X has quickly become one of my most used 'invisible' apps
            that just fits into my workflow. Whether I'm pointing out some sweet
            new app feature to a friend, sharing my a screenshot to social
            media, or capturing a GIF to report a bug, I'm using CleanShot in
            each of those cases!
          </div>
          <!---->
        </div>
        <div class="quote flex-none">
          <a
            class="author-link"
            href="https://twitter.com/Jonnotie"
            target="_blank"
            rel="noopener"
            ><div class="author">
              <picture class="avatar"
                ><source
                  srcset="
                    data:image/webp;base64,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
                  "
                  type="image/webp" />
                <img
                  src="https://cleanshot.com/_nuxt/jonnoriekwel.cfdeffef.jpg"
                  alt=""
              /></picture>
              <div class="name">
                Jonno Riekwel,<br /><span class="author-info"
                  ><!---->
                  UI Designer</span
                >
              </div>
            </div></a
          >
          <div class="content">
            This is a great little app that packs a punch. Hiding all the
            desktop icons, and replacing my wallpaper when taking screenshots
            are the killer features for me.
          </div>
          <!---->
        </div>
        <div class="quote flex-none">
          <a
            class="author-link"
            href="https://twitter.com/thorstenball"
            target="_blank"
            rel="noopener"
            ><div class="author">
              <picture class="avatar"
                ><source
                  srcset="
                    data:image/webp;base64,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
                  "
                  type="image/webp" />
                <img
                  src="data:image/jpeg;base64,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"
                  alt=""
              /></picture>
              <div class="name">
                Thorsten Ball,<br /><span class="author-info -twitter"
                  >𝕏 thorstenball</span
                >
              </div>
            </div></a
          >
          <div class="content">
            I bought this ... half a year ago? and it's one of my favorite Mac
            apps of all time. Today I realised that it can not only record
            mouseclicks and keystrokes when recording video/GIF, but also audio
            and 2nd video (webcam!)
          </div>
          <div class="tweet-link">
            <a
              class="link"
              href="https://twitter.com/thorstenball/status/1333113253635952642"
              target="_blank"
              rel="noopener"
              >View on X</a
            >
          </div>
        </div>
        <div class="quote flex-none">
          <a
            class="author-link"
            href="https://twitter.com/mg"
            target="_blank"
            rel="noopener"
            ><div class="author">
              <picture class="avatar"
                ><source
                  srcset="
                    data:image/webp;base64,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
                  "
                  type="image/webp" />
                <img
                  src="https://cleanshot.com/_nuxt/mattgalligan.7ff34b12.jpg"
                  alt=""
              /></picture>
              <div class="name">
                Matt Galligan,<br /><span class="author-info -twitter"
                  >𝕏 mg</span
                >
              </div>
            </div></a
          >
          <div class="content">
            Yesterday I picked up CleanShot X and am already so happy with it.
            Makes screenshots, screen recording, and annotation a breeze. Easily
            a 10x improvement over standard macOS stuff. #notsponsored
          </div>
          <div class="tweet-link">
            <a
              class="link"
              href="https://twitter.com/mg/status/1273246351107788800"
              target="_blank"
              rel="noopener"
              >View on X</a
            >
          </div>
        </div>
        <div class="quote flex-none">
          <a
            class="author-link"
            href="https://twitter.com/TheEricLima"
            target="_blank"
            rel="noopener"
            ><div class="author">
              <picture class="avatar"
                ><source
                  srcset="
                    data:image/webp;base64,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
                  "
                  type="image/webp" />
                <img
                  src="https://cleanshot.com/_nuxt/ericlima.ed0e24a8.jpg"
                  alt=""
              /></picture>
              <div class="name">
                Eric Lima,<br /><span class="author-info"
                  ><!---->
                  Founder of MakerNews</span
                >
              </div>
            </div></a
          >
          <div class="content">
            It's by far the best app I've come across to get those clean
            screenshots and recordings you always see and want. Do yourself and
            your time a favor and get CleanShot.
          </div>
          <!---->
        </div>
        <div class="gradient-cover"></div>
      </div>
      <div class="arrows-mobile lg:hidden">
        <img
          class="arrow -left"
          src="https://cleanshot.com/_nuxt/20-chevron-left.772b9c09.svg"
          alt="Previous testimonial"
        /><img
          class="arrow -right"
          src="https://cleanshot.com/_nuxt/20-chevron-right.2b95a164.svg"
          alt="Next testimonial"
        />
      </div>
    </div>
  </section>
</template>

<style scoped>
.quote:first-of-type {
  z-index: 0;
}
.quote:first-of-type {
  z-index: 0;
}
.quote {
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  background: #f6f6f6;
  border-radius: 20px;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  display: -webkit-inline-box;
  display: -ms-inline-flexbox;
  display: inline-flex;
  -ms-flex-direction: column;
  flex-direction: column;
  height: 430px;
  margin-right: 24px;
  padding: 40px;
  position: relative;
  vertical-align: top;
  width: 390px;
  z-index: 1;
}

.quotes {
  -webkit-box-flex: 0;
  -ms-flex: 0 0 1656px;
  flex: 0 0 1656px;
  height: 430px;
  overflow: hidden;
  position: relative;
}
.quotes {
  -webkit-box-flex: 0;
  -ms-flex: 0 0 1656px;
  flex: 0 0 1656px;
  height: 430px;
  overflow: hidden;
  position: relative;
}

.author {
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}
.tweet-link {
  margin-top: auto;
}

.description {
  color: #333;
  font-size: 20px;
  font-weight: 400;
  line-height: 1.6;
}

.avatar {
  border-radius: 10px;
  height: 64px;
  margin-right: 25px;
  overflow: hidden;
  width: 64px;
}

.name {
  color: #000;
  font-size: 16px;
  font-weight: 700;
  line-height: 1.5;
}

.content {
  color: #000;
  font-size: 18px;
  font-weight: 400;
  line-height: 1.55;
  margin-top: 32px;
}

.tweet-link {
  color: #1da1f2;
  font-size: 14px;
  font-weight: 700;
  line-height: 1.35;
  -webkit-transition: color 0.1s ease;
  transition: color 0.1s ease;
}

.col-1224 {
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  overflow: visible;
}
.col-1224 {
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  overflow: visible;
}
.col-1224 {
  margin: 0 auto;
  max-width: 1224px;
  padding: 0 8%;
}
.col-1224 {
  margin: 0 auto;
  max-width: 1224px;
  padding: 0 8%;
}

.left {
  -ms-flex-negative: 0;
  flex-shrink: 0;
  margin-right: 150px;
  max-width: 300px;
  margin-left: -70px;
}
</style>
