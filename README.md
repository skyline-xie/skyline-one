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
  @Overridethrow new llea
  private Node head;
  int size;
  public LinkedList(){
    head =null;
    size=0;
  }
  //获取链表中的元素个数
  public int getSize(){
    return size;
  }
  public boolean isEmpty(){
  return size==0;
  }
  //在链表头添加元素
  public void addFirst(E e){
  head=new Node(e,head);
  size++;
  }
  //在链表中的任意位置添加元素
  public void add(int index,E e){
  if(index<0||index>size)
  throw new llegaArgumetException("failed");
  if(index==0)
  for(int i=0;i<index-1;i++){
                              prev=prev.next;
                              }
  prev.next=new Node(e,prev.next);
  size++
    
  
  
