# algorithm



public class DoWhile1 {
    public static void main(String[] args) {
        int i = 10;

      while (i < 3);
       System.out.println("현재 숫자는:" + i);
            i++;
    }
}

> Process finished with exit code 0
-----------------------------------------------------------------

public class DoWhile1 {
    public static void main(String[] args) {
        int i = 10;

        do {

            System.out.println("현재 숫자는:" + i);
            i++;

        } while (i < 3);
    }
}

> 현재 숫자는:10

Process finished with exit code 0


do-while 최초 한 번은 실행
코드 블럭 실행 후 조건식 검증
