
```dataviewjs
let setting = {};
//在和风天气中创建的 Api key
setting.key = "dc0f31ac6f37484f88e3e7d45b84e403";
setting.city = "";//城市名 为空自动定位
setting.icon = true;//是否显示图标true false
setting.days =7 ;//天气预报天数1-7
setting.headerLevel = 3;//添加标题的等级
setting.addDesc = true;//是否添加描述true false
setting.onlyToday = false;//是否只在当天显示
setting.anotherCity = "上海";//添加另外一个城市
//脚本文件 weatherView.js 所在路径
dv.view("88-Template/script/weatherView",setting)
```



