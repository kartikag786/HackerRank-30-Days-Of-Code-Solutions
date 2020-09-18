def insert(self,head,data): 
    #Complete this method
        newNode = Node(data)
        if head == None:
            head = newNode
        else:
            temp = head
            while temp.next:
                temp = temp.next
            temp.next = newNode
        return head