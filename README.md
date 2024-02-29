# Description

reproduce webstorm's import subpath module bug


# Current

## 1. auto import

Incorrect import path when use auto import. (ctrl+space)

![reproduce-1.png](image%2Freproduce-1.png)


## 2. not found sub module's declaration

Not found sub module's declaration in webstorm

![reproduce-2.png](image%2Freproduce-2.png)


# Expect

Find subpath module's declaration and auto import is works fine. 


# Reproduce

1. clone this repository
    - `git clone https://github.com/ChoSeoHwan/webstorm-bug-report-1.git`
2. install package
    - `yarn install`
