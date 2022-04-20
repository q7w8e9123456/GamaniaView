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
   
   
如果flutter命令不能跑，請新增bash_profile並新增以下(/Library是我放flutter的位置請自行修改)
export PATH=$PATH:/Library/flutter/bin
export PATH=$PATH:/Library/flutter/.pub-cache/bin


flare_flutter

https://ithelp.ithome.com.tw/articles/10233127?sc=rss.qu
