# one-stop-restaurant
A web app that will be a full service, kitchen, and product management experience for restaurants.

# Concept:
Main Idea Focuses on the Stages of the Restaurant Experince.
* Resturant Set Up
  * Table Locations
  * Capacity Max
  * Connected to Seating/Reservations 
* Reservations and Seating
  * Reservations Based on Total Number of People
  * Disability Based Seating
  * Event Flags (celebrations/birthdays/etc.)
  * Date Time Based on Resturant Hours  
* Menu and Ordering
   * Menu and Order Editing
   * Drink and Food Ingredient Databases
* Kitchen and Meal Edititng
   * Flags to Show Allegys
   * Edited Orders Flags

# Django Back-End:

* OOP will focus on micro-services
 * Resturant Micro:
   * Tables
   * Capacity
   * Hours
   * Reservations
  * Menu Micro:
   * Order
   * Drink
   * Allergens
  * Kitchen Micro:
   * Menu Database
   * Order Editing
   * Ingredient Database
   * Menu 86 Capabilities

# Next.js TailWind Front-End
 * Needs to have consistency in location of editing flags etc for efficiency in Server User expereince.
 * Choice of Light and Dark modes for server preference.
 * Previous screen/selection button (BACK BUTTON)
 * UNDO BUTTON 

# Creating Users
 * Manager Users
  * Ability to Edit Ingredient & Menu Databases
  * Will be able to influence Values/Payment amounts
 * Server Users
  * Able to Place Orders at Tables
  * Edit Orders using Flags
  * Order Drinks
 * Bartender Users
  * Edit Ingredient and Menu Database with Bar Flag
  * Edit Drink Orders
 * Customer User
  * Holds:
   * Past Orders
   * Past Allergens
   * Disabilities (if applicable)
