<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">潜在扩散模型</font></font></h1><a id="user-content-latent-diffusion-models" class="anchor" aria-label="永久链接：潜在扩散模型" href="#latent-diffusion-models"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://arxiv.org/abs/2112.10752" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">arXiv</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> |</font></font><a href="#bibtex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">书目词典</font></font></a></p>
<p align="center" dir="auto">
<animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/CompVis/latent-diffusion/blob/main/assets/results.gif" data-target="animated-image.originalLink"><img src="/CompVis/latent-diffusion/raw/main/assets/results.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/CompVis/latent-diffusion/blob/main/assets/results.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="results.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/CompVis/latent-diffusion/raw/main/assets/results.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="814" height="407"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play results.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play results.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open results.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/CompVis/latent-diffusion/blob/main/assets/results.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image>
</p>
<p dir="auto"><a href="https://arxiv.org/abs/2112.10752" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用潜在扩散模型进行高分辨率图像合成</font></font></strong></a><br>
<a href="https://github.com/rromb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Robin Rombach</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> *、
</font></font><a href="https://github.com/ablattmann"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Andreas Blattmann</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> *、
</font></font><a href="https://github.com/qp-qp"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Dominik Lorenz</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、
</font></font><a href="https://github.com/pesser"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Patrick Esser</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、
</font></font><a href="https://hci.iwr.uni-heidelberg.de/Staff/bommer" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Björn Ommer</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 
* 同等贡献</font></font></p>
<p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="/CompVis/latent-diffusion/blob/main/assets/modelfigure.png"><img src="/CompVis/latent-diffusion/raw/main/assets/modelfigure.png" style="max-width: 100%;"></a>
</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">消息</font></font></h2><a id="user-content-news" class="anchor" aria-label="永久链接：新闻" href="#news"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2022 年 7 月</font></font></h3><a id="user-content-july-2022" class="anchor" aria-label="固定链接：2022 年 7 月" href="#july-2022"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在可以使用</font><font style="vertical-align: inherit;">用于运行</font></font><a href="https://arxiv.org/abs/2204.11824" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检索增强扩散模型的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推理代码和模型权重。请参阅</font></font><a href="#retrieval-augmented-diffusion-models"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本节</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2022 年 4 月</font></font></h3><a id="user-content-april-2022" class="anchor" aria-label="永久链接：2022 年 4 月" href="#april-2022"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">感谢</font></font><a href="https://github.com/crowsonkb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Katherine Crowson</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，无分类器指导获得了约 2 倍的加速，并且</font></font><a href="https://arxiv.org/abs/2202.09778" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PLMS 采样器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可用。另请参阅</font></font><a href="https://github.com/CompVis/latent-diffusion/pull/51" data-hovercard-type="pull_request" data-hovercard-url="/CompVis/latent-diffusion/pull/51/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此 PR</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的 1.45B</font></font><a href="#text-to-image"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">潜在扩散 LAION 模型</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font><a href="https://github.com/gradio-app/gradio"><font style="vertical-align: inherit;">Gradio</font></a><font style="vertical-align: inherit;">集成到</font></font><a href="https://huggingface.co/spaces" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Huggingface Spaces 🤗</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中。尝试一下网络演示：</font></font><a href="https://github.com/gradio-app/gradio"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://huggingface.co/spaces/multimodalart/latentdiffusion" rel="nofollow"><img src="https://camo.githubusercontent.com/5762a687b24495afb299c2c0bc68674a2a7dfca9bda6ee444b9da7617d4223a6/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f25463025394625413425393725323048756767696e67253230466163652d5370616365732d626c7565" alt="拥抱脸部空间" data-canonical-src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有更多预训练的 LDM 可供使用：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><a href="https://arxiv.org/abs/2111.02114" rel="nofollow"><font style="vertical-align: inherit;">在LAION-400M</font></a><font style="vertical-align: inherit;">数据库上训练的</font><font style="vertical-align: inherit;">1.45B</font></font><a href="#text-to-image"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="https://arxiv.org/abs/2111.02114" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"></font><a href="https://openreview.net/pdf?id=qw8AKxfYbI" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ImageNet 上的类条件模型，在使用无分类器指导</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">时实现了 3.6 的 FID </font><font style="vertical-align: inherit;">（可通过</font></font><a href="https://colab.research.google.com/github/CompVis/latent-diffusion/blob/main/scripts/latent_imagenet_diffusion.ipynb" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Colab Notebook</font></font></a> <a href="https://colab.research.google.com/github/CompVis/latent-diffusion/blob/main/scripts/latent_imagenet_diffusion.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取） 。</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求</font></font></h2><a id="user-content-requirements" class="anchor" aria-label="永久链接：要求" href="#requirements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以使用以下命令创建并激活</font><font style="vertical-align: inherit;">一个合适的</font></font><a href="https://conda.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">conda</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境：</font></font><code>ldm</code><font style="vertical-align: inherit;"></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>conda env create -f environment.yaml
conda activate ldm
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="conda env create -f environment.yaml
conda activate ldm" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预训练模型</font></font></h1><a id="user-content-pretrained-models" class="anchor" aria-label="永久链接：预训练模型" href="#pretrained-models"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有可用检查点的一般列表可通过我们的</font></font><a href="#model-zoo"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型动物园</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获得。如果您在工作中使用这些模型中的任何一个，我们总是很高兴收到</font></font><a href="#bibtex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引用</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检索增强扩散模型</font></font></h2><a id="user-content-retrieval-augmented-diffusion-models" class="anchor" aria-label="永久链接：检索增强扩散模型" href="#retrieval-augmented-diffusion-models"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/CompVis/latent-diffusion/blob/main/assets/rdm-preview.jpg"><img src="/CompVis/latent-diffusion/raw/main/assets/rdm-preview.jpg" alt="rdm-图" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
我们包括推理代码来运行我们的检索增强扩散模型（RDM），如</font></font><a href="https://arxiv.org/abs/2204.11824" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://arxiv.org/abs/2204.11824</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中所述。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，将额外必需的 python 包安装到您的</font></font><code>ldm</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境中</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install transformers==4.19.2 scann kornia==0.6.4 torchmetrics==0.6.0
pip install git+https://github.com/arogozhnikov/einops.git</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install transformers==4.19.2 scann kornia==0.6.4 torchmetrics==0.6.0
pip install git+https://github.com/arogozhnikov/einops.git" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并下载训练后的权重（初步检查点）：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>mkdir -p models/rdm/rdm768x768/
wget -O models/rdm/rdm768x768/model.ckpt https://ommer-lab.com/files/rdm/model.ckpt</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="mkdir -p models/rdm/rdm768x768/
wget -O models/rdm/rdm768x768/model.ckpt https://ommer-lab.com/files/rdm/model.ckpt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于这些模型以一组 CLIP 图像嵌入为条件，因此我们的 RDM 支持不同的推理模式，如下所述。</font></font></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅带有文本提示的 RDM（无需显式检索）</font></font></h4><a id="user-content-rdm-with-text-prompt-only-no-explicit-retrieval-needed" class="anchor" aria-label="永久链接：仅带有文本提示的 RDM（无需显式检索）" href="#rdm-with-text-prompt-only-no-explicit-retrieval-needed"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于 CLIP 提供了共享的图像/文本特征空间，并且 RDM 在训练期间学习覆盖给定示例的邻域，因此我们可以直接在其上获取给定提示和条件的 CLIP 文本嵌入。通过运行此模式</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python scripts/knn2img.py  --prompt "a happy bear reading a newspaper, oil on canvas"
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python scripts/knn2img.py  --prompt &quot;a happy bear reading a newspaper, oil on canvas&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有文本到图像检索功能的 RDM</font></font></h4><a id="user-content-rdm-with-text-to-image-retrieval" class="anchor" aria-label="永久链接：具有文本到图像检索的 RDM" href="#rdm-with-text-to-image-retrieval"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了能够运行以文本提示为条件的 RDM 以及从此提示检索到的图像，您还需要下载相应的检索数据库。我们提供从</font></font><a href="https://storage.googleapis.com/openimages/web/index.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Openimages</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/liaopeiyuan/artbench"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ArtBench</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据集提取的两个不同的数据库。交换数据库会导致模型的不同功能，如下所示，尽管两种情况下学习的权重相同。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://storage.googleapis.com/openimages/web/index.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载包含压缩为 CLIP 图像嵌入的检索数据集（ Openimages</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> (~11GB) 和</font></font><a href="https://github.com/liaopeiyuan/artbench"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ArtBench</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> (~82MB)）的</font><font style="vertical-align: inherit;">检索数据库：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>mkdir -p data/rdm/retrieval_databases
wget -O data/rdm/retrieval_databases/artbench.zip https://ommer-lab.com/files/rdm/artbench_databases.zip
wget -O data/rdm/retrieval_databases/openimages.zip https://ommer-lab.com/files/rdm/openimages_database.zip
unzip data/rdm/retrieval_databases/artbench.zip -d data/rdm/retrieval_databases/
unzip data/rdm/retrieval_databases/openimages.zip -d data/rdm/retrieval_databases/</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="mkdir -p data/rdm/retrieval_databases
wget -O data/rdm/retrieval_databases/artbench.zip https://ommer-lab.com/files/rdm/artbench_databases.zip
wget -O data/rdm/retrieval_databases/openimages.zip https://ommer-lab.com/files/rdm/openimages_database.zip
unzip data/rdm/retrieval_databases/artbench.zip -d data/rdm/retrieval_databases/
unzip data/rdm/retrieval_databases/openimages.zip -d data/rdm/retrieval_databases/" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们还</font><font style="vertical-align: inherit;">为 ArtBench提供经过训练的</font></font><a href="https://github.com/google-research/google-research/tree/master/scann"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ScaNN</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">搜索索引。下载并解压通过</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>mkdir -p data/rdm/searchers
wget -O data/rdm/searchers/artbench.zip https://ommer-lab.com/files/rdm/artbench_searchers.zip
unzip data/rdm/searchers/artbench.zip -d data/rdm/searchers</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="mkdir -p data/rdm/searchers
wget -O data/rdm/searchers/artbench.zip https://ommer-lab.com/files/rdm/artbench_searchers.zip
unzip data/rdm/searchers/artbench.zip -d data/rdm/searchers" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于 OpenImages 的索引很大（~21 GB），我们提供了一个脚本来创建并保存它以供采样期间使用。但请注意，如果没有此索引，则无法使用 OpenImages 数据库进行采样。通过运行脚本</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python scripts/train_searcher.py</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python scripts/train_searcher.py" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以通过以下方式开始使用视觉最近邻的基于检索的文本引导采样</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python scripts/knn2img.py  --prompt "a happy pineapple" --use_neighbors --knn &lt;number_of_neighbors&gt; 
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python scripts/knn2img.py  --prompt &quot;a happy pineapple&quot; --use_neighbors --knn <number_of_neighbors> " tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，支持的最大邻居数量为 20。可以通过 cmd 参数更改数据库，</font></font><code>--database</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该参数可以是</font></font><code>[openimages, artbench-art_nouveau, artbench-baroque, artbench-expressionism, artbench-impressionism, artbench-post_impressionism, artbench-realism, artbench-renaissance, artbench-romanticism, artbench-surrealism, artbench-ukiyo_e]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。使用时，</font><font style="vertical-align: inherit;">必须先执行</font></font><code>--database openimages</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上述脚本( )。</font></font><code>scripts/train_searcher.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于其相对较小的尺寸，artbench 数据库最适合创建更抽象的概念，并且不适用于详细的文本控制。</font></font></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">即将推出</font></font></h4><a id="user-content-coming-soon" class="anchor" aria-label="永久链接：即将推出" href="#coming-soon"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更好的模型</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更多决议</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图像到图像检索</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本转图像</font></font></h2><a id="user-content-text-to-image" class="anchor" aria-label="永久链接：文本到图像" href="#text-to-image"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/CompVis/latent-diffusion/blob/main/assets/txt2img-preview.png"><img src="/CompVis/latent-diffusion/raw/main/assets/txt2img-preview.png" alt="text2img-图" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载预训练的权重（5.7GB）</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>mkdir -p models/ldm/text2img-large/
wget -O models/ldm/text2img-large/model.ckpt https://ommer-lab.com/files/latent-diffusion/nitro/txt2img-f8-large/model.ckpt
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="mkdir -p models/ldm/text2img-large/
wget -O models/ldm/text2img-large/model.ckpt https://ommer-lab.com/files/latent-diffusion/nitro/txt2img-f8-large/model.ckpt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并采样</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python scripts/txt2img.py --prompt "a virus monster is playing guitar, oil on canvas" --ddim_eta 0.0 --n_samples 4 --n_iter 4 --scale 5.0  --ddim_steps 50
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python scripts/txt2img.py --prompt &quot;a virus monster is playing guitar, oil on canvas&quot; --ddim_eta 0.0 --n_samples 4 --n_iter 4 --scale 5.0  --ddim_steps 50" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这将在指定的输出位置</font><font style="vertical-align: inherit;">单独保存每个样本以及大小为</font></font><code>n_iter</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">x的网格（默认值</font><font style="vertical-align: inherit;">：）。质量、采样速度和多样性最好通过</font><font style="vertical-align: inherit;">、</font><font style="vertical-align: inherit;">和</font><font style="vertical-align: inherit;">参数来控制。根据经验，较高的值会</font><font style="vertical-align: inherit;">产生更好的样本，但代价是输出多样性降低。</font><font style="vertical-align: inherit;">
此外，增加通常也会提供更高质量的样本，但对于值 &gt; 250，回报会递减。</font><font style="vertical-align: inherit;">可以通过使用 来实现</font><font style="vertical-align: inherit;">快速采样（即 的低值），同时保持良好的质量</font><font style="vertical-align: inherit;">。通过使用</font><font style="vertical-align: inherit;">和</font><font style="vertical-align: inherit;">可以在保持良好质量的同时实现</font><font style="vertical-align: inherit;">
更快的采样（即更低的 值） </font><font style="vertical-align: inherit;">（请参阅</font><a href="https://arxiv.org/abs/2202.09778" rel="nofollow"><font style="vertical-align: inherit;">流形上扩散模型的伪数值方法</font></a><font style="vertical-align: inherit;">）。</font></font><code>n_samples</code><font style="vertical-align: inherit;"></font><code>outputs/txt2img-samples</code><font style="vertical-align: inherit;"></font><code>scale</code><font style="vertical-align: inherit;"></font><code>ddim_steps</code><font style="vertical-align: inherit;"></font><code>ddim_eta</code><font style="vertical-align: inherit;"></font><code>scale</code><font style="vertical-align: inherit;"></font><br><font style="vertical-align: inherit;"></font><code>ddim_steps</code><font style="vertical-align: inherit;"></font><code>ddim_steps</code><font style="vertical-align: inherit;"></font><code>--ddim_eta 0.0</code><font style="vertical-align: inherit;"></font><br><font style="vertical-align: inherit;"></font><code>ddim_steps</code><font style="vertical-align: inherit;"></font><code>--ddim_eta 0.0</code><font style="vertical-align: inherit;"></font><code>--plms</code><font style="vertical-align: inherit;"></font><a href="https://arxiv.org/abs/2202.09778" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">超过 256²</font></font></h4><a id="user-content-beyond-256" class="anchor" aria-label="永久链接：超越 256²" href="#beyond-256"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于某些输入，简单地以卷积方式在比训练时更大的特征上运行模型有时会产生有趣的结果。要尝试一下，请调整</font></font><code>H</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>W</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数（将被整数除以 8 以计算相应的潜在大小），例如运行</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python scripts/txt2img.py --prompt "a sunset behind a mountain range, vector image" --ddim_eta 1.0 --n_samples 1 --n_iter 1 --H 384 --W 1024 --scale 5.0  
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python scripts/txt2img.py --prompt &quot;a sunset behind a mountain range, vector image&quot; --ddim_eta 1.0 --n_samples 1 --n_iter 1 --H 384 --W 1024 --scale 5.0  " tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建大小为 384x1024 的样本。但请注意，与 256x256 设置相比，可控性有所降低。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下面的示例是使用上述命令生成的。
</font></font><a target="_blank" rel="noopener noreferrer" href="/CompVis/latent-diffusion/blob/main/assets/txt2img-convsample.png"><img src="/CompVis/latent-diffusion/raw/main/assets/txt2img-convsample.png" alt="text2img-图形-转换" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">修复</font></font></h2><a id="user-content-inpainting" class="anchor" aria-label="永久链接： 修复" href="#inpainting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/CompVis/latent-diffusion/blob/main/assets/inpainting.png"><img src="/CompVis/latent-diffusion/raw/main/assets/inpainting.png" alt="修复" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载预先训练的权重</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>wget -O models/ldm/inpainting_big/last.ckpt https://heibox.uni-heidelberg.de/f/4d9ac7ea40c64582b7c9/?dl=1
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="wget -O models/ldm/inpainting_big/last.ckpt https://heibox.uni-heidelberg.de/f/4d9ac7ea40c64582b7c9/?dl=1" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并采样</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python scripts/inpaint.py --indir data/inpainting_examples/ --outdir outputs/inpainting_results
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python scripts/inpaint.py --indir data/inpainting_examples/ --outdir outputs/inpainting_results" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><code>indir</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应包含图像</font></font><code>*.png</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和蒙版</font></font><code>&lt;image_fname&gt;_mask.png</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，如 中提供的示例</font></font><code>data/inpainting_examples</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类条件 ImageNet</font></font></h2><a id="user-content-class-conditional-imagenet" class="anchor" aria-label="永久链接：类条件 ImageNet" href="#class-conditional-imagenet"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="/CompVis/latent-diffusion/blob/main/scripts/latent_imagenet_diffusion.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过笔记本</font></font></a> <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可用</font></font><a href="https://colab.research.google.com/github/CompVis/latent-diffusion/blob/main/scripts/latent_imagenet_diffusion.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。
</font></font><a target="_blank" rel="noopener noreferrer" href="/CompVis/latent-diffusion/blob/main/assets/birdhouse.png"><img src="/CompVis/latent-diffusion/raw/main/assets/birdhouse.png" alt="类别条件" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无条件模型</font></font></h2><a id="user-content-unconditional-models" class="anchor" aria-label="永久链接：无条件模型" href="#unconditional-models"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们还提供了一个用于从无条件 LDM（例如 LSUN、FFHQ，...）中采样的脚本。通过启动它</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>CUDA_VISIBLE_DEVICES=<span class="pl-k">&lt;</span>GPU_ID<span class="pl-k">&gt;</span> python scripts/sample_diffusion.py -r models/ldm/<span class="pl-k">&lt;</span>model_spec<span class="pl-k">&gt;</span>/model.ckpt -l <span class="pl-k">&lt;</span>logdir<span class="pl-k">&gt;</span> -n <span class="pl-k">&lt;</span><span class="pl-cce">\#</span>samples<span class="pl-k">&gt;</span> --batch_size <span class="pl-k">&lt;</span>batch_size<span class="pl-k">&gt;</span> -c <span class="pl-k">&lt;</span><span class="pl-cce">\#</span>ddim steps<span class="pl-k">&gt;</span> -e <span class="pl-k">&lt;</span><span class="pl-cce">\#</span>eta<span class="pl-k">&gt;</span> </pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="CUDA_VISIBLE_DEVICES=<GPU_ID> python scripts/sample_diffusion.py -r models/ldm/<model_spec>/model.ckpt -l <logdir> -n <\#samples> --batch_size <batch_size> -c <\#ddim steps> -e <\#eta> " tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">培训您自己的 LDM</font></font></h1><a id="user-content-train-your-own-ldms" class="anchor" aria-label="永久链接：培训您自己的 LDM" href="#train-your-own-ldms"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据准备</font></font></h2><a id="user-content-data-preparation" class="anchor" aria-label="永久链接：数据准备" href="#data-preparation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">面孔</font></font></h3><a id="user-content-faces" class="anchor" aria-label="永久链接： 面孔" href="#faces"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要下载 CelebA-HQ 和 FFHQ 数据集，请按照</font></font><a href="https://github.com/CompVis/taming-transformers#celeba-hq"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">taming-transformers</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
存储库中的说明进行操作。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LSUN</font></font></h3><a id="user-content-lsun" class="anchor" aria-label="永久链接：LSUN" href="#lsun"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/fyu/lsun"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LSUN 数据集可以通过此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供的脚本方便地下载</font><font style="vertical-align: inherit;">。我们对训练图像和验证图像进行了自定义拆分，并在</font></font><a href="https://ommer-lab.com/files/lsun.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/lsun.zip</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上提供了相应的文件名。下载后，将它们解压到</font></font><code>./data/lsun</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.床/猫/教堂子集也应分别放置/符号链接于</font></font><code>./data/lsun/bedrooms</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">/ </font></font><code>./data/lsun/cats</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">/ </font></font><code>./data/lsun/churches</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">ImageNet</h3><a id="user-content-imagenet" class="anchor" aria-label="永久链接：ImageNet" href="#imagenet"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该代码将在第一次使用时</font><font style="vertical-align: inherit;">尝试下载（通过</font></font><a href="http://academictorrents.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Academic Torrents</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ）并准备ImageNet。然而，由于 ImageNet 相当大，这需要大量的磁盘空间和时间。如果您的磁盘上已经有 ImageNet，则可以通过将数据放入</font></font><code>${XDG_CACHE}/autoencoders/data/ILSVRC2012_{split}/data/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（默认为
</font></font><code>~/.cache/autoencoders/data/ILSVRC2012_{split}/data/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font><font style="vertical-align: inherit;">来加快速度
，其中 是</font><font style="vertical-align: inherit;">/</font></font><code>{split}</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">之一</font><font style="vertical-align: inherit;">。它应该具有以下结构：</font></font><code>train</code><font style="vertical-align: inherit;"></font><code>validation</code><font style="vertical-align: inherit;"></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>${XDG_CACHE}/autoencoders/data/ILSVRC2012_{split}/data/
├── n01440764
│   ├── n01440764_10026.JPEG
│   ├── n01440764_10027.JPEG
│   ├── ...
├── n01443537
│   ├── n01443537_10007.JPEG
│   ├── n01443537_10014.JPEG
│   ├── ...
├── ...
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="${XDG_CACHE}/autoencoders/data/ILSVRC2012_{split}/data/
├── n01440764
│   ├── n01440764_10026.JPEG
│   ├── n01440764_10027.JPEG
│   ├── ...
├── n01443537
│   ├── n01443537_10007.JPEG
│   ├── n01443537_10014.JPEG
│   ├── ...
├── ..." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您还没有提取数据，您还可以将
</font></font><code>ILSVRC2012_img_train.tar</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">/ </font></font><code>ILSVRC2012_img_val.tar</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（或它们的符号链接）
放入</font></font><code>${XDG_CACHE}/autoencoders/data/ILSVRC2012_train/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">/
中</font></font><code>${XDG_CACHE}/autoencoders/data/ILSVRC2012_validation/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，然后将其提取到上面的结构中，而无需再次下载。请注意，只有当文件夹</font></font><code>${XDG_CACHE}/autoencoders/data/ILSVRC2012_{split}/data/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和文件
</font><font style="vertical-align: inherit;">都不存在时才会发生这种情况
</font></font><code>${XDG_CACHE}/autoencoders/data/ILSVRC2012_{split}/.ready</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。如果您想强制再次运行数据集准备，请删除它们。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型训练</font></font></h2><a id="user-content-model-training" class="anchor" aria-label="永久链接：模型训练" href="#model-training"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">训练模型的日志和检查点保存到</font></font><code>logs/&lt;START_DATE_AND_TIME&gt;_&lt;config_spec&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">训练自动编码器模型</font></font></h3><a id="user-content-training-autoencoder-models" class="anchor" aria-label="永久链接：训练自动编码器模型" href="#training-autoencoder-models"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供了在 ImageNet 上训练 KL 正则化自动编码器的配置</font></font><code>configs/autoencoder</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。训练可以从跑步开始</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>CUDA_VISIBLE_DEVICES=&lt;GPU_ID&gt; python main.py --base configs/autoencoder/&lt;config_spec&gt;.yaml -t --gpus 0,    
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="CUDA_VISIBLE_DEVICES=<GPU_ID> python main.py --base configs/autoencoder/<config_spec>.yaml -t --gpus 0,    " tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其中是 { </font><font style="vertical-align: inherit;">(f=32, d=64), </font><font style="vertical-align: inherit;">(f=16, d=16),
 </font><font style="vertical-align: inherit;">(f=8, d=4), </font><font style="vertical-align: inherit;">(f=4, d=3)}</font></font><code>config_spec</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">之一。</font></font><code>autoencoder_kl_8x8x64</code><font style="vertical-align: inherit;"></font><code>autoencoder_kl_16x16x16</code><font style="vertical-align: inherit;"></font><code>autoencoder_kl_32x32x4</code><font style="vertical-align: inherit;"></font><code>autoencoder_kl_64x64x3</code><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要训&ZeroWidthSpace;&ZeroWidthSpace;练 VQ 正则化模型，请参阅</font></font><a href="https://github.com/CompVis/taming-transformers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">taming-transformers</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
存储库。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">培训 LDM</font></font></h3><a id="user-content-training-ldms" class="anchor" aria-label="永久链接：培训 LDM" href="#training-ldms"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们</font></font><code>configs/latent-diffusion/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供了在 LSUN-、CelebA-HQ、FFHQ 和 ImageNet 数据集上训练 LDM 的配置。训练可以从跑步开始</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>CUDA_VISIBLE_DEVICES=<span class="pl-k">&lt;</span>GPU_ID<span class="pl-k">&gt;</span> python main.py --base configs/latent-diffusion/<span class="pl-k">&lt;</span>config_spec<span class="pl-k">&gt;</span>.yaml -t --gpus 0,</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="CUDA_VISIBLE_DEVICES=<GPU_ID> python main.py --base configs/latent-diffusion/<config_spec>.yaml -t --gpus 0," tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其中</font></font><code>&lt;config_spec&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是 { </font></font><code>celebahq-ldm-vq-4</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(f=4, VQ-reg.自动编码器, 空间大小 64x64x3), </font></font><code>ffhq-ldm-vq-4</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(f=4, VQ-reg.自动编码器, 空间大小 64x64x3),
 </font></font><code>lsun_bedrooms-ldm-vq-4</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(f=4, VQ-reg.自动编码器, 空间大小) 之一64x64x3)，
 </font></font><code>lsun_churches-ldm-vq-4</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(f=8，KL-reg.自动编码器，空间大小32x32x4)，</font></font><code>cin-ldm-vq-8</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(f=8，VQ-reg.自动编码器，空间大小32x32x4)}。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型动物园</font></font></h1><a id="user-content-model-zoo" class="anchor" aria-label="永久链接：模型动物园" href="#model-zoo"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预训练的自动编码模型</font></font></h2><a id="user-content-pretrained-autoencoding-models" class="anchor" aria-label="永久链接：预训练的自动编码模型" href="#pretrained-autoencoding-models"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/CompVis/latent-diffusion/blob/main/assets/reconstruction2.png"><img src="/CompVis/latent-diffusion/raw/main/assets/reconstruction2.png" alt="记录2" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有模型均经过训练直至收敛（rFID 没有进一步的实质性改进）。</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">rFID 与 val</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">火车台阶</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">峰值信噪比</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PSIM</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关联</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">评论</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">f=4，VQ（Z=8192，d=3）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.58</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">533066</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">27.43+/-4.26</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.53+/-0.21</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/vq-f4.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/vq-f4.zip</font></font></a></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">f=4，VQ（Z=8192，d=3）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.06</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">658131</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">25.21+/-4.17</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.72+/-0.26</font></font></td>
<td><a href="https://heibox.uni-heidelberg.de/f/9c6681f64bb94338a069/?dl=1" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://heibox.uni-heidelberg.de/f/9c6681f64bb94338a069/?dl=1</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不注意</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">f=8，VQ（Z=16384，d=4）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.14</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">971043</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">23.07 +/- 3.99</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.17+/-0.36</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/vq-f8.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/vq-f8.zip</font></font></a></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">f=8，VQ（Z=256，d=4）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.49</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1608649</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">22.35+/-3.81</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.26+/-0.37</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/vq-f8-n256.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/vq-f8-n256.zip</font></font></a></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">f=16，VQ（Z=16384，d=8）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5.15</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1101166</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">20.83+/-3.61</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.73+/-0.43</font></font></td>
<td><a href="https://heibox.uni-heidelberg.de/f/0e42b04e2e904890a9b6/?dl=1" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://heibox.uni-heidelberg.de/f/0e42b04e2e904890a9b6/?dl=1</font></font></a></td>
<td></td>
</tr>
<tr>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">f=4，KL</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.27</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">176991</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">27.53+/-4.54</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.55+/-0.24</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/kl-f4.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/kl-f4.zip</font></font></a></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">f=8，KL</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.90</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">246803</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">24.19+/-4.19</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.02+/-0.35</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/kl-f8.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/kl-f8.zip</font></font></a></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">f=16，KL (d=16)</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.87</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">442998</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">24.08 +/- 4.22</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.07+/-0.36</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/kl-f16.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/kl-f16.zip</font></font></a></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">f=32，KL (d=64)</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.04</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">406763</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">22.27+/-3.93</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.41+/-0.40</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/kl-f32.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/kl-f32.zip</font></font></a></td>
<td></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取模型</font></font></h3><a id="user-content-get-the-models" class="anchor" aria-label="永久链接：获取模型" href="#get-the-models"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行以下脚本会下载并提取所有可用的预训练自动编码模型。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>bash scripts/download_first_stages.sh</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="bash scripts/download_first_stages.sh" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第一阶段模型可以在以下位置找到：</font></font><code>models/first_stage_models/&lt;model_spec&gt;</code></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预训练 LDM</font></font></h2><a id="user-content-pretrained-ldms" class="anchor" aria-label="永久链接：预训练的 LDM" href="#pretrained-ldms"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">日期</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">相信</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">普雷克</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记起</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关联</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">评论</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CelebA-总部</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无条件图像合成</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LDM-VQ-4（200 个无步骤，eta=0）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5.11 (5.11)</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3.29</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.72</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.49</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/celeba.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/celeba.zip</font></font></a></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FF总部</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无条件图像合成</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LDM-VQ-4（200 个无步骤，eta=1）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.98 (4.98)</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.50 (4.50)</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.73</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.50</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/ffhq.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/ffhq.zip</font></font></a></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LSUN-教堂</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无条件图像合成</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LDM-KL-8（400 步，eta=0）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.02 (4.02)</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.72</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.64</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.52</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/lsun_churches.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/lsun_churches.zip</font></font></a></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LSUN-卧室</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无条件图像合成</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LDM-VQ-4（200 个无步骤，eta=1）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.95 (3.0)</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.22 (2.23)</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.66</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.48</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/lsun_bedrooms.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/lsun_bedrooms.zip</font></font></a></td>
<td></td>
</tr>
<tr>
<td>ImageNet</td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类条件图像合成</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LDM-VQ-8（200 个无步骤，eta=1）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">7.77(7.76)* /15.82**</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">201.56(209.52)* /78.82**</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.84* / 0.65**</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.35* / 0.63**</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/cin.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/cin.zip</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">*：带引导，classifier_scale 10 **：不带引导，括号中的分数使用</font></font><a href="https://github.com/openai/guided-diffusion"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ADM提供的脚本计算</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概念性字幕</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本条件图像合成</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LDM-VQ-f4（100 DDIM 步骤，eta=0）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">16.79</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">13.89</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/text2img.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/text2img.zip</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从 LAION 进行微调</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开图像</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">超分辨率</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LDM-VQ-4</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/sr_bsr.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/sr_bsr.zip</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BSR 图像劣化</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开图像</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">布局到图像合成</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LDM-VQ-4（200 个无步骤，eta=0）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">32.02</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">15.92</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/layout2img_model.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/layout2img_model.zip</font></font></a></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">风景</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">语义图像合成</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LDM-VQ-4</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/semantic_synthesis256.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/semantic_synthesis256.zip</font></font></a></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">风景</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">语义图像合成</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LDM-VQ-4</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
<td><a href="https://ommer-lab.com/files/latent-diffusion/semantic_synthesis.zip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://ommer-lab.com/files/latent-diffusion/semantic_synthesis.zip</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在分辨率 512x512 上进行微调</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取模型</font></font></h3><a id="user-content-get-the-models-1" class="anchor" aria-label="永久链接：获取模型" href="#get-the-models-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上面列出的 LDM 可以通过以下方式联合下载和提取：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>bash scripts/download_models.sh</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="bash scripts/download_models.sh" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后可以在 中找到模型</font></font><code>models/ldm/&lt;model_spec&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">即将推出...</font></font></h2><a id="user-content-coming-soon-1" class="anchor" aria-label="永久链接：即将推出..." href="#coming-soon-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更多用于条件 LDM 的推理脚本。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与此同时，您可以使用我们的 Colab 笔记本</font></font><a href="https://colab.research.google.com/drive/1xqzUi2iXQXDqXBHQGP9Mqt2YrYW6cx-J?usp=sharing" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://colab.research.google.com/drive/1xqzUi2iXQXDqXBHQGP9Mqt2YrYW6cx-J?usp=sharing</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">评论</font></font></h2><a id="user-content-comments" class="anchor" aria-label="永久链接：评论" href="#comments"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的扩散模型代码库很大程度上建立在</font></font><a href="https://github.com/openai/guided-diffusion"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenAI 的 ADM 代码库</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
和</font></font><a href="https://github.com/lucidrains/denoising-diffusion-pytorch"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/lucidrains/denoising-diffusion-pytorch</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">之上。感谢开源！</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Transformer 编码器的实现来自</font><font style="vertical-align: inherit;">lucidrains</font><a href="https://github.com/lucidrains?tab=repositories"><font style="vertical-align: inherit;">的</font></a></font><a href="https://github.com/lucidrains/x-transformers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">x-transformers</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="https://github.com/lucidrains?tab=repositories"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">书目词典</font></font></h2><a id="user-content-bibtex" class="anchor" aria-label="永久链接： BibTeX" href="#bibtex"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@misc{rombach2021highresolution,
      title={High-Resolution Image Synthesis with Latent Diffusion Models}, 
      author={Robin Rombach and Andreas Blattmann and Dominik Lorenz and Patrick Esser and Björn Ommer},
      year={2021},
      eprint={2112.10752},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

@misc{https://doi.org/10.48550/arxiv.2204.11824,
  doi = {10.48550/ARXIV.2204.11824},
  url = {https://arxiv.org/abs/2204.11824},
  author = {Blattmann, Andreas and Rombach, Robin and Oktay, Kaan and Ommer, Björn},
  keywords = {Computer Vision and Pattern Recognition (cs.CV), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Retrieval-Augmented Diffusion Models},
  publisher = {arXiv},
  year = {2022},  
  copyright = {arXiv.org perpetual, non-exclusive license}
}


</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@misc{rombach2021highresolution,
      title={High-Resolution Image Synthesis with Latent Diffusion Models}, 
      author={Robin Rombach and Andreas Blattmann and Dominik Lorenz and Patrick Esser and Björn Ommer},
      year={2021},
      eprint={2112.10752},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

@misc{https://doi.org/10.48550/arxiv.2204.11824,
  doi = {10.48550/ARXIV.2204.11824},
  url = {https://arxiv.org/abs/2204.11824},
  author = {Blattmann, Andreas and Rombach, Robin and Oktay, Kaan and Ommer, Björn},
  keywords = {Computer Vision and Pattern Recognition (cs.CV), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Retrieval-Augmented Diffusion Models},
  publisher = {arXiv},
  year = {2022},  
  copyright = {arXiv.org perpetual, non-exclusive license}
}

" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</article></div>
