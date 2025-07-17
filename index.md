# 直近の活動と成果物のご紹介

- 【作成日】： 2025年7月17日
- 【氏名】　： 田中 宏幸
- 【連絡先】： mxg00554@gmail.com


# 成果物リスト
- 個人製作ゲーム
- クロスシミュレーションシステム
- ノードベースパーティクルエディター
- 海洋レンダー
- GPUパーティクルエディター

# 個人製作ゲーム
直近の活動としましてローグライトシューティングゲーム「Planets Ambrosia」を2025年7月Steamにてリリースいたしました。<br>
ストアページのURL --><a href="https://store.steampowered.com/app/3737960/Planets_Ambrosia/">https://store.steampowered.com/app/3737960/Planets_Ambrosia/</a><br>

ゲームエンジン：Unity<br>
　　　制作人数：１人(画像制作の一部を外部に委託しております)<br>
　　　制作期間：２か月半<br>
得られたスキル：C#,C++(GPUパーティクルエディターの作成),Compute Shader(HLSL),Steamでアプリをリリースする為の手続き
### 特筆事項
- 画像の一部は生成AIを使用して作成されました。
- 音声は全てフリー音源を使用いたしました。
- エフェクトは自作ツールを用いて**全て自作いたしました**。
- コンピュートシェーダーを使用して大量のパーティクル描画を実現し、派手なエフェクトで爽快感を向上させました。
- Steamのクラウドセーブと実績はSteam.netを使用しました。
- 未リリースですがAndroid版も動作しております。

<video src="images/PlanetsAmbrosiaIntroduction.mp4#t=2" controls="true" width="800"></video>


# クロスシミュレーションシステム
使用言語：C++<br>
シミュレーション結果に基づいてボーンを制御する方式となっております。

<video src="images/Cross-simulation demo.mp4#t=3" controls="true" width="800"></video>

# ノードベースパーティクルエディター
プラットフォーム：Windows Formアプリケーション<br>
　　　　使用言語：C#,C++<br>
　　　　制作人数：１人<br>
　　　　制作期間：４か月（後に継続してメンテナス）<br>
<image src="images/Node-based Particle Editor.png"></image>
ノードを組み合わせてパーティクルの挙動を制御可能になっております。


# 海洋レンダー
プラットフォーム：Windows,Android,iOS<br>
　　　　使用言語：C++,HLSL<br>
　　　　制作人数：１人<br>
　　　　制作期間：１か月半<br>

<video src="images/Ocean Shader Demo.mp4" controls="true" width="800"></video>

# GPUパーティクルエディター
プラットフォーム：Windows,Unity<br>
　　　　使用言語：C#,C++,HLSL<br>
　　　　制作人数：１人<br>
　　　　制作期間：２か月半<br>
## 特筆事項
- 個人製作ゲーム「Planets Ambrosia」のパーティクルエフェクトの作成で使用しました。
- 画像をアトラス化及び事前アルファー乗算化して加算ブレンドとアルファーブレンドをまとめて１回のドローコールで描画させています。
- パーティクルの放出と更新は全てGPUにより処理されます。
- Unityで使用可能です。
- パーティクルの各プロパティーをファンクションカーブでアニメーションさせ、オプションでシェーダーコードを記述する事で込み入った制御も可能としております。(座標追従やコリジョンなど)

<video src="images/GPU Particle Editor.mp4" controls="true" width="800"></video>
<image src="images/GPU Particle Editor Screenshot.png"></image>
