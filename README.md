# BFPRT
BFPRT algorithm


算法: BFPRT 

语言: python

作用: 给定无序list，选取最大n个数的index

输入: ctr_scores,N个数浮点无序数组

输出: largest_n_id,n个最大数的index

时间复杂度: O(N)

空间复杂度: O(N)

具体证明可见分治法，《算法设计与分析》第二版，屈婉玲、刘田、张立昂、王捍贫编著书籍

#### 使用方式：
        example1:
            array = [6,2,3,4,1]
            print(topN(array,3)) 
            print(topN(array,1)) 
            print(topN(array,0))
            print(topN(array,5))
        outputs:
            [0, 2, 3]
            [0]
            []
            [0, 1, 2, 3, 4]
其他用例请见代码
    
如需求的第n大的数，修改132-139行即可
