
> When asked to implement waterfall, I'm asking...
> - async function 
> - series function 
> - setImmidiate / setTimeout / process.nextTick

### 思路分析
- what: 
```
 * Runs the `tasks` array of functions in series, each passing their results to
 * the next in the array. However, if any of the `tasks` pass an error to their
 * own callback, the next function is not executed, and the main `callback` is
 * immediately called with the error.
```

- 

### 代码解析
- [秒懂版 `async-waterfall`](!https://github.com/es128/async-waterfall/blob/master/index.js)
- [优雅易读绕弯子版 `waterfall`](!https://github.com/caolan/async/blob/master/lib/waterfall.js)
- [私人轮子版 `waterfall`](!https://github.com/Joanna913/interview-questions/edit/master/waterfal.md)


### 其他拓展
- serialize 
