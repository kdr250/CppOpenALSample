# C++ OpenAL Sample
C++とOpenALを学習する用のレポジトリ

## ビルド方法
### ネイティブの場合
[Build a project](https://github.com/microsoft/vscode-cmake-tools/blob/main/docs/how-to.md#build-a-project) を参考にして、ビルドして実行。

### Webの場合
1. プロジェクト直下で `emcmake cmake -B build-web -G Ninja` を実行。
2. `cmake --build build-web` を実行。
3. `python -m http.server -d build-web` を実行してWebサーバー起動。
4. ブラウザで `http://localhost:8000/main.html` にアクセスして確認。

## 参考にしたURL
- [GitHub - openal-soft](https://github.com/kcat/openal-soft)
- [GitHub - openal-soft > examples > alplay.c](https://github.com/kcat/openal-soft/blob/master/examples/alplay.c)
- [emscripten - Audio](https://emscripten.org/docs/porting/Audio.html)
