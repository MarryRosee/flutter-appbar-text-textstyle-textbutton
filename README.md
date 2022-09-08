# flutter-appbar-text-textstyle-textbutton
flutter-appbar-text-textstyle-textbutton
  runApp(
    MaterialApp(
      home: Scaffold(
        backgroundColor: Colors.green,
        appBar: AppBar(
          backgroundColor: Colors.red,
          title: Text(
            "Home Screen",
            style: TextStyle(
              color: Colors.blue,
              fontSize: 18,
              fontWeight: FontWeight.bold,
              wordSpacing: 16,
              backgroundColor: Colors.yellowAccent,
            ),
          ),
        ),
        body: Center(
          child: TextButton(
              child: Text(
                "Login",
                style: TextStyle(
                  color: Colors.blue,
                  fontSize: 55,
                  fontWeight: FontWeight.bold,
                  wordSpacing: 4,
                  backgroundColor: Colors.pink,
                ),
              ),
              onPressed: () {}),
        ),
      ),
    ),
  );
