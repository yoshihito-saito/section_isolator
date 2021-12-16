# Section Isolator
![section_isolator](https://user-images.githubusercontent.com/61833067/144965045-e983cca4-f713-49b6-bf29-88df3f0db54d.png)
## Create enviroment
1. download zip -> unzip
2. conda env create -f=env_hst.yml

## Usage
1. conda activate HST
2. jupyter lab
3. open section_isolator.ipynb

## Data
撮像したスライド画像のパスをリスト形式で入力。

例えば folder1/01_slide.tif, folder1/02_slide.tif, folder1/03_slide.tif となっていれば、

data_list = [folder1/01_slide.tif, folder1/02_slide.tif, folder1/03_slide.tif]

## Tips
切片は左上から縦に貼っていったものに対応。

きれいに切片を貼る必要がある。

切片間の距離を詰めすぎない！！


