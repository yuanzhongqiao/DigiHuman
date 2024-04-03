<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数字人类</font></font></h1><a id="user-content-digihuman" class="anchor" aria-label="永久链接：DigiHuman" href="#digihuman"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DigiHuman 是一个旨在</font><font style="vertical-align: inherit;">根据相机输入在 3D 角色模型上
自动生成</font></font><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全身姿势动画 + 面部动画的</font></font></b><font style="vertical-align: inherit;"></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目。
这个项目是我在阿米尔卡比尔理工大学（AUT）计算机工程的学士学位论文。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关于数码人</font></font></h2><a id="user-content-about-digihuman" class="anchor" aria-label="永久链接：关于 D&ZeroWidthSpace;&ZeroWidthSpace;igiHuman" href="#about-digihuman"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DigiHuman 是一个用于在 3D 虚拟角色上实现动画生成自动化的系统。它使用姿势估计和面部标志生成器模型在 3D 虚拟角色上创建整个身体和面部动画。
 </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
DigiHuman 是使用</font></font><a href="https://github.com/google/mediapipe"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MediaPipe</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Unity3D</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发的。 MediaPipe 生成人体全身和面部的 3D 地标，Unity3D 在处理 MediaPipe 生成的地标后用于渲染最终动画。下图显示了应用程序的整体架构。</font></font></p>
<div align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/dataFlow.png?raw=true"><img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/dataFlow.png?raw=true" alt="标识" style="max-width: 100%;"></a>
</div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目的示例输出</font></font></h2><a id="user-content-sample-outputs-of-the-project" class="anchor" aria-label="永久链接：项目的示例输出" href="#sample-outputs-of-the-project"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div align="center" dir="auto">
<a href="https://youtu.be/maUUXfe_EcU" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目演示</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="https://youtu.be/L62w5AMaFOk" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">教程</font></font></a>
</div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手动画</font></font></h3><a id="user-content-hands-animations" class="anchor" aria-label="永久链接：手动画" href="#hands-animations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div align="center" dir="auto">
  <animated-image data-catalyst=""><a href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/2828_ok.gif" data-target="animated-image.originalLink">
    <img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/2828_ok.gif?raw=true" alt="标识" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage">
  </a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/2828_ok.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="Logo" class="AnimatedImagePlayer-animatedImage" src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/2828_ok.gif?raw=true" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="690" height="388"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play Logo" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play Logo">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open Logo in new window" class="AnimatedImagePlayer-button" href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/2828_ok.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image>
  <animated-image data-catalyst=""><a href="https://thumbs.gfycat.com/VibrantDearestKomododragon-size_restricted.gif" rel="nofollow" data-target="animated-image.originalLink">
    <img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/2828_1t05.gif?raw=true" alt="标识" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage">
  </a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://thumbs.gfycat.com/VibrantDearestKomododragon-size_restricted.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="Logo" class="AnimatedImagePlayer-animatedImage" src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/2828_1t05.gif?raw=true" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="690" height="388"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play Logo" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play Logo">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open Logo in new window" class="AnimatedImagePlayer-button" href="https://thumbs.gfycat.com/VibrantDearestKomododragon-size_restricted.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image>
</div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全身动画</font></font></h3><a id="user-content-full-body-animation" class="anchor" aria-label="永久链接：全身动画" href="#full-body-animation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div align="center" dir="auto">
  <animated-image data-catalyst=""><a href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/figure_headphone.gif" data-target="animated-image.originalLink">
    <img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/figure_headphone.gif" alt="标识" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage">
  </a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/figure_headphone.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="Logo" class="AnimatedImagePlayer-animatedImage" src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/figure_headphone.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="692" height="388"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play Logo" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play Logo">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open Logo in new window" class="AnimatedImagePlayer-button" href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/figure_headphone.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image>
    <animated-image data-catalyst=""><a href="https://gfycat.com/braveglumguanaco" rel="nofollow" data-target="animated-image.originalLink">
    <img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/hands_greek.gif" alt="标识" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage">
  </a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://gfycat.com/braveglumguanaco" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="Logo" class="AnimatedImagePlayer-animatedImage" src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/hands_greek.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="692" height="388"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play Logo" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play Logo">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open Logo in new window" class="AnimatedImagePlayer-button" href="https://gfycat.com/braveglumguanaco" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image>
</div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人脸动画</font></font></h3><a id="user-content-face-animation" class="anchor" aria-label="永久链接：脸部动画" href="#face-animation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div align="center" dir="auto">
  <animated-image data-catalyst=""><a href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/mouth_deform_1_japan.gif" data-target="animated-image.originalLink">
    <img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/mouth_deform_1_japan.gif?raw=true" alt="标识" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage">
  </a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/mouth_deform_1_japan.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="Logo" class="AnimatedImagePlayer-animatedImage" src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/mouth_deform_1_japan.gif?raw=true" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="690" height="388"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play Logo" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play Logo">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open Logo in new window" class="AnimatedImagePlayer-button" href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/mouth_deform_1_japan.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image>
  <animated-image data-catalyst=""><a href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/blinks_1_japan.gif" data-target="animated-image.originalLink">
    <img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/blinks_1_japan.gif?raw=true" alt="标识" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage">
  </a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/blinks_1_japan.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="Logo" class="AnimatedImagePlayer-animatedImage" src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/blinks_1_japan.gif?raw=true" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="690" height="388"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play Logo" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play Logo">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open Logo in new window" class="AnimatedImagePlayer-button" href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/blinks_1_japan.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image>
  <animated-image data-catalyst=""><a href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/mouth_1_japan.gif" data-target="animated-image.originalLink">
    <img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/mouth_1_japan.gif?raw=true" alt="标识" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage">
  </a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/mouth_1_japan.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="Logo" class="AnimatedImagePlayer-animatedImage" src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/mouth_1_japan.gif?raw=true" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="690" height="388"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play Logo" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play Logo">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open Logo in new window" class="AnimatedImagePlayer-button" href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/mouth_1_japan.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image>
   <animated-image data-catalyst=""><a href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/mouth_dir_1_japan.gif" data-target="animated-image.originalLink">
    <img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/mouth_dir_1_japan.gif?raw=true" alt="标识" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage">
  </a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/mouth_dir_1_japan.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="Logo" class="AnimatedImagePlayer-animatedImage" src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/mouth_dir_1_japan.gif?raw=true" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="690" height="388"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play Logo" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play Logo">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open Logo in new window" class="AnimatedImagePlayer-button" href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/mouth_dir_1_japan.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image>
</div>


<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2><a id="user-content-installation" class="anchor" aria-label="永久链接：安装" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按照说明运行程序！</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">后端服务器安装</font></font></h3><a id="user-content-backend-server-installtion" class="anchor" aria-label="永久链接：后端服务器安装" href="#backend-server-installtion"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 MediaPipe python。</font></font></li>
</ol>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre> <span class="pl-s1">pip</span> <span class="pl-s1">install</span> <span class="pl-s1">mediapipe</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value=" pip install mediapipe" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ol start="3" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 OpenCV python。</font></font></li>
</ol>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre> <span class="pl-s1">pip</span> <span class="pl-s1">install</span> <span class="pl-s1">opencv</span><span class="pl-c1">-</span><span class="pl-s1">python</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value=" pip install opencv-python" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ol start="5" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">转到</font></font><code>backend</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录并安装其他要求：</font></font></li>
</ol>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre> <span class="pl-s1">pip</span> <span class="pl-s1">install</span> <span class="pl-c1">-</span><span class="pl-s1">r</span> <span class="pl-s1">requirements</span>.<span class="pl-s1">txt</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value=" pip install -r requirements.txt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ol start="6" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您需要</font></font><a href="https://drive.google.com/file/d/15VSa2m2F6Ch0NpewDR7mkKAcXlMgDi5F/view?usp=sharing" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">COCO 数据集的预训练生成器模型并将其放入</font></font><code>backend/checkpoints/coco_pretrained/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></li>
</ol>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Unity3D安装</font></font></h3><a id="user-content-unity3d-installation" class="anchor" aria-label="永久链接：Unity3D 安装" href="#unity3d-installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按照以下指南安装 Unity3D 及其要求（如果已安装 Unity3D，请跳过 1-3）。</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载并安装  </font></font><a href="https://unity.com/download" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">UnityHub</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在UnityHub中添加新许可证并注册</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在UnityHub内安装Unity编辑器（</font><font style="vertical-align: inherit;">推荐</font></font><code>LTS</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版本和更高版本）。</font></font><code>2020.3.25f1</code><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Unity 项目设置中，在播放器设置中允许 HTTP 连接。</font></font></li>
</ol>
 <div align="center" dir="auto">
  <a href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/http.png">
    <img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/http.png?raw=true" alt="标识" style="max-width: 100%;">
  </a>
</div>
<ol start="5" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载以下包并将其导入到您的项目中，以启用 FFmpeg 提供的录制选项（下载</font></font><code>.unitypackage</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件并将其拖到您的项目中）。</font></font></li>
</ol>
<ul dir="auto">
<li><a href="https://github.com/keijiro/FFmpegOut/releases"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FFmpegOut 包</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（MIT 许可证）</font></font></li>
<li><a href="https://github.com/keijiro/FFmpegOutBinaries/releases"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FFmpegOutBinaries 包</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(GPL)</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法</font></font></h1><a id="user-content-usage" class="anchor" aria-label="永久链接：用法" href="#usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"></font><code>backend</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用以下命令
</font><font style="vertical-align: inherit;">在目录中运行后端服务器：</font></font><div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code> python server.py
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value=" python server.py" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行 Unity 项目并打开主场景</font></font><code>Assets\Scenes\MainScene.unity</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过从 Unity 项目上传视频到后端来测试程序（您可以通过从右侧菜单中选择提供的动画来测试应用程序！）。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">添加新的 3D 角色</font></font></h2><a id="user-content-adding-new-3d-characters" class="anchor" aria-label="永久链接：添加新的 3D 角色" href="#adding-new-3d-characters"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以将您的角色添加到项目中！角色应该有一个标准的人形装备来显示运动动画。为了渲染面部动画，角色应该有面部装备（Blendmesh）。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
请按照以下步骤添加您的角色：</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"></font><a href="http://assetstore.unity.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从Unity 资产商店</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查找 3D 角色模型</font><font style="vertical-align: inherit;">或下载免费模型（您可以从</font></font><a href="http://mixamo.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mixamo</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等网站下载）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开角色设置并将装备设置为人形</font></font></li>
</ol>
<div align="left" dir="auto">
  <a href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/3.png">
    <img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/3.png?raw=true" alt="标识" width="300" height="150" style="max-width: 100%;">
  </a>
</div>
<ol start="3" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 3D 角色模型拖放到</font></font><code>CharacterChooser/CharacterSlideshow/Parent</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Unity 主场景中的对象，如下图所示</font></font></li>
</ol>
<div align="left" dir="auto">
  <a href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/1.png">
    <img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/1.png?raw=true" alt="标识" width="300" height="400" style="max-width: 100%;">
  </a>
</div>
<ol start="4" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将</font></font><code>BlendShapeController</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>QualityData</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组件添加到场景中的角色对象（在最后一步中拖动到父对象内）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设定</font></font><code>BlendShapeController</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">值</font></font></li>
</ol>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将角色</font></font><code>SkinnedMeshRenderer</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组件添加到</font></font><code>BlendShapeController</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组件中。</font></font></li>
</ul>
<div align="left" dir="auto">
  <a href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/5.png">
    <img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/5.png?raw=true" alt="标识" style="max-width: 100%;">
  </a>
</div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到下面的每个 blnedShape 权重数字</font></font><code>SkinnedMeshRenderer</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并在</font></font><code>BlendShapes</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内部字段中设置这些数字</font></font><code>BlendShapeController</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（用于为</font></font><code>BlendShapeController</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组件指定每个 BlendShape 值，以便通过修改这些 blnedShape 值将动画显示在角色脸上）</font></font></li>
</ul>
<div align="left" dir="auto">
  <a href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/6.png">
    <img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/6.png?raw=true" alt="标识" width="300" height="400" style="max-width: 100%;">
  </a>
</div>
<ol start="6" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在场景层次结构内的路径上</font><font style="vertical-align: inherit;">打开</font></font><code>CharacterSlideshow</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对象，然后将新的拖动角色添加到</font><font style="vertical-align: inherit;">属性中（所有角色都应在内部引用</font><font style="vertical-align: inherit;">）。</font></font><code>CharacterChooser/CharacterSlideshow</code><font style="vertical-align: inherit;"></font><code>nodes</code><font style="vertical-align: inherit;"></font><code>nodes</code><font style="vertical-align: inherit;"></font></li>
</ol>
<div align="left" dir="auto">
  <a href="https://github.com/Danial-Kord/DigiHuman/blob/images/images/8.jpg">
    <img src="https://github.com/Danial-Kord/DigiHuman/raw/images/images/8.jpg?raw=true" alt="标识" width="500" height="300" style="max-width: 100%;">
  </a>
</div>
<ol start="7" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行应用程序，您现在可以选择要渲染动画的角色！</font></font></li>
</ol>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特征</font></font></h1><a id="user-content-features" class="anchor" aria-label="永久链接：特点" href="#features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>


<ul class="contains-task-list">
<li class="task-list-item"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox" checked=""><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">制作全身动画</font></font></li>
<li class="task-list-item"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox" checked=""><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对 3D 角色进行多个混合形状动画（当前最多支持 40 个混合形状动画）</font></font></li>
<li class="task-list-item"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox" checked=""><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Humanoid T-Pose 装备支持任何 3D 模型</font></font></li>
<li class="task-list-item"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox" checked=""><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">导出视频文件中的动画</font></font></li>
<li class="task-list-item"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox" checked=""><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">保存动画数据并重新渲染以供将来使用</font></font></li>
<li class="task-list-item"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox" checked=""><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">过滤 mediaPipe 输出以检测和消除噪音并获得更好的平滑度（当前使用低通滤波）</font></font></li>
</ul>

<ul class="contains-task-list">
<li class="task-list-item"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对角色脸部进行细致的动画处理
</font></font><ul class="contains-task-list">
<li class="task-list-item"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过输入 mediaPipe FaceMesh（468 点）的输出数据来训练回归模型以生成 Blendmesh 权重</font></font></li>
<li class="task-list-item"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用StyleGan技术替换整个角色脸部网格</font></font></li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无需人形装备即可自动装备 3D 模型（使用 RigNet 等深度神经网络模型）</font></font></li>
<li class="task-list-item"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 PIFuHD 等模型自动生成完整的角色网格（正在进行中！）</font></font></li>
<li class="task-list-item"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用音频信号或自然语言处理方法详细制作 3D 角色嘴部动画</font></font></li>
<li class="task-list-item"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成完整的 3D 环境</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">资源</font></font></h2><a id="user-content-resources" class="anchor" aria-label="永久链接：资源" href="#resources"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">身体姿势估计：BlazePose 模型
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文：</font></font><a href="https://arxiv.org/abs/2006.10204" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BlazePose：设备上实时身体姿势跟踪</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手部姿势估计：MediaPipe 手部模型
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文：</font></font><a href="https://arxiv.org/abs/2006.10214" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MediaPipe Hands：设备上实时手部跟踪</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人脸检测：BlazeFace 模型
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文：</font></font><a href="https://arxiv.org/abs/1907.05047" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BlazeFace：移动 GPU 上的亚毫秒级神经人脸检测</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人脸标志生成器：MediaPipe 人脸标志模型
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文：</font></font><a href="https://arxiv.org/abs/1907.06724" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">移动 GPU 上的单目视频实时面部表面几何形状</font></font></a></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许可证和引用</font></font></h2><a id="user-content-licenses--citations" class="anchor" aria-label="永久链接：许可证和引用" href="#licenses--citations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数码人许可证</font></font></h3><a id="user-content-digihuman-licence" class="anchor" aria-label="永久链接：DigiHuman 许可证" href="#digihuman-licence"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序许可证：</font></font><a href="https://github.com/Danial-Kord/DigiHuman/blob/main/LICENSE.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPL-3.0 许可证</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
仅限非商业用途。如果您分发或传播修改或未修改的程序或其任何部分的副本，您必须向作为程序原作者的 Danial Kordmodanlou 提供适当的信用。该属性应包含在使用或显示本程序的任何位置。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FFmpeg</font></font><br></h3><a id="user-content-ffmpeg" class="anchor" aria-label="永久链接：FFmpeg" href="#ffmpeg"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"></font><a href="http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FFmpeg 根据GNU 宽通用公共许可证 (LGPL) 2.1 版或更高版本</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获得许可</font><font style="vertical-align: inherit;">。但是，FFmpeg 合并了</font></font><a href="http://www.gnu.org/licenses/old-licenses/gpl-2.0.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GNU 通用公共许可证 (GPL) 版本 2</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或更高版本中涵盖的几个可选部分和优化</font><font style="vertical-align: inherit;">。如果使用这些部分，则 GPL 适用于所有 FFmpeg。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Unity FFmpeg 软件包已获得</font></font><a href="https://github.com/keijiro/FFmpegOut/blob/master/LICENSE.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Keijiro Takahashi MIT的许可</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高干</font></font></h3><a id="user-content-gaugan" class="anchor" aria-label="永久链接：高干" href="#gaugan"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用NVIDIA 开发的</font></font><a href="https://github.com/NVlabs/SPADE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SPADE</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">存储库，并根据</font><a href="https://github.com/noyoshi/smart-sketch/blob/master/LICENSE"><font style="vertical-align: inherit;">GPL V 3.0</font></a><font style="vertical-align: inherit;">许可从</font></font><a href="https://github.com/noyoshi/smart-sketch"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Smart-Sketch</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行定制</font></font><a href="https://github.com/noyoshi/smart-sketch/blob/master/LICENSE"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></li>
</ul>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@inproceedings{park2019SPADE,
  title={Semantic Image Synthesis with Spatially-Adaptive Normalization},
  author={Park, Taesung and Liu, Ming-Yu and Wang, Ting-Chun and Zhu, Jun-Yan},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  year={2019}
}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@inproceedings{park2019SPADE,
  title={Semantic Image Synthesis with Spatially-Adaptive Normalization},
  author={Park, Taesung and Liu, Ming-Yu and Wang, Ting-Chun and Zhu, Jun-Yan},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  year={2019}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3D角色</font></font></h3><a id="user-content-3d-characters" class="anchor" aria-label="永久链接：3D 角色" href="#3d-characters"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://unity-chan.com/contents/license_en/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Unity-chan 模型</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://www.mixamo.com" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">mixamo 模型</font></font></a></p>

<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接触</font></font></h1><a id="user-content-contact" class="anchor" aria-label="永久链接：联系方式" href="#contact"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">丹尼尔·科尔莫丹卢 - </font></font><a href="mailto:kordmodanloo@gmail.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">kordmodanloo@gmail.com</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网站：</font></font><a href="https://danial-kord.github.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">danial-kord.github.io</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目链接：</font></font><a href="https://github.com/Danial-Kord/DigiHuman"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">github.com/Danial-Kord/DigiHuman</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">电报 ID：</font></font><a href="https://t.me/Danial_km" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">@Danial_km</font></font></a></p>
</article></div>
