# Skill-Tree-UE5
A simple Skill Tree that you can use in Unreal Engine 5

Create simple nodes that can be unlocked
Create trees by assigning neighbor nodes 
Includes a basic menu setup with each node and available currency/reward

# How to Create a Node

1. Open up the Skill Menu Blueprint in the content folder
2. In the Palette Tab in the User Created section drag in a "WB Skill Node"

# How to Create a Tree

1. For each node in your tree repeat the following:
2. In the "Default" section of the Node assign the previous node to something of your choice, if it is the first node in the tree set the corresponding bool to true
3. Assign the next nodes that can be unlocked after you unlock this node


### Credits: https://www.youtube.com/watch?v=198AMGtdo-E