# linked-list-by-loops
I have make a prograame to print linked list by loops in java
package LinkedList;

public class basicsll  {
  


    public static class Node{
        int data; //value
        Node next; // address of next node
        Node(int data){
            this.data=data;
        }
    }
    public static void main(String[] args) {
        Node a =new Node(5);
        //System.out.println(a.next);//null
        Node b =new Node(3);
        Node c =new Node(9);
        Node d =new Node(8);
        Node e =new Node(4);
        /* 5-3-9-8-4 */
        a.next=b;// 5 is connected with 3
        b.next=c;
        c.next=d;
        d.next=e;

        // linked list by loop
//        Node temp=a; 
//        for(int i=1;i<=5;i++){
//            System.out.print(temp.data+ " ");
//            temp=temp.next;

        //While loop
//        Node temp=a;
//        while(temp!=null){
//            System.out.println(temp.data+" ");
//            temp=temp.next;

       


        }
}


