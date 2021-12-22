import java.util.Random;

public class Uc2 {

        public static final int INITIAL_BET_STAKE = 100;
        public static final int BET_AMT = 1;

        public static void main(String[] args) {
            int remaining_amount = 0;
            Random random=new Random();
            int num=random.nextInt(2);
            System.out.println(num);
            if (num == 0) {
                remaining_amount = remaining_amount + BET_AMT;
                System.out.println("After winning bet" + remaining_amount);
            } else
                remaining_amount = remaining_amount - BET_AMT;
            System.out.println("After loosing bet" + remaining_amount);
        }
    }
