# jsp_12 : Switch 문

![image](https://user-images.githubusercontent.com/37132897/158112510-14004a21-ac4a-4247-b129-7bc2cddf6e53.png)
- a의 값이 3이기 때문에, a가 3이 되는 case 3의 경우가 true가 되므로 출력문이 실행되어 3이 출력된다.

      // a의 값 3으로 지정
      
      var a = 3;
      
      switch (a) {
      
        case 1:
        
          document.write("1");
          
          break;
          
        case 2:
        
          document.write("2");
          
          break;
          
        case 3:
        
          document.write("3");
          
          break;
          
        default: // 만족하는 값이 없을 때 출력, if문의 else 와 비슷한 역할
        
          document.write("default");
          
