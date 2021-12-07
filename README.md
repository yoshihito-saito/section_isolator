# Section Isolator

## Create enviroment
1. download zip -> unzip
2. conda env create -f=env_name.yml

## Usage
1. conda activate HST
2. jupyter lab
3. open section_isolator.ipynb

## Data
撮像したスライド画像のパスをリスト形式で入力。

例えば folder1/01_slide, folder1/02_slide, folder1/03_slide となっていれば、

data_list = [folder1/01_slide, folder1/02_slide, folder1/03_slide]

として、入力。

## Tips
切片は左上から縦に貼っていったものに対応。

きれいに切片を貼る必要がある。

切片間の距離を詰めすぎない！！

