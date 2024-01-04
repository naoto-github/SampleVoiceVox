# SampleVoiceVox
VoiceVoxのサンプル

# 設定方法

1. [VOICEBVOX ENGINE 0.14.6](https://github.com/VOICEVOX/voicevox_engine/releases/tag/0.14.6)から，エンジン本体をダウンロードする（取り敢えずはWindows（CPU版）で問題ない）．
2. ダウンロードしたファイルを圧縮・解凍ソフトの[7-Zip](https://7-zip.opensource.jp/)で解凍する（ファイルの拡張子を.7zにすると良い）．
3. 解凍したフォルダ内にある**run.exe** を実行する．
4. 実行すると下記の画面が表示され，VoiceVoxのサーバが起動する．サーバのIPアドレスやポート番号を確認すること．

[![Image from Gyazo](https://i.gyazo.com/9916288017a532da2b3cdc292840f714.png)](https://gyazo.com/9916288017a532da2b3cdc292840f714)

# 実行方法

1. SampleVoiceVox.ipynbを[Jupyter Lab](https://jupyter.org/)などを利用してローカルで実行する．
2. `generateVoice(text, speaker)`関数で，textで指定した文字列を，speakerで指定した話者で，音声合成する．
3. **sample.wav**として音声が保存されるので確認する．
