```dart

body: RichText(
    text: TextSpan(
        style: TextStyle(
          color: Colors.blue,
          fontSize: 22,
        ),
        children: <TextSpan>[
      TextSpan(text: 'Hello'),
      TextSpan(
          text: 'Anya',
          style: TextStyle(
            fontSize: 44,
            color: Colors.red,
            fontWeight: FontWeight.bold,
            fontStyle: FontStyle.italic,
          )),
      TextSpan(
          text: 'Flutter',
          style: TextStyle(
            fontSize: 61,
            color: Colors.lightGreen,
            fontWeight: FontWeight.bold,
          ))
    ]))
    

```