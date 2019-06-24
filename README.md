# cifar10
元記事: https://qiita.com/yy1003/items/c590d1a26918e4abe512

各ファイル・ディレクトリの説明は以下のとおりです．  
###ディレクトリ
- models: 学習済みモデルを置いてあるディレクトリ   
-- ensemble_"数字".hdf5が，記事最後で紹介したアンサンブル学習の際の学習済みモデル   
- predictions: アンサンブル学習での予測を置いてあるディレクトリ  
-- pred_"数字".npy: アンサンブル学習に用いた各モデルの予測   
-- final_pred.npy: 各モデルの予測の平均
### ipython notebook
- cifar10.ipynb: 記事のコードを実行可能な形でまとめたnotebook
- predict.ipynb: 学習済みモデルを使用して予測をするためのnotebook．"models"ディレクトリを使用.

