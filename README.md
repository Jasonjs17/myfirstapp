
void main(){
//setup appTitle and hiFlutter article,
var apptitle = text('My first time creating an Flutter App'),
hiFlutter = Text(
'Hi, Flutter. ',
style: TextStyle(fontsize: 50),
);

//setup appBody article
Var appBody = center(
child: hiFlutter,
);

//setup appBar article
Var appBar = AppBar(
title: appTitle,
);

//setup app article
var app = MaterialApp(
home: Scaffold(
appBar: appBar,
body: appBody,
),
);

runApp (app);
}