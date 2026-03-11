# Data-structure-program-15
#include<stdio.h>
#include<stdlib.h>
Struct Node{
 Int orderID;
 Struct Node *next;
};
Struct Node *front=NULL;
Struct Node *rear=NULL;
Void addOrder(int id){
 Struct Node 
*newNode=(struct 
Node*)malloc(sizeof(struct 
Node));
 newNode->orderID=id;
 newNode->next=NULL;
 if(rear==NULL){
 front=rear=newNode;
 }
 Else{
 Rear->next=newNode;
 Pending Orders:
201 202 203
Processing order: 201
Pending Orders:
202 203
