# Question-One1-
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Main.java to edit this template
 */
package roadaccidentreport;

/**
 *
 * @author ammaa
 */
public class RoadAccidentReport {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        
        // Prompt the user to populate & declare a single-dimensional array for the different cities
        String[] cities = {"Cape Town", "Johannesburg", "Port Elizabeth"};

        
        // Vehicle Types are stored as [Car, Motor Bike]
        // 3 cities, 2 types of vehicles
       int[][] vehicles = new int[3][2]; 
{
            
    }
        // Using a for loop,Prompt user to input car & bike accidents by declaring and populating a two-dimensional array for the vehicle types
        for (int i = 0; i < cities.length; i++) {
            System.out.print("Enter the number of car accidents for " + cities[i] + ": ");
            vehicles[i][0] = scanner.nextInt();
            System.out.print("Enter the number of motorbike accidents for " + cities[i] + ": ");
            vehicles[i][1] = scanner.nextInt();
        }


        
}
        // use a for loop to Print road accident totals for each city
               
        for (int i = 0; i < cities.length; i++) {
            System.out.println(cities[i] + " Car: " + vehicles[i][0] + " Motor Bike: " + vehicles[i][1]);
        }
           


        // Find the city with the highest number of road accidents using an if statement
            int maxDifference = 0;
        String cityWithMaxDifference = "";
        for (int i = 0; i < cities.length; i++) {
            int difference = vehicles[i][0] + vehicles[i][1];
            if (difference > maxDifference) {
                maxDifference = difference;
                cityWithMaxDifference = cities[i];
            }
        }


        // Step 5: Print the manufacturer with the greatest price difference
        System.out.println("The city with the highest number of road accidents i: : " + cityWithMaxDifference);
    

    
        
        
        
}     
  
