public class SpeedConverter {
 
    public static long toMilesPerHour(double kilometersPerHour) {
        if (kilometersPerHour < 0) {
            return -1;
        }
        return Math.round(kilometersPerHour / 1.609);
    }
 
    public static void printConversion(double kilometersPerHour) {
        if (kilometersPerHour < 0) {
            System.out.println("Invalid Value");
            return;
        }
        long milesPerHour = toMilesPerHour(kilometersPerHour);
        System.out.println(kilometersPerHour + " km/h = " + milesPerHour + " mi/h");
    }

    public static void main(String[] args) {
        // Test cases
        printConversion(10.5);    // Output: 10.5 km/h = 7 mi/h
        printConversion(-5);      // Output: Invalid Value
        printConversion(25.42);   // Output: 25.42 km/h = 16 mi/h
        printConversion(75.114);  // Output: 75.114 km/h = 47 mi/h
    }
}
