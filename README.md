-------------------------
### Run octopress-bitcoin-donation-aside-Google-Colab

https://colab.research.google.com/drive/1OShIMVcFZ_khsUIBOIV1lzrqAGo1gfm_?usp=sharing

-------------------------

This is a new custom aside for [Octopress](https://github.com/imathis/octopress?ref=commandbarr) that shows a QR Code and an address to send [Bitcoin](http://bitcoin.org) donations to.

To install copy the files included to your octopress installation.

**DO NOT OVERWRITE THE `_config.yml` FILE**

In your existing `_config.yml` you simply add the following line at the very bottom.

`# Bitcoin Donations`

`bitcoin: 13BrFJVFX6ao7LtzqR92vgYeMBC3va6pe8`

Obviously change the address to your own, or keep mine. I don't mind. ;)

Then change the line:

`default_asides: [`

Add to it:

`custom/asides/bitcoin.html`

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=parttimelegend&url=https://github.com/PartTimeLegend/octopress-bitcoin-donation-aside&title=Octopress Bitcoin Donation Aside&language=&tags=github&category=software) [![tip for next commit](http://tip4commit.com/projects/889.svg)](http://tip4commit.com/github/PartTimeLegend/octopress-bitcoin-donation-aside)
