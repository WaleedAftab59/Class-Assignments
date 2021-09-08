void main(){
  var eng = 80;
  var urdu = 87;
  var isl = 77;
  var math = 88;
  var phy = 98;
  
  var obt_marks = eng + urdu + isl + math + phy;
  var per = (obt_marks/500)*100;
  
  print('----------------------------');
  print('--------Mark Sheet----------');
  print('----------------------------');
  print('English Obtain Marks ${eng}');
  print('Urdu Obtain Marks ${urdu}');
  print('Islamiat Obtain Marks ${isl}');
  print('Math Obtain Marks ${math}');
  print('Physics Obtain Marks ${phy}');
  print('Your Obtained Marks ${obt_marks}');
  print('Your Percentage ${per}');
  
  if (per>= 80)
  {
    print('You Got A+');
  }
  else if (per>= 70 && per < 80)
  {
    print('You Got A');
  }
    else if (per>= 60 && per < 70)
  {
    print('You Got B');
  }
    else if (per>= 50 && per < 60)
  {
    print('You Got C');
  }
    else if (per>= 40 && per < 50)
  {
    print('You Got D');
  }
  else
  {
    print('You are Fail');
  }
  

}