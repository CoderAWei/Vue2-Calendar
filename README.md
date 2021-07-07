# Vue2-Calendar
Vue实现的日历组件 可实现点击多选，滑动多选，切换周起始日

##  Attributes

| 参数        | 说明                | 类型    | 可选值     | 默认值 |
| ----------- | ------------------- | ------- | ---------- | ------ |
| can-select  | 是否开启选择日期项  | Boolean | true/false | false  |
| selectMode  | 选择模式：点击/滑动 | String  | click/move | click  |
| startOfWeek | 周起始日            | Number  | [1,7]      | 1      |
| width       | 整个日历的宽度      | String  | -          | 70%    |
| tbodyHeight | 日期的高度          | String  | -          | 60px   |

##  Events

| 事件名       | 说明                   | 参数      |
| ------------ | ---------------------- | --------- |
| dateSelected | 当用户开启选择日期触发 | selection |
