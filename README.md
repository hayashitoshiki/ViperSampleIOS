# ViperSampleIOS


## 概要
VIPER  
V：View　　　 ：画面描画
I：Interactor：ビジネスロジック  
P：Presenter ：UIロジック  
E：Entity    ：モデル  
R：Router    ：画面遷移  

## イメージ
MVPの進化系  
M(Model)V(View)P(Presenter)→M(Model)V(View)P(Presenter)R(Router)

* Presentasion層  
  * View  
       --storyBoard：画面レイアウト  
       --ViewController：画面描画、アクション受け取り
  * Presenter：UIロジック     
  * Router：画面遷移  

* Domain層
  * Interactor：ビジネスロジック
  * Entity　　 ：データモデル
