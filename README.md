# GamaniaView
a custom view library


/* a sample with set function value

  static showTestToast(String txt,f(String s)) {
    Fluttertoast.showToast(
        msg: txt,
        toastLength: Toast.LENGTH_LONG,
        gravity: ToastGravity.BOTTOM,
        timeInSecForIosWeb: 3,
        backgroundColor: Colors.black,
        textColor: Colors.orange,
        fontSize: 24.0).then((value) => f(txt));
  }
  ToastUtil.showTestToast('aaa', (String a){

  });

  static showTestToast(String txt,Function a) {
    Fluttertoast.showToast(
        msg: txt,
        toastLength: Toast.LENGTH_LONG,
        gravity: ToastGravity.BOTTOM,
        timeInSecForIosWeb: 3,
        backgroundColor: Colors.black,
        textColor: Colors.orange,
        fontSize: 24.0).then((value) => a);
  }
  ToastUtil.showTestToast('aa',  test() {

  });
   */
