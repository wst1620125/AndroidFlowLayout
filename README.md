# AndroidFlowLayout
A flow layout for Android

samples
----

![](http://img02.taobaocdn.com/imgextra/i2/160310864/TB2MH8.bVXXXXa3XXXXXXXXXXXX_!!160310864.png)


dependencies
----

* gralde

```groovy
compile(group: 'com.liangfeizc', name: 'flowlayout', version: '1.0.0', ext: 'aar')
```

or

```groovy
compile 'com.liangfeizc:flowlayout:1.0.0@aar'
```

* maven

```xml
    <dependency>
        <groupId>com.liangfeizc</groupId>
        <artifactId>flowlayout</artifactId>
        <version>1.0.0</version>
        <type>aar</type>
    </dependency>
```

usage
----

```xml
<com.liangfeizc.flowlayout.FlowLayout
    android:id="@+id/flow_layout"
    flowlayout:vertical_spacing="10dp"
    flowlayout:horizontal_spacing="10dp"
    android:layout_width="match_parent"
    android:layout_height="wrap_content" />
```
