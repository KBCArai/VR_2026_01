\# VR\_2026\_01



Unreal Engine 5.1 を使用した VR デバッグ検証用プロジェクト。  

ターゲット起動・色変更・Debug HUD 表示・開始トリガー Volume などの実装例を含む。



---



\## 🛠 開発環境



\- Unreal Engine 5.1

\- OpenXR

\- Meta Quest 3s（Link / AirLink）

\- Windows 11

\- Visual Studio 2022（C++使用時）



---



\## ▶ 起動手順



1\. VR デバイスをUSBケーブルでPCに接続

2.meta Horizon Linkを起動

3.VR デバイス内のメニューから「link」を開き、PCに接続

4.Epic Launcher から Unreal Engine 5.1 を起動

5.Githubで共有されたUE5プロジェクトを開く

6.【BPのみで使用する場合、この手順は不要】 必要に応じて右クリック → Generate Visual Studio project files

5\.UE5エディタ上から VR Preview 実行



---



\## 🕶 VR 実行条件



\- Meta Quest を Link 接続

\- OpenXR Runtime を Oculus に設定



---



\## 🧪 実装済みの内容



\- ターゲット被弾時の色変更（Dynamic Material Instance）※最初の2つ以外は設定変更必要

\- Debug Widget ワールド表示（目の前に出る赤い文字のログ）

\- Start Volume によるゲーム開始処理（ゲーム開始時刻の取得・表示）

\- BP\_Target 起動制御（特定の床に触れるとターゲットが向きを変える）

\- VRPawn DebugLog 表示（目の前に出る赤い文字のログ）

\- ライティング影響検証



---





