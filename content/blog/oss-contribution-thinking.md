---
title: 貢獻開源專案的收穫和觀察
date: '2019-01-27T09:44:00.000Z'
tags: ["open source", "programming"]
---

大約從今年1月初以來，我開始重拾貢獻開源專案，主要是在 [enzyme](https://github.com/airbnb/enzyme/) 這個專案上。這篇文章想談的倒不是如何貢獻開源專案、送PR的流程等等，只是這一個月以來的心得和觀察。

## 為什麼要貢獻開源專案？

在我還是學生的時候，就已經有嘗試過貢獻開源專案。開始工作之後因為各種因素，一直到最近才有時間和動力重新再開始。

一開始貢獻專案的時候，不可否認地，很大一部分是想做到很厲害的事情。或許是對自己的信心不足，或是覺得自己的履歷空空的。當時覺得，**如果能夠貢獻一些程式到很大的開源專案，那應該是一件很厲害、很酷的事情吧**，所以就去做了。做了一陣子之後，我發現雖然我真的送了一些 PR 過去，也有一些被 merge 進去了，但我並沒有很開心。而且我發現我開始會焦慮的等回覆和 code review，或是擔心自己的程式碼有問題。

我開始嘗試去想，到底在貢獻專案的過程中，什麼才是真正有價值的呢？什麼才是讓我有動力去做的呢？

回想了一下整個過程，我發現讓我開心，或覺得有收穫的，是在

1. 研究程式碼的運作方式
2. 得到回饋、不一樣的想法的時候。

研究專案的程式碼、搞懂平常在用的工具背後的運作模式時，會讓我有種成就感，同時也會學到東西；而在 code review 或是討論 API 格式，得到 maintainer 或其它成員的不同回饋時，也會讓我學到別人不一樣的看法，這也會讓我覺得開心。我發現這些才是真正能推動我去貢獻開源專案的動力，也是我收穫最多的地方。

當 PR 真正被 merge 進去、github profile 上多了一個記錄時當然也是會開心一下下。但那就是順水推舟的結果了。

## maintainer 真的很辛苦

大部分的專案 maintainer 都很少，即使有名如 [react](https://github.com/facebook/react)，也就是幾個人而已。我最近參與的 enzyme 更是只有 [Jordan Harband](https://github.com/ljharb) 一個人而已。作為 maintainer，除了 code contribution 還要負責回覆 issues、code review等等，非常多的工作，做了還往往被使用者當作理所當然，所以 maintainer 真的非常辛苦。即使你可能沒有時間幫忙，寫封信說聲謝謝或抖內一下都是件好事。

## 不是只有 code contribution 才叫貢獻開源專案

協助重現 bug、幫忙回覆 issue、寫文件等等也是一種貢獻的方式。這可以減輕 maintainer 的負擔。而且在做這些事的過程中，也會讓你更熟悉專案及其社群，甚至可能延伸出一些實作的好點子。如果你想參與一個專案，但發現有很多 bugfix issue 都已經有人在做了，不妨可以先從這些事情參與。

## 當你的留言沒有人回覆的時候

當 maintainer 沒有注意到你的回覆時，不需要覺得是不是自己的發言有問題而放棄。很可能只是 maintainer 太忙而疏忽了。你可以嘗試過一兩天再留言一次，或者如果專案本身有 gitter 或 IRC 等即時聊天的平台，直接上去問 maintainer 通常可以得到回覆。如果你盡力聯繫 maintainer 了但還是都沒有回應，暫時先放著去做其它的事情，或是直接先做一個 proof of concept 丟出來得到更多討論，也是一個好方法。