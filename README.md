# lsd-steps
### 基于uview的steps组件
### 找了半天找不到能够点击的步骤条，没办法基于uView的步骤条组件自己改了个，发布上来给大家使用
### 很简单，支持change事件，其他同uview的steps组件
### 具体使用方法为：
```javascript
<lsd-steps 
:direction="stepsDirection" 
:current="stepsCurrent" 
:list="steps" 
:mode="stepsMode" 
:icon="stepsIcon" 
@change="scrollTo"
></lsd-steps>

scrollTo(index){
console.log(index)
this.stepsCurrent = index;
},
```
## 具体请参考 https://www.uviewui.com/components/steps.html
