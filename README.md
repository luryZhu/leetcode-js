# leetcode js刷题记录

## 刷题路线

参考

https://github.com/Chocolate1999/leetcode-javascript

https://github.com/sl1673495/leetcode-javascript

记录更新在 [本仓库](https://github.com/luryZhu/leetcode-js) 的 `Issues` 中，按照 `Labels` 分类

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

### 二叉树

[题目列表](https://github.com/luryZhu/leetcode-js/issues?q=is%3Aissue+is%3Aopen+label%3A%E4%BA%8C%E5%8F%89%E6%A0%91)

#### DFS

深度优先，先遍历左子树再遍历右子树

函数出口：空结点

判断：是叶子结点，xx操作，是分支节点，递归

回溯：遍历完左右子树操作xx

## js特别注意

[函数嵌套](https://github.com/luryZhu/leetcode-js/issues/6)

[深拷贝，浅拷贝](https://github.com/luryZhu/leetcode-js/issues/7)





