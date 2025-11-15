# GAME_PROGRAM-EXP-6

### Implement the AI random movement.
## Aim:
Implement the AI random movement.

## Algorithm:
Step:01 Create a Character Blueprint.

Step:02 Create a Blackboard.

Step:03 Open the Behavior Tree editor.

Step:04 Create Behavior Tree nodes for the following,  "Selector" node: Controls the execution of child nodes.  "Service" node: Monitors and updates values in the Blackboard.  "Sequence" node: Executes child nodes in sequential order.  "Random" decorator: Randomly selects a child node to execute.  "Move To" task: Moves the AI character to a specified location.

Step:05 Set up the Blackboard with vector key and bool keys and save it.

Step:06 Set up the AI character Blueprint with the help of AI controller component.

Step:07 Set the AI controller and behavior treeiIn the Possess node, select the AI Character Blueprint you created and drag off the AICharacter reference and search for “Use Blackboard”

Step:08 Set up the NavMesh and boundaries, we can adjust the size and position to cover the desired play area.

## Output:

<img width="1016" height="428" alt="image" src="https://github.com/user-attachments/assets/a0e3b59e-b12a-41c8-8b6b-c542f9cc71a6" />
<img width="1200" height="871" alt="image" src="https://github.com/user-attachments/assets/2a96b6aa-f912-48b9-bb1e-cd6c696cb1a6" />
<img width="1297" height="498" alt="image" src="https://github.com/user-attachments/assets/1e968736-6ba5-4cc3-aae6-91d6a041855e" />

## Result:
Thus, the AI concept to the actor for a random movement is implemented.
