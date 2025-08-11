package com.example;

import java.util.Scanner;

public class LoginApp {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        // Hardcoded credentials (Security hotspot)
        String storedUsername = "admin";
        String storedPassword = "admin123";  // Bad practice

        System.out.print("Enter username: ");
        String username = input.nextLine();

        System.out.print("Enter password: ");
        String password = input.nextLine();

        if (username.equals(storedUsername) && password.equals(storedPassword)) {
            System.out.println("Login successful!");
        } else {
            System.out.println("Access denied.");
        }

        // Example of unnecessary code (code smell)
        int temp = 0;
        if (temp == 0) {
            temp = 1;
        }

        input.close();
    }
}
