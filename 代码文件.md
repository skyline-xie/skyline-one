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
  Node prev=dummyHead;
  for(int i=0;i<index;i++){
                              prev=prev.next;
                              }
  prev.next=new Node(e,prev.next);
  size++
                              }
                            public void addFirdt(E e){
                            add(0,e);
                            }
                            public void addList(E e){add(size,e)}
                              public int getSize(){
                              dummyHead=new Node(null,null);
                              size=0;
                            puvlic E get(int index){
                            if(index<0||index>=size)
                               throw new llegaArgumetException("failed");
  Node cur=dummyHead.next;
  for(int i=0;i<index;i++)
                           cur=cur.next;
 return cur.e;
                           }
                           public boolean contains(E e){
                           while(cur!=null)
                           if(cuur.e.equals(e))
                           return ture;
                           cur=cur.next;
                           }
                           return false;
                           }
                           public E remove(int index){
                           if(index<0||index>=size)
                               throw new llegaArgumetException("failed");
  Node prev=dummyHead;
  for(int i=0;i<index;i++)
                           prev=prev.next;
                           prev.next=reNode.next;
                           reNode.next=null;
                           size--;
                           return reNode.e;}
                           //现在写一个LeetCode里面的题（203）
                           public LisNode removeElements(LisNode head,int val){
                           while(head!=null&&val==val){
                           LisNode delNode=head;
                           head=head.next;
                           delNode.next=null;}
                           if(head==null)
                           return null;
                           lisNode prev=head;
                           while(prve.next.val==val){
                           LidNode deNode=prev.neext;
                           prev.next=deNode.next;
                           }
                           else
                           prev=prev.next;
                           }
                           return head;
                           }
                           
                           
                            
                              
  
  
