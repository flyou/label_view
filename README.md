# label_view

## 1.import LableView.dart

> import 'package:label_view/LableView.dart';

## 2.use in Code

```
void main() {
   runApp(new MaterialApp(
     home: LabelViewDemo(),
   ));
 }
 
 class LabelViewDemo extends StatelessWidget {
   @override
   Widget build(BuildContext context) {
     return Scaffold(
       appBar: AppBar(
         title: Text("LabelViewDemo"),
       ),
       body: LabelView( Size(500, 100)),
     );
   }
 }
 ```


## desc of aattribute 

 > final Size size; //the size of labelView <br/>
 > final String labelText;// label text<br/>
 > final TextStyle textStyle;// label text style<br/>
 > final Color labelColor;// label color<br/>
 > final Color backgroundColor;// label background color<br/>
 > final bool useAngle;// use angele or false<br/>
 > final labelAlignment;// labelAlignment in widget<br/>
 
 
## picture

![](http://wx1.sinaimg.cn/mw690/0060lm7Tly1fwjjbakm0qj30p806f0sv.jpg)

![](http://wx3.sinaimg.cn/mw690/0060lm7Tly1fwkeqvqqqzj30u00c8t8n.jpg)


![](http://wx1.sinaimg.cn/mw690/0060lm7Tly1fwkeqvr10bj30u00c80sp.jpg)


![](http://wx1.sinaimg.cn/mw690/0060lm7Tly1fwkeqvr3uwj30u00c0749.jpg)


![](http://wx4.sinaimg.cn/mw690/0060lm7Tly1fwkeqvquo1j30u00c4mx3.jpg)

<br/>

![](http://wx4.sinaimg.cn/mw690/0060lm7Tly1fwkgh9lvntj30ci0m8q70.jpg)

**Contact me**

blog: [flutter.link](http://flutter.link)<br/>
email:  [email me](mailto:fangjaylong@gmail.com)

**License**

AdCountView is under the Apache2.0 license. See the [LICENSE](https://github.com/flyou/label_view/blob/master/LICENSE) file for details.