create env

```bash
conda create -n wineq python=3.11 -y
```

activate env
```
conda activate wineq
```

install the req
```
pip install -r requirements.txt
```


```
git init
```

```
dvc init
```

```
dvc add data_given/winequality.csv
```
```
git add .
```
```
git commit -m "first commit"
```
```
git remote add origin https://github.com/Likhi2005/WineQualityCheck.git
```
```
git branch -M main
```
