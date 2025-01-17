package diogonalelements;
public class Diogonalelements {
    public static void main(String[] args) {
        int[][] squareMatrix = {
            {1,2,3},
            {4,5,6},
            {7,8,9}
        };
        System.out.println("diogonal matrix:");
        for( int i = 0;i<squareMatrix.length;i++){
            System.out.println(squareMatrix[i][i]+"");
        }
        System.out.println();
    } 
}

Output

diogonal matrix:
1
5
9
