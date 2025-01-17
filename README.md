# Graph-less Collaborative Filtering 复现


## Environment
The implementation for SimRec is under the following development environment:
* python=3.10.4
* torch=1.11.0
* numpy=1.22.3
* scipy=1.7.3

## data
rechorus中的数据集：
Grocery_and_Gourmet_Food：
MovieLens_1M：

## Usage
将工作区打开为'fx\ReChorus-master\SimRec',运行下列命令行

* Grocery_and_Gourmet_Food：
```
python main.py --data Grocery_and_Gourmet_Food： --cd 1e-1 --soft 10 --tempsoft 1e-2 --sc 5 --reg 1e-6
```
* MovieLens_1M：
```
python main.py --data MovieLens_1M： --sc 1 --soft 1e-1 --cd 1e-2
```
