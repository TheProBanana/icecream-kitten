# icecream-kitten

Icecream-kitten is my attempt at learning python by making a very simple "Artificial Intelligence". That is to say, I know the basics of how AIs learn, but know nothing on how to implement that or even start it. So i'm going to attempt to make an escape room where the computer tries to escape in anyway possible.

The basic run-down of this project is as follows:
    1. Using the console, create a tileset that can contain objects (e.g. chair, door, person, etc.).

        a. Create a list for the height of the room. This allows for us to stack objects on top of eachother.

            - I choose list, pythons version of an array, data structure because we need to be able to access each individual piece of data directly. 

        b. Create a set dimension list of the length and width of the room.

        c. Create a procedurally generate map using the room height, width, and lengths dimensions in the multidimensional list. Use unicode characters to represent different objects in the room.

    2. Allow objects to be moved.

        a. Get the starting list location of the object.

        b. Track each tile the object has entered.

        c. Get ending list location.

        d. Update map.

    4. Create a person that can walk around and interact with the objects.

        a. Character object that has a length, width, height.

        b. Movement controller that will allow the character to move around the room.

        c. Collision detection so the person cannot occupy the same tile as another large object.

        d. Inventory so person can carry items.
        
        e. Interaction controller that allows the person to interact with objects.

    5. Figure out how to make a basic learning machine for the person.

        a. Point system so that everytime the computer gets closer to finishing the puzzle, it'll get a point. 

        b. Make the point system mean something so the computer wants to get the most points possible. This will give the computer "intelligence" instead of it randomly doing actions until it completes the puzzle.

        c. Run multiple iterations (generations) of the computer. A generation of the computer should be a "better" version. Each generation should have multiple computers running at once, only taking the attributes of the ones that got the highest points. This is the learning aspect. This is needed so the final version of the computer is the fastest and most effective version at solving the puzzle. It will also have the best ability to solve puzzles it hasn't done before.

    6. Create puzzles for the person to solve to escape.

        a. Start off with one puzzle for the computer to learn the solution. It should be really simple.

        b. After successful completion of the first puzzle, run a few generations on it so the computer can learn.

        c. Create a second puzzle. This one should be more complicated, but still simple. 

        d. Run multiple generations on the second puzzle for learning.

        e. Run multiple generations on each puzzle.

        f. Create a third, complicated puzzle. It shouldn't be simple to allow the computer to have more learning room.


File structure:
