# CreateClass
Initialize project CreateClass in another package called utilites

This program Calculator.java invokes methods of a another class MathHelper. Initially the MathHelper
class did not exist and therefore the methods were within the main class Calculator. The same methods
were later migrated into the class MathHelper. Strings inputted from user are pass as arguments to the
methods in which they are converted with the Double class into double numeric format in order to do
calculations. ie. double var = Double.parseDouble(string);

Also note that the new class MathHelper was created in a different package not under the same package
as the Calculator main class.
