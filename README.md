package com.company;

import java.util.*;

public class rrr {
    public static void main(String[] args) {
    
    Scanner scr = new Scanner(System.in)
    
    int volume = Integer.parseInt(scr.nextLine());
    int pipe1 = Integer.parseInt(scr.nextLine());
    int pipe2 = Integer.parseInt(scr.nextLine());
    double hours = Double.parseDouble(scr.nextLine());
    double water = (pipe1 * hours) + (pipe2 * hours);
    
    if (water <= volume) {
    System.out.printf("The pool is %.0f%% full. Pipe 1 : %.0f%%. pipe 2: %.0f%%" ,Math.floor(water / volume * 100);
    Math.floor((pipe1 * hours) / water * 100),
    Math.floor((pipe2 * hours) / water * 100));
    
    }else{
    System.out.printf("For %f hours the pool overflows with %f litres.", hours,water - volume);
         }
        }
        
     }   
        
