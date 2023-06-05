# EXP-02---PAWN-MOVEMENT
Developed by : Shobika P
Register No: 212221230096
## AIM:
To Create a player movement using pawn, collectible, player health, and score.

## PROCEDURE:
### To create and destroy the coin:
1.Create a new project in Unreal Engine and choose a template that suits your needs.

2.Add a new actor to the level and call it "Coin".

3.Create a new blueprint based on the Coin actor by selecting it in the Content Browser and choosing "Create Blueprint".

4.Open the Coin blueprint and add a static mesh component to represent the coin. You can import a 3D model or use one of the default shapes provided by Unreal Engine.

5.Add a collision component to the Coin blueprint so that the player can interact with it. Choose a simple collision shape like a sphere or a box.

6.Add a variable to the Coin blueprint to keep track of whether the coin has been collected or not. Call it "IsCollected" and set its default value to false.

7.Create a new blueprint based on the player character by selecting it in the Content Browser and choosing "Create Blueprint".

8.Open the player blueprint and add a collision component to represent the player's interaction with the coins.

9.Add an event to the player blueprint that gets triggered when the player collides with a coin. Use a collision event and check if the collided actor is a coin.

10.If the collided actor is a coin, check if it has already been collected. If not, set its IsCollected variable to true and add its value to a score variable in the player blueprint.

11.Remove the coin from the level by calling its Destroy function.

12.Add several instances of the Coin actor to the level and adjusttheir positions so that they are spread out and not too close to each other.
## Output:
### For Creating a Coin:
![p11](https://github.com/Shobika187/EXP-02---PAWN-MOVEMENT/assets/94508142/bd7082b5-cf5d-4d01-8b30-ca6b412f598f)
![image](https://github.com/Shobika187/EXP-02---PAWN-MOVEMENT/assets/94508142/2ed91533-75b4-4c2f-93a4-61483b08818c)
![image](https://github.com/Shobika187/EXP-02---PAWN-MOVEMENT/assets/94508142/842aa053-108c-4c9a-a4a7-9fdfaa5b092c)
![image](https://github.com/Shobika187/EXP-02---PAWN-MOVEMENT/assets/94508142/32760c29-ee28-4134-8255-37da5e47f184)
![image](https://github.com/Shobika187/EXP-02---PAWN-MOVEMENT/assets/94508142/a9a2f59b-ba92-4b2f-8552-84c2015ab0b5)



