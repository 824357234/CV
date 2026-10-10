# superglue

## 局限
SuperGlue 的效果很好，但有两个瓶颈：
- 全局 cross-attention 太贵（O(N²)）
- 每一层都要执行 cross-attention，缺乏自适应能力


## 方法