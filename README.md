        Node head = new Node(4);
        Node nodeB = new Node(4);
        Node nodeC = new Node(4);
        Node nodeD = new Node(4);
        Node nodeE = new Node(4);
        
        head.next = nodeB;
        nodeB.next = nodeB;
        nodeC.next = nodeD;
        nodeD.next = nodeE;
        
        countNodes(head);
        
        
        
        
        
        public class Node {
    int data;
    Node next;
    Node(int data) {
        this.data = data;
    }
}
