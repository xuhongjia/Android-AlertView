[![Android Gems](http://www.android-gems.com/badge/saiwu-bigkoo/Android-AlertView.svg?branch=master)](http://www.android-gems.com/lib/saiwu-bigkoo/Android-AlertView)

# Android-AlertView
AlertViewController


## Demo
![](https://github.com/saiwu-bigkoo/Android-AlertView/blob/master/preview/alertviewdemo.gif)

gradle :
```java
   compile 'com.bigkoo:alertview:1.0.2'
```

### config in java code
```java
new AlertView("xx", null, "xx", null,
                new String[]{"xx", "xx"},
                this, AlertView.Style.ActionSheet, new OnItemClickListener(){
                    public void onItemClick(Object o,int position){
                        Toast.makeText(this, "xx" + position + "个", 
                        Toast.LENGTH_SHORT).show();
                    }
                }).show();
```
```java
new AlertView("xx", "xx", null, new String[]{"xx"}, null, this, 
                AlertView.Style.Alert, null).show();
```

