//documentation section
/* Fathiah Awanis , 21/6/2022, Liner Queue Array*/

//pre-processor section
#include<stdio.h>

//global variable section

//initialize variable
#define SIZE 8 //represent MAX size
int queue[SIZE]; //represent our queue array
int front, rear = -1; //remeber set front and rear index with default -1 

//1st function - enqueue
int enqueue(int value){
    if(rear == SIZE - 1){ //check queue is Full
        printf("Overflow Queue!");
    }
    else if(front == -1 && rear == -1){ //when front and rear index = -1, insert first element (5)
        front = 0;
        rear = 0;
        queue[rear] = value;
    }
    else{
        rear++;    //increase rear by 1 to add more element
        queue[rear]= value;   //store new element on rear
    }
}
    int dequeue(){
        if (front == -1 && rear == -1){         //check queue is empty or not
            printf("Queue is Empty");
        }
        else if(front == rear){
        int front = -1;
        int rear = -1;
        }
        else{
        
            printf("Delete value from the queue: %d \n", queue[front]); //display element
            front++;    //increase front by 1 to delete element
        }
    }

        int peek(){
            if(front == -1 && rear == -1){
                printf("Queue is Empty");
            }
            else{
                printf("Peek value in Queue is: %d\n", queue[front]);
            }
        }
        

        int main (){
            enqueue(5);
            enqueue(10);
            enqueue(15);
            enqueue(20);
            enqueue(25);
            dequeue();
            dequeue();
            peek();

            printf("Queue list is: ");
            //display queue in the list
            for(int i = front; i <= rear; i++){
                printf(" %d", queue[i]);
            }
        
         return 0;

        }
