# skyline-one
public class LinkedList<E>{
  public E e;
  public Node next;
  public Node (E e,Nede next){
    this.e=e;
    this.next=next;
  }
  public Node(E e){
     this(e,null)
  }
  public Node(){
     this(null,null);
  }
  
