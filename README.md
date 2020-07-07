＃rcnn_Lung

DICOM画像から肺結節を検出する
 
# Requirement
 
* mrcnn
* pydicom
*tensorflow==v1.x
*keras==2.2.5

 
# Installation
 
Colab Notebookに上記のライブラリをインストールするコマンドを記載してある。
セルを実行するとインストールが始まります。

# Usage
Colabで開くを押すとノートブックが開かれます。あとはセルを一つずつ実行すると実行されます。

＃注意
mrcnnはTensorflow v2.0は対応していないためインストールを忘れないこと
DICOM形式の画像の為、OpenCVやPIL等の画像読み込みライブラリは使用できない。
#課題
画像データが154枚と少なかった為か、出力結果がとても汚かった。
次回以降はさらにデータを増やして実行したい。

＃作者
*奈良岡 伶

＃参考文献
*医療AIとディープラーニングシリーズPythonによる医療画像処理入門
*MASK-RCNN sample starter code
(https://www.kaggle.com/drt2290078/mask-rcnn-sample-starter-code)
 
