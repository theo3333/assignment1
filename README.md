# assignment1

The goal of this Bag of Marbles program is to have various ways to add and remove different variety of marbles from a bag. The marbles can be of different colors, different sizes, but no matter what properties, they should be removed or added to the bag at will. They can be removed one at a time. There can be an extremely small number or very large, in the millions of marbles added to an infintely sized bag.

We will start with our complete marble collection OUTSIDE the bag, whatever number it is.

Our PROPERTIES of the marbles can include:
Color (red, blue, green etc.)
Size (Small, Medium, Large):

class Marbles {
public:
    int color;
    int size;
    Marbles(int color, int size){

    };
    

BEHAVIORS of marbles:
Add specific marble to bag (random option?):
//Add various types of marbles to bag
        bag.AddMarb(Marbles(red, small));
        bag.AddMarb(Marbles(blue, medium));
        bag.AddMarb(Marbles(green, large));
        
Remove specific from bag (random option?):
//Remove various types of marbles from bag
        Marbles marbles = bag.RemoveMarb();
        
(Search for specific marble outside bag and see how many there are?)

Placing the marbles into the bag would involve the various combos of marbles existing: A red Large, Blue Small etc. marble can be selected and placed in the bag, which will be registered as in the bag.
Removing any marbles should react in a similar manner. For example, if you want to remove a Red Large, you remove it and place it back in your collection record:

cout <<"From the the bag, you draw a" << marbles.color << marbles.size << "marble." <<endl;
//Show marbles in bag number
        cout<<"Number of marbles in bag are:" << marbles.Bag() <<endl;
        return 0;

If there are no more Red Large marbles for example, the bag will read as out of Red Large. But there might be other marble combos there.

There will be 'int ' to represent the marbles properties of color and size, classes for both the Marble and Bag.  

For the bag properties, it's not as important as the marbles: just the size of the bag.
At the beginning of the program, we could request the user input 'How many MAX marbles should this bag hold?' Zero would be an error, but a number in the billions could be allowed. (Possibly stopping after 20 digits or less).

Testing: We could test input of both color and size, adding specific marbles, removing marbles from bag, marble numbers in bag. See what happens when removing all marble combos.
