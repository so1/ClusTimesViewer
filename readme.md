＃ClusTimes を設置してくれてありがとうございます
ClusTimesは、clusterのユーザー有志による草の根新聞メディアです。
このClusTimes Viewerをワールドに設置すると、自動的にClusTimesの最新版を読み込み、ワールドで記事を表示します。

#ClusTimes-Viewerの設置方法
 - [project foloder] Asset/prefabs/にある、ClusTimes Controllerを設置
 - [Hierarchy] UI->PlayerLocalUIを追加（すごく大きいですがサイズも場所もそのままで大丈夫）
 - PlayerLocalUIを開きsafeareaに、ClusTimes - local UIを設置
 - 記事を出したい位置に空のGameObject
 - LocalUIのインスペクタのScale/Position/Rotation Constraintのそれぞれに、さっきつくった空のGameObjectを指定し、Zeroのボタンを押す
 - これで設置場所を調整してください（モニタには前後があるのでご注意ください）
