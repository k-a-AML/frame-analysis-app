# 2次元骨組簡易解析ワークスペース (Windows版)

ブラウザ向けに開発された2次元骨組解析エンジンをデスクトップ向けにパッケージングした、教育・学習支援用の簡易構造解析アプリケーションです。

直感的なモデリング操作により、剛性マトリクス法による弾性応力解析を実行し、変形挙動・断面力図（軸力・せん断力・曲げモーメント）・応力度を2D図面およびリアルタイム3Dビューで視覚的に確認できます。

---

## 配布およびインストール方法 (Download)

本ソフトウェアのWindows用インストーラー（`.msi`）およびZIP配布版は、本リポジトリ右側の **[Releases](../../releases)** よりダウンロードしてください。

- **対象OS**: Windows 10 / 11 (64bit)
- **形式**: Windows インストーラー パッケージ (`.msi`)
- **提供形態**: インストーラーによるバイナリ配布（※ソースコードおよび内部スクリプト一式は非公開です）

---

## 利用規約 (Terms of Use)

本ソフトウェア（プログラム本体、UIデザイン、インストーラー）に関する著作権は、**近畿大学建築学部 建築数理研究室** に帰属します。

教育・研究機関における学習支援を目的として無償提供を行っておりますが、**オープンソースソフトウェア（改変・二次配布の自由許諾）ではありません**。

- **利用対象者**: 建築構造分野等の教育・研究に携わる教員、研究者、およびその指導下にある関係者
- **許諾範囲**: 講義、演習、ゼミナール、学術研究における学習支援目的での私的・学内利用
- **禁止事項**:
  - 本ソフトウェア（インストーラーパッケージを含む）の無断での二次配布、転載、Web上への再公開
  - 商業目的の設計業務や営利活動での無断利用
  - プログラムのリバースエンジニアリング、逆コンパイル、内部リソースの抽出・改変

---

## 同梱ライブラリのライセンス表示 (Third-Party Licenses)

本アプリケーションの3Dグラフィックス表示部には、オープンソースライブラリ「Three.js」（コアライブラリおよびカメラ操作コンポーネント OrbitControls.js を含む）が組み込まれてコンパイルされています。MITライセンスの規約に基づき、以下に著作権表示および許諾条文を掲示します。

### Three.js (including OrbitControls)
- **対象コンポーネント**: `three.min.js`, `OrbitControls.js`
- **著作権表示**: Copyright © 2010-2021 Three.js Authors
- **公式サイト**: [https://threejs.org/](https://threejs.org/)
- **ライセンス**: MIT License

```text
The MIT License

Copyright © 2010-2021 three.js authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

---

## 免責事項 (Disclaimer)

1. 本ソフトウェアは、構造力学・建築構造学の学習および現象理解の支援を目的とした教育用簡易解析ツールです。
2. 計算精度やアルゴリズムの妥当性には配慮しておりますが、提示される計算結果（部材変位、断面力、応力度等）の完全性・正確性を保証するものではありません。
3. 実建物の構造計算、実務設計、確認申請用書類の作成、あるいは施工現場での最終安全確認への適用は固くお断りいたします。
4. 本ツールの利用または利用不能により生じたいかなる直接的・間接的損害（業務上のトラブル、事故等を含む）についても、開発者および所属研究機関は一切の法的責任・賠償義務を負いません。
