# 8528d-WebUI

## これは何？
「[AIとコラボして神絵師になる 論文で読み解くStable Diffusion](https://ivtv.page.link/ap)」の表紙でコラボした[852話さん](https://twitter.com/8co28)が作った [8528-diffusion](https://huggingface.co/852wa/8528-diffusion) v0.2 をGoogle Colab上で起動したWebUIで使用するコードです。

- GPU搭載PCなど不要
- 難しいインストールも不要
- ボスが来た！ブラウザを閉じるだけ
- もちろん無料で利用できる

- [記念ツイート](https://twitter.com/8co28/status/1600367719140188160)

## 本家852話さんによる解説

- [ブログ](https://note.com/852wa/n/n212ab941e8ce)

### v0.1→v0.2の記述から
2022/12/7
https://huggingface.co/852wa/8528-diffusion
8528d-v0-2.ckptを公開しました。

v0.1からの変更点


*  人物がより出やすく、安定しやすくなった
* より多くの作風が出やすくなった
* 若干絵がクリアになった
* 全体的なディティールアップ
* ckptファイル名を短縮

## 用意するもの/使い方

- [Google Colab](https://colab.research.google.com/github/kaitas/8528d-WebUI/blob/main/8528_diffusion_v0_2_WebUI.ipynb)
- Hugging Faceのアカウント
  - Settings→ [Access Tokens](https://huggingface.co/settings/tokens) で Token を取得しておく 

- 最後の実行ステップで

```
Running on local URL:  http://127.0.0.1:7860
Running on public URL: https://hogehoge.gradio.app
```

と出てくるURLをブラウザの gradio.app のURLを別ウインドウで開くと、[AUTOMATIC1111 WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui)が動きます。
あとはプロンプトを入力して「Generate」するなり、img2imgするなりお好きなように！


## 起動したWebUIの例

![](https://pbs.twimg.com/media/FjfvQAzVIAAoR3n?format=jpg&name=4096x4096)

### 作例 by しらいはかせ

![](https://pbs.twimg.com/media/Fjfu21MUUAIlvMN?format=png&name=small)
