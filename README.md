# MachineLearningC4.5
决策树之 C4.5 算法（未完待续）

----------------------------------------------

# 数据集
|  Day  |    OutLook      |   Temperature   |   Humidity   |   Wind   |  PlayTennis  |
| :---: | :-------------: | :-------------: | :----------: | :------: | :----------: |
| 1     | Sunny           | 85              | 85           | False    | No           |
| 2     | Sunny           | 80              | 90           | True     | No           |
| 3     | Overcast        | 83              | 78           | False    | Yes          |
| 4     | Rainy           | 70              | 96           | False    | Yes          |
| 5     | Rainy           | 68              | 80           | False    | Yes          |
| 6     | Rainy           | 65              | 70           | True     | No           |
| 7     | Overcast        | 64              | 65           | True     | Yes          |
| 8     | Sunny           | 72              | 95           | False    | No           |
| 9     | Sunny           | 69              | 70           | False    | Yes          |
| 10    | Rainy           | 75              | 80           | False    | Yes          |
| 11    | Sunny           | 75              | 70           | True     | Yes          |
| 12    | Overcast        | 72              | 90           | True     | Yes          |
| 13    | Overcast        | 81              | 75           | False    | Yes          |
| 14    | Rainy           | 71              | 80           | True     | No           |

-----------------------------------

# 决策树
```text
OutLook
    Sunny->Humidity
        >70->No
        <=70->Yes
    Overcast->Yes
    Rainy->Windy
        False->Yes
        True->No
```

-----------------------------------

　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　本人CSDN博客 [点击链接](http://blog.csdn.net/lemon_tree12138)