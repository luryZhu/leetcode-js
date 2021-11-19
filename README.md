# leetcode js刷题记录

## 刷题路线

参考

https://github.com/Chocolate1999/leetcode-javascript

https://github.com/sl1673495/leetcode-javascript

记录更新在本仓库的 `Issues` 中，按照 `Labels` 分类

## 分类

### 二分查找

[题目列表](https://github.com/luryZhu/leetcode-js/labels/%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE)

通常维护 `l`，`r`，`m`

循环条件 `while(l<=r)` ，即 `l>r` 时中止

比较中值 `m` 与目标值的对应关系，缩小范围，通常

- 位运算取中值 `m=(l+r)>>1`

- 偏小，则缩左边界 `l=m+1`
- 偏大，则缩右边界 `r=m-1`

注意边界值



