# applet-components
记录微信小程序开发用到的组件  
1. [圆形进度条](./circle) 

![圆形进度条](./image/circle.png)

```
<circle draw='circwewle' child='32' parent='36' r = '60'/>
```

2. [自定义导航栏](./cu-custom)

![自定义导航栏](./image/nav.png)

```
<cu-custom isBack="{{true}}"><view slot="backText">返回</view><view slot="content">请假申请</view></cu-custom>
```

2. [日期时间选择器](./datetime)

![日期时间选择器](./image/datetime.png)

```
<datetime isRequired="true" bind:dateTimePicker="onDateTimePicker" name='leaveStart' format='yyyy-MM-dd HH:mm' />
```