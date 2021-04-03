# fish_recognition English follows Japanese
Pagination_Scraping.ipynbでWEB魚図鑑というサイトから画像をスクレイピング。
Create_Dataset.ipynbでそれらの画像からデータセットを作成。
Fish_recognition.ipynbでCNNによる学習。
DataAugmentationにより約86%の精度が見込まれます。
判定した魚を使った料理のレシピを提案するものになっています。

I collect images from "WEB fish picture book" by "Pagination_Scraping.ipynb" which implements web scraping.
I create the dataset by "Create_Dataset.ipynb"
I train the model using CNN by "Fish_recognition.ipynb"
The accuracy must be about 86% by DataAugmentation.
Recipes which use recognized fish will be suggested.
