# Mirika downloads

**ここは配布用のミラーです。アプリのソースコードは置いていません。**

Mirika 本体のダウンロード(Windows / macOS / Linux)と、Chrome 拡張・OBS オーバーレイ・SDK・書類一式を配っています。
製品情報と使い方は [mirika.dev](https://mirika.dev/) をご覧ください。
質問・不具合報告は [公式 Discord](https://discord.gg/fnmUau5qzB) へ、最新情報は [X @mirika_dev](https://x.com/mirika_dev) でどうぞ。

## ダウンロード

[Releases](../../releases) の一番上が最新版です。

| ファイル | 中身 |
| --- | --- |
| `Mirika-Setup-<版>.exe` | Windows インストーラ(通常版。NVIDIA の GPU を見つけると、初回起動時に CUDA を自動で後入れします) |
| `Mirika-Setup-<版>-cuda.exe` | Windows インストーラ(CUDA 同梱版。NVIDIA の GPU をお使いならこちらがおすすめ) |
| `Mirika-<版>-mac-arm64.dmg` | macOS(Apple Silicon)。**署名と公証がまだのため未署名**です。対応が済むまでは、腕に覚えのある方が自己責任でお使いください |
| `Mirika-<版>-linux-x86_64.AppImage` | Linux |
| `mirika-obs-overlays.zip` | 配信用の OBS オーバーレイ(HTML) |
| `mirika-sdk.zip` | ゴーストの梱包・人格回帰テストの道具 |
| `mirika-chrome-extension.zip` | ブラウザ連携の拡張機能 |
| `mirika-docs-ja.zip` | 書類一式の PDF(要件定義書・基本設計書・詳細設計書・機能仕様書・運用手順書・テスト仕様書。0.6.9 の先行版から) |

`-beta` や `-rc` の付いた版は試用版です。ふだんお使いになるなら、付いていない版をお選びください。

## 「Source code (zip)」について

リリースのページには、GitHub が**すべてのリリースに自動で付ける**「Source code (zip)」「Source code (tar.gz)」が並びます。
**これはアプリのソースではなく、この README だけが入った数百バイトのファイル**です(GitHub の仕様で消せません)。
アプリ本体のソースは非公開のリポジトリにあり、ここには置いていません。

なお、上の表のうち **OBS オーバーレイ・SDK・Chrome 拡張は中身をそのまま読めます** —— 手を入れて使っていただくためのものです。

## 不具合のご報告

アプリの `/log file` で動作ログのフォルダが開きます。その日のファイルを添えていただけると原因がすぐ分かります(API キーなどの秘密は伏せ字になっています)。

---

**This is a download mirror. It does not contain the application's source code.**

Installers for [Mirika](https://mirika.dev/) (Windows / macOS / Linux), plus the OBS overlays, SDK, Chrome extension, and (from the 0.6.9 previews on) the Japanese document set as PDF (`mirika-docs-ja.zip`).

Windows has two installers: `Mirika-Setup-<version>.exe` (standard; it adds CUDA on first launch when it finds an NVIDIA GPU) and `Mirika-Setup-<version>-cuda.exe` (CUDA bundled; recommended for NVIDIA GPUs). The macOS `.dmg` is not signed or notarized yet. Versions with `-beta` or `-rc` are previews; pick one without a suffix for everyday use.

Every GitHub release automatically gets "Source code (zip)" / "Source code (tar.gz)" links. **Those contain only this README** — a few hundred bytes — not the application. GitHub does not allow removing them. The application source lives in a private repository.

The OBS overlays, SDK, and Chrome extension *are* readable and meant to be modified.
