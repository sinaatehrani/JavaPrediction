import java.util.*;
import java.util.function.Predicate;

public class Exercise1 {
    public static void main(String[] args) {
        List<Apple> apples = Arrays.asList(
                new Apple(1),
                new Apple(2),
                new Apple(1),
                new Apple(8),
                new Apple(6),
                new Apple(5));
        List<Apple> filtered = filter(apples, a -> a.size>1);
        Collections.sort(apples,(a1,a2)->a1.size-a2.size );
        System.out.println(filtered);


        }
        static List<Apple>
        filter(List<Apple> list, Predicate<Apple> condition){

            List<Apple> result = new ArrayList<>();
            for(Apple apple : list){
            if (condition.test(apple))
                result.add(apple);
            }
                return result;

        }
}

class Apple{
    int size;
    public Apple(int size){
        this.size= size;
    }
}
