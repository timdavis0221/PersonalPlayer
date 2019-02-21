# Personal Player

使用 ExoPlayer 來製作個人播放器

## 嘗試要做的功能 :

1. 新增手機上的影片到播放清單。
2. 新增網路上的影片到播放清單。
3. Seekbar 能累加播放輕單所有影片的時間，並在同個畫面播放所有加入的影片。
4. 點擊清單的影片能直接播放/暫停，影片播完能接著下個影片播。

## 目前進度 :

- 導入 module of exoplayer-core, exoplayer-ui, exoplayer-dash，並解決 support library 版本混用的問題。
- 使用 PlayerView, SimpleExoPlayer, MediaSource 初始化基本的播放器跟畫面來播範例 MP4 影片。

## Reference

1. [ExoPlayer Developer Guide](https://google.github.io/ExoPlayer/guide.html)
2. [Playing video by ExoPlayer](https://medium.com/fungjai/playing-video-by-exoplayer-b97903be0b33)
