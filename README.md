# cutout_text_effect

<img src='https://raw.githubusercontent.com/lkrjangid1/cutout_text_effect/master/ex.png'>

Make cutout effect of your text in an easy way.

## Usage
`CutOutText` need at least one argument which is `text`

```dart
CustomPaint(
      painter: CutOutText(
        text: 'Hello World',
        textDirection: TextDirection.rtl,
        boxRadius: 10,
        boxBackgroundColor: Colors.blueAccent,
        textStyle: TextStyle(
          fontSize: 50.0,
          fontWeight: FontWeight.bold,
        ),
      ),
    );
```
