# JStructure
JavaScript 版本的数据结构，提供常用的数据结构封装，基于清华大学邓俊辉老师的数据结构课程

[![Build status](https://travis-ci.com/open-node/jstructures.svg?branch=master)](https://travis-ci.org/open-node/jstructures)
[![codecov](https://codecov.io/gh/open-node/jstructures/branch/master/graph/badge.svg)](https://codecov.io/gh/open-node/jstructures)

# 进度
* [x] List (linked-list)
* [x] Vector
* [x] Stack
* [x] Queue
* [x] SegmentTree
* [x] UnionFind
* [x] BinTree
  * [x] BST (BinanySearchTree)
  * [ ] BTree
* [ ] Graph
* [ ] Heap
  * [ ] MaxHeap
  * [ ] MinHeap
  * [ ] LeftHeap
* [ ] Priority Queue



<!-- Generated by documentation.js. Update this documentation by updating the source code. -->



<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

-   [AVL][1]
    -   [insert][2]
        -   [Parameters][3]
    -   [remove][4]
        -   [Parameters][5]
    -   [balanced][6]
        -   [Parameters][7]
    -   [AVLBalanced][8]
        -   [Parameters][9]
    -   [balFac][10]
        -   [Parameters][11]
    -   [height][12]
        -   [Parameters][13]
-   [BST][14]
    -   [search][15]
        -   [Parameters][16]
    -   [insert][17]
        -   [Parameters][18]
    -   [remove][19]
        -   [Parameters][20]
    -   [removeAt][21]
        -   [Parameters][22]
    -   [searchIn][23]
        -   [Parameters][24]
-   [BinNode][25]
    -   [Parameters][26]
    -   [data][27]
    -   [parent][28]
    -   [lc][29]
    -   [rc][30]
    -   [height][31]
    -   [size][32]
    -   [isRoot][33]
    -   [isLChild][34]
    -   [isRChild][35]
    -   [hasParent][36]
    -   [hasLChild][37]
    -   [hasRChild][38]
    -   [hasChild][39]
    -   [hasBothChild][40]
    -   [isLeaf][41]
    -   [sibling][42]
    -   [uncle][43]
    -   [fromParentTo][44]
    -   [pred][45]
    -   [succ][46]
    -   [insertAsLC][47]
        -   [Parameters][48]
    -   [insertAsRC][49]
        -   [Parameters][50]
    -   [travLevel][51]
        -   [Parameters][52]
    -   [travPre][53]
        -   [Parameters][54]
    -   [travIn][55]
        -   [Parameters][56]
    -   [travPost][57]
        -   [Parameters][58]
    -   [swap][59]
        -   [Parameters][60]
-   [BinTree][61]
    -   [size][62]
    -   [size][63]
        -   [Parameters][64]
    -   [empty][65]
    -   [root][66]
    -   [root][67]
        -   [Parameters][68]
    -   [updateHeightAbove][69]
        -   [Parameters][70]
    -   [insertAsRoot][71]
        -   [Parameters][72]
    -   [insertAsLC][73]
        -   [Parameters][74]
    -   [insertAsRC][75]
        -   [Parameters][76]
    -   [attachAsLC][77]
        -   [Parameters][78]
    -   [attachAsRC][79]
        -   [Parameters][80]
    -   [remove][81]
        -   [Parameters][82]
    -   [secede][83]
        -   [Parameters][84]
    -   [travLevel][85]
        -   [Parameters][86]
    -   [travPre][87]
        -   [Parameters][88]
    -   [travIn][89]
        -   [Parameters][90]
    -   [travPost][91]
        -   [Parameters][92]
-   [ListNode][93]
    -   [Parameters][94]
    -   [insertAsSucc][95]
        -   [Parameters][96]
    -   [insertAsPred][97]
        -   [Parameters][98]
-   [List][99]
    -   [Parameters][100]
    -   [size][101]
    -   [first][102]
    -   [last][103]
    -   [insertAsFirst][104]
        -   [Parameters][105]
    -   [insertAsLast][106]
        -   [Parameters][107]
    -   [insertA][108]
        -   [Parameters][109]
    -   [insertB][110]
        -   [Parameters][111]
    -   [remove][112]
        -   [Parameters][113]
    -   [disordered][114]
    -   [findElem][115]
        -   [Parameters][116]
    -   [search][117]
        -   [Parameters][118]
    -   [deduplicate][119]
    -   [uniquify][120]
    -   [traverse][121]
        -   [Parameters][122]
    -   [valid][123]
        -   [Parameters][124]
    -   [selectMax][125]
        -   [Parameters][126]
    -   [insertionSort][127]
        -   [Parameters][128]
    -   [selectionSort][129]
        -   [Parameters][130]
    -   [merge][131]
        -   [Parameters][132]
    -   [mergeSort][133]
        -   [Parameters][134]
-   [Queue][135]
    -   [enqueue][136]
        -   [Parameters][137]
    -   [dequeue][138]
    -   [front][139]
    -   [empty][140]
    -   [size][141]
-   [SegmentTree][142]
    -   [Parameters][143]
    -   [size][144]
    -   [size][145]
    -   [leftChild][146]
        -   [Parameters][147]
    -   [rightChild][148]
        -   [Parameters][149]
    -   [build][150]
        -   [Parameters][151]
    -   [query][152]
        -   [Parameters][153]
    -   [update][154]
        -   [Parameters][155]
    -   [find][156]
        -   [Parameters][157]
    -   [union][158]
        -   [Parameters][159]
    -   [isConnected][160]
        -   [Parameters][161]
-   [SegmentTree][162]
    -   [Parameters][163]
    -   [size][164]
    -   [size][165]
    -   [leftChild][166]
        -   [Parameters][167]
    -   [rightChild][168]
        -   [Parameters][169]
    -   [build][170]
        -   [Parameters][171]
    -   [query][172]
        -   [Parameters][173]
    -   [update][174]
        -   [Parameters][175]
    -   [find][176]
        -   [Parameters][177]
    -   [union][178]
        -   [Parameters][179]
    -   [isConnected][180]
        -   [Parameters][181]
-   [Stack][182]
    -   [push][183]
        -   [Parameters][184]
    -   [pop][185]
    -   [top][186]
    -   [empty][187]
    -   [size][188]
-   [Vector][189]
    -   [Parameters][190]
    -   [size][191]
    -   [insert][192]
        -   [Parameters][193]
    -   [removeRange][194]
        -   [Parameters][195]
    -   [remove][196]
        -   [Parameters][197]
    -   [disordered][198]
    -   [findElem][199]
        -   [Parameters][200]
    -   [search][201]
        -   [Parameters][202]
    -   [deduplicate][203]
    -   [uniquify][204]
    -   [traverse][205]
        -   [Parameters][206]
    -   [binSearch][207]
        -   [Parameters][208]
    -   [bubbleSort][209]
        -   [Parameters][210]
    -   [merge][211]
        -   [Parameters][212]
    -   [mergeSort][213]
        -   [Parameters][214]

## AVL

**Extends BST**

AVL 类(AVL 树, 继承自 BST)

Returns **[AVL][215]** Instance

### insert

插入元素

#### Parameters

-   `e` **Anyone** 要插入的数据元素

Returns **[BinNode][216]** 

### remove

删除元素, 注意是删除节点，非节点为根的子树

#### Parameters

-   `e` **Anyone** 要插入的数据元素

Returns **[Boolean][217]** 是否成功删除

### balanced

判断某个节点是否理想平衡即：左右高度相等

#### Parameters

-   `x`  
-   `要判断的节点` **[BinNode][216]** 

Returns **[Boolean][217]** 

### AVLBalanced

判断某个节点是否AVL平衡即：-2&lt;左高度-右高度&lt;2

#### Parameters

-   `x`  
-   `要判断的节点` **[BinNode][216]** 

Returns **[Boolean][217]** 

### balFac

获取节点的平衡因子 x.lc.height - x.rc.height;

#### Parameters

-   `x`  
-   `要判断的节点` **[BinNode][216]** 

Returns **[number][218]** 左子树高度和右子树高度的差值

### height

获取节点的高度

#### Parameters

-   `x`  
-   `要判断的节点` **[BinNode][216]** 

Returns **[number][218]** 节点高度，空树高 -1， 叶子高 0

## BST

**Extends BinTree**

BST 类(二叉搜索树类, 继承自 BinTree)

Returns **[BST][219]** Instance

### search

查找元素 e 所在的节点

#### Parameters

-   `e` **Anyone** 要搜索的元素

Returns **\[[BinNode][216]]** 返回两项，第一项是搜索命中的节点，第二项是命中节点的父节点

### insert

插入元素

#### Parameters

-   `e` **Anyone** 要插入的数据元素

Returns **[BinNode][216]** 

### remove

删除元素, 注意是删除节点，非节点为根的子树

#### Parameters

-   `e` **Anyone** 要插入的数据元素

Returns **[Boolean][217]** 是否成功删除

### removeAt

删除某个节点

#### Parameters

-   `x` **[BinNode][216]** 要删除的节点

Returns **[BinNode][216]** 返回接替者

### searchIn

以 v 为根节点查找元素 e 所在的节点

#### Parameters

-   `v` **[BinNode][216]** 要搜索的树的根节点
-   `e` **Anyone** 要搜索的元素
-   `parent`  
-   `p` **[BinNode][216]** 当前搜索节点的父节点

Returns **\[[BinNode][216]]** 返回两项，第一项是搜索命中的节点，第二项是命中节点的父节点

## BinNode

BinNode 类(二叉树节点类)

### Parameters

-   `e` **Anyone**  (optional, default `null`)
-   `parent` **[BinNode][216]** 父节点 (optional, default `null`)
-   `lc` **[BinNode][216]** 左子节点 (optional, default `null`)
-   `rc` **[BinNode][216]** 右子节点 (optional, default `null`)

Returns **[BinNode][216]** Instance

### data

节点存储数据

### parent

父节点

### lc

左子节点

### rc

右子节点

### height

以该节点为根的树高度

### size

节点为根的子树规模

Returns **[Boolean][217]** 

### isRoot

判断是否是根节点

Returns **[Boolean][217]** 

### isLChild

判断是否是左子节点

Returns **[Boolean][217]** 

### isRChild

判断是否是右子节点

Returns **[Boolean][217]** 

### hasParent

判断是否有父节点

Returns **[Boolean][217]** 

### hasLChild

判断是有左子节点

Returns **[Boolean][217]** 

### hasRChild

判断是有左子节点

Returns **[Boolean][217]** 

### hasChild

判断是有子节点

Returns **[Boolean][217]** 

### hasBothChild

判断是有完整子节点 (即左右子节点都有)

Returns **[Boolean][217]** 

### isLeaf

判断是否是叶子节点(没有子节点)

Returns **[Boolean][217]** 

### sibling

兄弟节点

Returns **[BinNode][216]** 

### uncle

叔叔节点(即父节点的兄弟节点)

Returns **[BinNode][216]** 

### fromParentTo

获取来自父节点的引用

Returns **[Array][220]** [object, key]

### pred

获取中序遍历下的直接前驱

Returns **[BinNode][216]** 返回前驱节点，不存在则返回 null

### succ

获取中序遍历下的直接后继

Returns **[BinNode][216]** 返回后继节点，不存在则返回 null

### insertAsLC

将元素作为左子节点插入

#### Parameters

-   `e` **Anyone** 

Returns **[BinNode][216]** 返回插入额节点

### insertAsRC

将元素作为右子节点插入

#### Parameters

-   `e` **Anyone** 

Returns **[BinNode][216]** 返回插入额节点

### travLevel

当前节点作为根节点的子树层次遍历 BFS

#### Parameters

-   `p`  
-   `visit`  
-   `访问函数` **[function][221]** 

Returns **void** 

### travPre

当前节点作为根节点的子树前序遍历 DFS

#### Parameters

-   `p` **[BinNode][216]** 遍历的节点
-   `visit`  
-   `访问函数` **[function][221]** 

Returns **void** 

### travIn

当前节点作为根节点的子树中序遍历 DFS

#### Parameters

-   `p` **[BinNode][216]** 遍历的节点
-   `visit`  
-   `访问函数` **[function][221]** 

Returns **void** 

### travPost

当前节点作为根节点的子树后序遍历 DFS

#### Parameters

-   `p` **[BinNode][216]** 遍历的节点
-   `visit`  
-   `访问函数` **[function][221]** 

Returns **void** 

### swap

交换量几个节点的数据

#### Parameters

-   `node1` **[BinNode][216]** 要交换的节点1
-   `node2` **[BinNode][216]** 要交换的节点2

Returns **void** 

## BinTree

BinTree 类(二叉树类)

Returns **[BinTree][222]** Instance

### size

树的规模

Returns **[number][218]** 

### size

更新树的规模

#### Parameters

-   `num`  

Returns **[number][218]** 

### empty

树是否为空

Returns **[Boolean][217]** 

### root

树根节点

Returns **[BinNode][216]** 

### root

重置根节点

#### Parameters

-   `_root`  

Returns **[BinNode][216]** 

### updateHeightAbove

更新节点以及祖先节点的高度

#### Parameters

-   `p` **[BinNode][216]** 要更新的节点

Returns **[number][218]** 返回更新后的高度

### insertAsRoot

作为树根节点插入

#### Parameters

-   `e` **Anyone** 要插入的数据元素

Returns **[BinNode][216]** 

### insertAsLC

作为节点的左孩子插入

#### Parameters

-   `p` **[BinNode][216]** 要插入的位置
-   `e` **Anyone** 要插入的数据元素

Returns **[BinNode][216]** 

### insertAsRC

作为节点的右孩子插入

#### Parameters

-   `p` **[BinNode][216]** 要插入的位置
-   `e` **Anyone** 要插入的数据元素

Returns **[BinNode][216]** 

### attachAsLC

作为节点的左孩子接入子树

#### Parameters

-   `p` **[BinNode][216]** 要插入的位置
-   `s` **[BinTree][222]** 要接入的数

Returns **[BinNode][216]** 

### attachAsRC

作为节点的右孩子接入子树

#### Parameters

-   `p` **[BinNode][216]** 要插入的位置
-   `s` **[BinTree][222]** 要接入的数

Returns **[BinNode][216]** 

### remove

删除某个节点作为根的子树

#### Parameters

-   `p` **[BinNode][216]** 要删除的根节点

Returns **[number][218]** 返回删除节点的总个数

### secede

分离某个节点作为根的子树

#### Parameters

-   `p` **[BinNode][216]** 要删除的根节点

Returns **[BinTree][222]** 返回分离出来的子树

### travLevel

树的层次遍历

#### Parameters

-   `visit`  
-   `访问函数` **[function][221]** 

Returns **void** 

### travPre

树的前序遍历

#### Parameters

-   `visit`  
-   `访问函数` **[function][221]** 

Returns **void** 

### travIn

树的中序遍历

#### Parameters

-   `visit`  
-   `访问函数` **[function][221]** 

Returns **void** 

### travPost

树的后序遍历

#### Parameters

-   `visit`  
-   `访问函数` **[function][221]** 

Returns **void** 

## ListNode

ListNode 类

### Parameters

-   `e` **Anyone?** 初始数组

Returns **[ListNode][223]** Instance

### insertAsSucc

将 元素 e 作为当前节点的直接后继插入

#### Parameters

-   `e` **Anyone** 

Returns **[ListNode][223]** 

### insertAsPred

将 元素 e 作为当前节点的直接前驱插入

#### Parameters

-   `e` **Anyone** 

Returns **[ListNode][223]** 

## List

Linked-list 类

### Parameters

-   `_elem` **[Array][220]** 初始数组

Returns **[List][224]** Instance

### size

获取列表长度/大小

Returns **[number][218]** 

### first

获取列表首节点

Returns **[ListNode][223]** 

### last

获取列表末节点

Returns **[ListNode][223]** 

### insertAsFirst

将 e 作为首节点插入列表

#### Parameters

-   `e` **Anyone** 

Returns **[ListNode][223]** 

### insertAsLast

将 e 作为末节点插入列表

#### Parameters

-   `e` **Anyone** 

Returns **[ListNode][223]** 

### insertA

e 作为节点 p 的直接后继插入

#### Parameters

-   `p`  
-   `e` **Anyone** 

Returns **[number][218]** 

### insertB

e 作为节点 p 的直接前驱插入

#### Parameters

-   `p`  
-   `e` **Anyone** 

Returns **[number][218]** 

### remove

删除指定节点 p

#### Parameters

-   `p` **[number][218]** 要删除元素

Returns **Anyone** e 删除的元素

### disordered

返回列表中相邻元素逆序对总数, 当返回为0则代表列表有序

Returns **[Number][218]** 

### findElem

从节点p往前查找目标元素 e 所在最后节点, 最多查询 n 个

#### Parameters

-   `e` **Anyone** 要搜索的元素
-   `n` **[number][218]** 最大搜索次数 (optional, default `this[size]`)
-   `p` **[ListNode][223]** 从p节点往前查找, 默认为 tailer，查找全部 (optional, default `this[tailer]`)

Returns **[ListNode][223]** 等于 e 的元素最后的节点

### search

从节点p的n的真前驱中查找不大于 e 的最后者

#### Parameters

-   `e` **Anyone** 要搜索的元素
-   `n` **[number][218]** 最大搜索次数 (optional, default `this[size]`)
-   `p` **[ListNode][223]** 从p节点往前查找, 默认为 tailer，查找全部 (optional, default `this[tailer]`)

Returns **[ListNode][223]** 等于 e 的元素最后的节点

### deduplicate

剔除重复元素，保证每个元素都是唯一的

Returns **[number][218]** 被删除的元素个数

### uniquify

有序列表剔除重复元素，保证每个元素都是唯一的

Returns **[number][218]** 被删除的元素个数

### traverse

向量的遍历

#### Parameters

-   `visit` **[function][221]** 访问函数

Returns **any** void

### valid

判断节点是否合法，存在，且不是首尾哨兵

#### Parameters

-   `p` **[ListNode][223]** 

Returns **[boolean][217]** 

### selectMax

从起始位置 p 的n个元素中找到最大者, 相同大小后者优先

#### Parameters

-   `p` **[ListNode][223]** 排序起始节点 (optional, default `this[header].succ`)
-   `n` **[number][218]**  (optional, default `this[size]`)

Returns **[ListNode][223]** 

### insertionSort

列表的插入排序, 对起始位置为 p 的 n 的元素进行排序

#### Parameters

-   `p` **[ListNode][223]** 排序起始节点 (optional, default `this[header].succ`)
-   `n` **[number][218]**  (optional, default `this[size]`)

Returns **[ListNode][223]** 排序后的起始节点

### selectionSort

列表的选择排序, 对起始位置为 p 的 n 的元素进行排序

#### Parameters

-   `p` **[ListNode][223]** 排序起始节点 (optional, default `this[header].succ`)
-   `n` **[number][218]**  (optional, default `this[size]`)

Returns **[ListNode][223]** 排序后的起始节点

### merge

列表的归并排序之归并, 对起始位置为 p 的 n 的元素进行排序

#### Parameters

-   `p` **[ListNode][223]** 合并起始节点
-   `n` **[number][218]** 
-   `he` **[List][224]** 要合并的另外一个列表
-   `q` **[ListNode][223]** 合并的另外一个列表起始节点
-   `m` **[number][218]** 要合并的另外一个列表的节点数

Returns **[ListNode][223]** 归并后的起始节点

### mergeSort

列表的归并排序, 对起始位置为 p 的 n 的元素进行排序

#### Parameters

-   `p` **[ListNode][223]** 排序起始节点 (optional, default `this[header].succ`)
-   `n` **[number][218]**  (optional, default `this[size]`)

Returns **[ListNode][223]** 排序后的起始节点

## Queue

Queue 类

Returns **[Queue][225]** Instance

### enqueue

e 加入队列尾部(排队)

#### Parameters

-   `e` **Anyone** 

Returns **void** 

### dequeue

将队首出队

Returns **Anyone** e 之前压入的元素

### front

指向队首元素

Returns **Anyone** e 之前压入的元素

### empty

判断队列是否为空

Returns **[Boolean][217]** 

### size

当前队列列长度(规模)

Returns **[number][218]** 

## SegmentTree

Segment-tree 线段树(区间树)类

### Parameters

-   `data`  
-   `mergeFn`  
-   `_elem` **[Array][220]** 初始数组

Returns **[List][224]** Instance

### size

获取数据长度/大小

Returns **[number][218]** 

### size

获取数据长度/大小

Returns **[number][218]** 

### leftChild

左节点的索引

#### Parameters

-   `index`  

Returns **[number][218]** 

### rightChild

右节点的索引

#### Parameters

-   `index`  

Returns **[number][218]** 

### build

构建线段树

#### Parameters

-   `index`  
-   `left`  
-   `right`  

Returns **void** 

### query

查询线段树的某一区间

#### Parameters

-   `qL` **[Number][218]** 查询的区间开始值
-   `qR` **[Number][218]** 查询的区间结束值

Returns **Anyone** 

### update

更新某个值

#### Parameters

-   `index` **[Number][218]** 原数组的索引
-   `val` **Anyone** 修改后的值

Returns **void** 

### find

查找p所属的集合编号

#### Parameters

-   `p` **[Number][218]** 

Returns **[Number][218]** 

### union

链接两个元素

#### Parameters

-   `p` **[Number][218]** 
-   `q` **[Number][218]** 

Returns **void** 

### isConnected

判断两个元素是否相连

#### Parameters

-   `p` **[Number][218]** 
-   `q` **[Number][218]** 

Returns **[Boolean][217]** 

## SegmentTree

Segment-tree 线段树(区间树)类

### Parameters

-   `size`  
-   `_elem` **[Array][220]** 初始数组

Returns **[List][224]** Instance

### size

获取数据长度/大小

Returns **[number][218]** 

### size

获取数据长度/大小

Returns **[number][218]** 

### leftChild

左节点的索引

#### Parameters

-   `index`  

Returns **[number][218]** 

### rightChild

右节点的索引

#### Parameters

-   `index`  

Returns **[number][218]** 

### build

构建线段树

#### Parameters

-   `index`  
-   `left`  
-   `right`  

Returns **void** 

### query

查询线段树的某一区间

#### Parameters

-   `qL` **[Number][218]** 查询的区间开始值
-   `qR` **[Number][218]** 查询的区间结束值

Returns **Anyone** 

### update

更新某个值

#### Parameters

-   `index` **[Number][218]** 原数组的索引
-   `val` **Anyone** 修改后的值

Returns **void** 

### find

查找p所属的集合编号

#### Parameters

-   `p` **[Number][218]** 

Returns **[Number][218]** 

### union

链接两个元素

#### Parameters

-   `p` **[Number][218]** 
-   `q` **[Number][218]** 

Returns **void** 

### isConnected

判断两个元素是否相连

#### Parameters

-   `p` **[Number][218]** 
-   `q` **[Number][218]** 

Returns **[Boolean][217]** 

## Stack

Stack 类

Returns **[Stack][226]** Instance

### push

e 作为压入栈顶

#### Parameters

-   `e` **Anyone** 

Returns **void** 

### pop

将栈顶出栈

Returns **Anyone** e 之前压入的元素

### top

指向栈顶元素，并不出栈

Returns **Anyone** e 之前压入的元素

### empty

判断栈是否为空

Returns **[Boolean][217]** 

### size

当前栈高度(规模)

Returns **[Number][218]** 

## Vector

### Parameters

-   `_elem` **[Array][220]** 初始数组 (optional, default `[]`)

Returns **[Vector][227]** Instance

### size

获取向量大小

Returns **[number][218]** 

### insert

e 作为秩为 r 的元素插入，原后继元素依次后移

#### Parameters

-   `r` **[number][218]** 插入新元素的秩 0 &lt;= r &lt;= size
-   `e` **Anyone** 

Returns **[number][218]** 

### removeRange

删除指定区间的元素, 原后继元素依次前移\[lo, hi)

#### Parameters

-   `lo` **[number][218]** 要删除元素起始的秩 0 &lt;= r &lt;= size
-   `hi` **[number][218]** 要删除元素结束的秩 0 &lt;= r &lt;= size

Returns **[number][218]** 删除的元素数量

### remove

删除指定秩的元素, 原后继元素依次前移

#### Parameters

-   `r` **[number][218]** 要删除元素的秩 0 &lt;= r &lt;= size

Returns **Anyone** e 删除的元素

### disordered

返回向量中相邻元素逆序对总数, 当返回为0则代表向量有序

Returns **[Number][218]** 

### findElem

在向量的区间 \[lo, hi)查找元素等于 e 的最大秩

#### Parameters

-   `e` **Anyone** 要搜索的元素
-   `lo` **[number][218]** 要查找的起始秩 (optional, default `0`)
-   `hi` **[number][218]** 要查找的结束秩 (optional, default `_elem.length`)

Returns **[number][218]** 等于 e 的元素最大的秩

### search

在有序向量的区间\[lo, hi)查找元素e 所在的秩, 0 &lt;= lo &lt;= hi &lt;= size

#### Parameters

-   `e` **Anyone** 要搜索的元素
-   `lo` **[number][218]** 要查找的起始秩
-   `hi` **[number][218]** 要查找的结束秩

Returns **[number][218]** 不大于 e 的元素最大的秩

### deduplicate

剔除重复元素，保证每个元素都是唯一的

Returns **[number][218]** 被删除的元素个数

### uniquify

有序向量剔除重复元素，保证每个元素都是唯一的

Returns **[number][218]** 被删除的元素个数

### traverse

向量的遍历

#### Parameters

-   `visit` **[function][221]** 访问函数

Returns **any** void

### binSearch

在有序向量的区间\[lo, hi)查找元素不大于 e 的元素的最大秩, 0 &lt;= lo &lt;= hi &lt;= size

#### Parameters

-   `_elem` **[Vector][227]** 要搜索的有序向量或有序数组
-   `e` **Anyone** 要搜索的元素
-   `lo` **[number][218]** 要查找的起始秩 (optional, default `0`)
-   `hi` **[number][218]** 要查找的结束秩 (optional, default `_elem.length`)

Returns **[number][218]** 不大于 e 的元素最大的秩

### bubbleSort

排序算法 起泡排序, 具有稳定性

#### Parameters

-   `_elem` **[Vector][227]** 要排序的向量或数据
-   `lo` **[number][218]** 要查找的起始秩 (optional, default `0`)
-   `hi` **[number][218]** 要查找的结束秩 (optional, default `_elem.length`)

Returns **void** 

### merge

排序算法 归并排序之合并

#### Parameters

-   `_elem` **[Vector][227]** 要排序的向量或数据
-   `lo` **[number][218]** 要查找的起始秩
-   `mi`  
-   `hi` **[number][218]** 要查找的结束秩

Returns **void** 

### mergeSort

排序算法 归并排序

#### Parameters

-   `_elem` **[Vector][227]** 要排序的向量或数据
-   `lo` **[number][218]** 要查找的起始秩 (optional, default `0`)
-   `hi` **[number][218]** 要查找的结束秩 (optional, default `_elem.length`)

Returns **void** 

[1]: #avl

[2]: #insert

[3]: #parameters

[4]: #remove

[5]: #parameters-1

[6]: #balanced

[7]: #parameters-2

[8]: #avlbalanced

[9]: #parameters-3

[10]: #balfac

[11]: #parameters-4

[12]: #height

[13]: #parameters-5

[14]: #bst

[15]: #search

[16]: #parameters-6

[17]: #insert-1

[18]: #parameters-7

[19]: #remove-1

[20]: #parameters-8

[21]: #removeat

[22]: #parameters-9

[23]: #searchin

[24]: #parameters-10

[25]: #binnode

[26]: #parameters-11

[27]: #data

[28]: #parent

[29]: #lc

[30]: #rc

[31]: #height-1

[32]: #size

[33]: #isroot

[34]: #islchild

[35]: #isrchild

[36]: #hasparent

[37]: #haslchild

[38]: #hasrchild

[39]: #haschild

[40]: #hasbothchild

[41]: #isleaf

[42]: #sibling

[43]: #uncle

[44]: #fromparentto

[45]: #pred

[46]: #succ

[47]: #insertaslc

[48]: #parameters-12

[49]: #insertasrc

[50]: #parameters-13

[51]: #travlevel

[52]: #parameters-14

[53]: #travpre

[54]: #parameters-15

[55]: #travin

[56]: #parameters-16

[57]: #travpost

[58]: #parameters-17

[59]: #swap

[60]: #parameters-18

[61]: #bintree

[62]: #size-1

[63]: #size-2

[64]: #parameters-19

[65]: #empty

[66]: #root

[67]: #root-1

[68]: #parameters-20

[69]: #updateheightabove

[70]: #parameters-21

[71]: #insertasroot

[72]: #parameters-22

[73]: #insertaslc-1

[74]: #parameters-23

[75]: #insertasrc-1

[76]: #parameters-24

[77]: #attachaslc

[78]: #parameters-25

[79]: #attachasrc

[80]: #parameters-26

[81]: #remove-2

[82]: #parameters-27

[83]: #secede

[84]: #parameters-28

[85]: #travlevel-1

[86]: #parameters-29

[87]: #travpre-1

[88]: #parameters-30

[89]: #travin-1

[90]: #parameters-31

[91]: #travpost-1

[92]: #parameters-32

[93]: #listnode

[94]: #parameters-33

[95]: #insertassucc

[96]: #parameters-34

[97]: #insertaspred

[98]: #parameters-35

[99]: #list

[100]: #parameters-36

[101]: #size-3

[102]: #first

[103]: #last

[104]: #insertasfirst

[105]: #parameters-37

[106]: #insertaslast

[107]: #parameters-38

[108]: #inserta

[109]: #parameters-39

[110]: #insertb

[111]: #parameters-40

[112]: #remove-3

[113]: #parameters-41

[114]: #disordered

[115]: #findelem

[116]: #parameters-42

[117]: #search-1

[118]: #parameters-43

[119]: #deduplicate

[120]: #uniquify

[121]: #traverse

[122]: #parameters-44

[123]: #valid

[124]: #parameters-45

[125]: #selectmax

[126]: #parameters-46

[127]: #insertionsort

[128]: #parameters-47

[129]: #selectionsort

[130]: #parameters-48

[131]: #merge

[132]: #parameters-49

[133]: #mergesort

[134]: #parameters-50

[135]: #queue

[136]: #enqueue

[137]: #parameters-51

[138]: #dequeue

[139]: #front

[140]: #empty-1

[141]: #size-4

[142]: #segmenttree

[143]: #parameters-52

[144]: #size-5

[145]: #size-6

[146]: #leftchild

[147]: #parameters-53

[148]: #rightchild

[149]: #parameters-54

[150]: #build

[151]: #parameters-55

[152]: #query

[153]: #parameters-56

[154]: #update

[155]: #parameters-57

[156]: #find

[157]: #parameters-58

[158]: #union

[159]: #parameters-59

[160]: #isconnected

[161]: #parameters-60

[162]: #segmenttree-1

[163]: #parameters-61

[164]: #size-7

[165]: #size-8

[166]: #leftchild-1

[167]: #parameters-62

[168]: #rightchild-1

[169]: #parameters-63

[170]: #build-1

[171]: #parameters-64

[172]: #query-1

[173]: #parameters-65

[174]: #update-1

[175]: #parameters-66

[176]: #find-1

[177]: #parameters-67

[178]: #union-1

[179]: #parameters-68

[180]: #isconnected-1

[181]: #parameters-69

[182]: #stack

[183]: #push

[184]: #parameters-70

[185]: #pop

[186]: #top

[187]: #empty-2

[188]: #size-9

[189]: #vector

[190]: #parameters-71

[191]: #size-10

[192]: #insert-2

[193]: #parameters-72

[194]: #removerange

[195]: #parameters-73

[196]: #remove-4

[197]: #parameters-74

[198]: #disordered-1

[199]: #findelem-1

[200]: #parameters-75

[201]: #search-2

[202]: #parameters-76

[203]: #deduplicate-1

[204]: #uniquify-1

[205]: #traverse-1

[206]: #parameters-77

[207]: #binsearch

[208]: #parameters-78

[209]: #bubblesort

[210]: #parameters-79

[211]: #merge-1

[212]: #parameters-80

[213]: #mergesort-1

[214]: #parameters-81

[215]: #avl

[216]: #binnode

[217]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Boolean

[218]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number

[219]: #bst

[220]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Array

[221]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Statements/function

[222]: #bintree

[223]: #listnode

[224]: #list

[225]: #queue

[226]: #stack

[227]: #vector
